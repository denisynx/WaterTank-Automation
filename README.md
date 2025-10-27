# 💧 Water Tank Automation Project

### Technologies:

-   **OpenPLC** – main control logic (Modbus TCP server)
-   **Factory I/O** – 3D simulation environment
-   **Node-RED** – SCADA dashboard + data logging
-   **SQLite** – database for historical data

### Architecture:

    Factory I/O ↔ OpenPLC ↔ Node-RED ↔ SQLite

### Features:

-   Real-time water level visualization
-   Pump control (auto/manual)
-   Data logging to SQLite
-   Simple SCADA dashboard

### How to Run:

1. Open OpenPLC Runtime → load `main.st`
2. Run Factory I/O → use Modbus TCP client (127.0.0.1:502)
3. Start Node-RED → import `flow.json`
4. Open Dashboard: `http://127.0.0.1:1880/ui`
