# Mars Rover Mission Control

## Task 1: Analyze the Engineering Note

### Functional Requirements

| ID | Requirement |
|---|---|
 FR-01  The rover shall receive commands from Mission Control and execute valid commands. 
 FR-02  The rover shall report its current position, battery level, temperature, and communication status. 
 FR-03  The system shall allow only authenticated Mission Control operators to issue commands. 
 FR-04  The system shall reject invalid or unauthorized commands. |
 FR-05  The rover shall enter Safe Mode when a critical battery or thermal condition is detected. 
 FR-06  Mission Control shall receive the command execution status. |
 FR-07  The system shall record all commands and critical rover events with timestamp and operator ID. 

### Non-Functional Requirements

| ID | Requirement |
|---|---|
 NFR-01  The system shall continue operating despite temporary communication interruptions. 
 NFR-02  Only authenticated Mission Control operators shall be permitted to issue rover commands. 
 NFR-03  Command processing should normally complete within 5 seconds after a command is received by the rover. 
 NFR-04  The system should support communication with multiple rovers simultaneously. 

---
