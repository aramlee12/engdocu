## Mermaid library

```mermaid
graph TD;
A(START) --> B(Check temperature);
B-->C(Is the roo hot?)
C-->|Yes|D(Turn on Air conditioner)
C-->|No|E(Turn off Air conditioner)
```

```mermaid
gantt
    title A Gantt Diagram
    dateFormat YYYY-MM-DD
    section Section
        A task          :a1, 2014-01-01, 30d
        Another task    :after a1, 20d
    section Another
        Task in Another :2014-01-12, 12d
        another task    :24d
```

# MatJax
$$\ lambda = \frac {v}{f}$$

# vega-lite
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
