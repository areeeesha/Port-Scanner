# Multi-Threaded Port Scanner

A fast, lightweight, and efficient multi-threaded TCP port scanner written in Python. This tool utilizes a `ThreadPoolExecutor` to concurrently scan a range of target ports on a specified host, logging the results both to the console and a local log file.

## Features
* **Multi-Threaded Performance:** Dynamically scales up to 100 concurrent workers for fast scanning.
* **Dual Logging:** Outputs clean, timestamps-enabled logs to both the terminal screen and `scan_result.log`.
* **Graceful Error Handling:** Robust handling for unknown hosts, connection timeouts, and refused connections.

## How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/areeeesha/Syntecxhub-Port-Scanner.git](https://github.com/areeeesha/Syntecxhub-Port-Scanner.git)
   cd Syntecxhub-Port-Scanner

This project is intended for educational purposes and was developed as part of a cybersecurity internship project at Syntecxhub
