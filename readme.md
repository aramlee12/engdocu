## Mermaid library


### Flow Diagram<!-- Flow diagram -->
```mermaid
graph LR;
A(START) --> B(Check temperature);
B-->C{Is the room hot?}
C-->|Yes|D(Turn on Air conditioner)
C-->|No|E(Turn off Air conditioner)

classDef whiteBackground fill:#FFFFFF,color:#000,stroke-width:0px;
linkStyle 0,1 stroke:#000,stroke-width:2px;
class Yes whiteBackground;
class No whiteBackground;
```

### Gantt Chart<!-- Gantt Chart -->
```mermaid
gantt
    title Aram's project schedule
    dateFormat YYYY-MM-DD
    section Feasibility
        Planning          :a1, 2014-01-01, 30d
        Brainstorming    :after a1, 20d
    section Initial prototype
        Initial Design :2014-01-12, 12d
        Prototype    :24d
```

## MatJax
$$\ lambda = \frac {v}{f}$$

## vega-lite
```vega-lite
{
  "mark": "line",
  "data": {
    "url": "simple.csv"
  },
  "encoding": {
    "x": {
      "field": "time(s)",
      "type": "quantitative"
    },
    "y": {
      "field": "distance(m)",
      "type": "quantitative"
    } 
  }
}
```
also check out vega project

# sequence diagram

```mermaid
  sequenceDiagram
  MCU->>Sensor: Start
  MCU->>Sensor: Slave address
  Sensor->>MCU: Ack
  MCU->>Sensor: Data
  ```
