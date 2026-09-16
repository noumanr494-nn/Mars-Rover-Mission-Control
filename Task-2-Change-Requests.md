# Task 2: Change Requests

## CR-01 — Emergency Safety

### Original Requirement

FR-04:

The rover shall enter Safe Mode when a critical battery or thermal condition is detected.

### Updated Requirement

The rover shall enter Safe Mode within 3 seconds when battery temperature exceeds the critical threshold or battery capacity falls below the defined emergency level.

### Change Explanation

The original requirement did not specify a time limit.

The new requirement specifies:

- Safe Mode within 3 seconds
- Critical battery temperature threshold
- Emergency battery capacity level

This makes the requirement more measurable and testable.

---

## CR-02 — Mission Expansion

### Original Requirement

NFR-04:

The system should support communication with multiple rovers simultaneously.

### Updated Requirement

The system shall support at least 20 simultaneously connected rovers.

### Change Explanation

The original requirement did not specify the number of rovers.

The new requirement specifies a minimum of 20 connected rovers, making it measurable and testable.

---

## CR-03 — Security Upgrade

### Original Requirement

NFR-02:

Only authenticated Mission Control operators shall be permitted to issue rover commands.

### Updated Requirement

The system shall require authenticated and role-authorized operators before accepting rover commands.

### Change Explanation

The original requirement checked only authentication.

The new requirement requires both:

1. Authentication
2. Role authorization

This provides a stronger access-control requirement.

---

# Final Requirements After Changes

| ID | Type | Final Requirement |
|---|---|---|
| FR-01 | Functional | The rover shall receive commands from Mission Control and execute valid commands. |
| FR-02 | Functional | The rover shall report its position, battery level, temperature, and communication status. |
| FR-03 | Functional | The system shall allow authenticated operators to issue commands. |
| FR-04 | Functional | The rover shall enter Safe Mode within 3 seconds during critical battery or thermal conditions. |
| FR-05 | Functional | The system shall reject invalid or unauthorized commands. |
| FR-06 | Functional | Mission Control shall receive command execution status. |
| FR-07 | Functional | The system shall record commands and critical rover events with timestamp and operator ID. |
| NFR-01 | Non-Functional | The system shall continue operating despite temporary communication interruptions. |
| NFR-02 | Non-Functional | The system shall require authenticated and role-authorized operators. |
| NFR-03 | Non-Functional | Command processing should normally complete within 5 seconds. |
| NFR-04 | Non-Functional | The system shall support at least 20 simultaneously connected rovers. |
