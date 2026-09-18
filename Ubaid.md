1. Functional Requirements (FRs)
FR-01: The system shall allow authenticated Mission Control operators to send movement commands to the rover.

FR-02: The rover shall receive and execute valid commands sent by Mission Control.

FR-03: The rover shall report its current position, battery level, temperature, and communication status to Mission Control.

FR-04: The rover shall enter Safe Mode within 3 seconds when
battery temperature exceeds the critical threshold or
battery capacity falls below the defined emergency level.

FR-05: The system shall reject invalid or unauthorized commands before they are sent to the rover.

FR-06: Mission Control shall receive the execution status of each command sent to the rover.

2. Non-Functional Requirements (NFRs)
NFR-01: The system shall continue operating normally during temporary communication interruptions and shall recover when communication is restored.

NFR-02: Only authenticated Mission Control operators shall be permitted to issue rover commands.

NFR-04:
The system shall support at least 20 simultaneously
connected rovers.

NFR-04: The system shall support communication with multiple rovers simultaneously.
