# I/O Mapping

This file documents the signal mapping between Factory I/O Warehouse, MX OPC, and GX Works3 PLC.

| Tag Name | PLC Address | Type | Factory I/O Device / Function |
|---|---:|---|---|
| emergency | X0 | BOOL Input | Emergency Stop |
| stop | X1 | BOOL Input | Stop Button |
| start | X2 | BOOL Input | Start Button |
| home | X3 | BOOL Input | Home / Reset signal |
| atload | X4 | BOOL Input | At Load Sensor |
| robotsensor | X5 | BOOL Input | Diffuse Sensor 0 / Robot Sensor |
| aleftsensor | X6 | BOOL Input | At Left Sensor |
| amidsensor | X7 | BOOL Input | At Middle Sensor |
| arightsensor | X8 | BOOL Input | At Right Sensor |
| moveXsensor | X9 | BOOL Input | Moving X Sensor |
| moveZsensor | XA | BOOL Input | Moving Z Sensor |
| stoplamp | Y0 | BOOL Output | Stop Light |
| startlamp | Y1 | BOOL Output | Start Light |
| resetlamp | Y2 | BOOL Output | Reset Light |
| entryconeyor | Y3 | BOOL Output | Entry Conveyor |
| loadconveyor | Y4 | BOOL Output | Load Conveyor |
| forkleftmove | Y5 | BOOL Output | Forks Left |
| forklift | Y6 | BOOL Output | Lift |
| forkrightmove | Y7 | BOOL Output | Forks Right |
| alarm | Y8 | BOOL Output | Alarm |
| Target | D0 | WORD | Target Position |

## Communication

| Item | Value |
|---|---|
| OPC Server | Mitsubishi.MXOPC.6 |
| Polling Time | 1000 ms |
| Access | Read / Write |
