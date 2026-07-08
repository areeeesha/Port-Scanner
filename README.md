# Python Port Scanner

A multithreaded TCP port scanner built with Python. The scanner checks a range of ports on a target host and reports whether each port is open, closed, timed out, or produced an error. Results are displayed in the terminal and saved to a log file.

---

## Features

- Multithreaded scanning using ThreadPoolExecutor
- Hostname to IP address resolution
- Detects:
  - Open ports
  - Closed ports
  - Timed-out ports
  - Socket errors
- Saves scan results to `scan_result.log`
- Console and file logging
- Configurable port range

---

## Technologies Used

- Python 3
- socket
- logging
- concurrent.futures
- datetime

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Port-Scanner.git
```

Move into the project folder:

```bash
cd Port-Scanner
```

---

## Running the Program

```bash
python port_scanner.py
```

Example:

```
Enter the host to scan: scanme.nmap.org
Enter the starting port number: 20
Enter the ending port number: 100
```

---

## Output

Example:

```
PORT 22: OPEN
PORT 23: CLOSED
PORT 80: OPEN
PORT 81: TIMEOUT
```

A complete log is also saved to:

```
scan_result.log
```

---

## Project Structure

```
Port-Scanner/
│── port_scanner.py
│── README.md
│── requirements.txt
│── .gitignore
```

---

## Learning Objectives

This project demonstrates:

- Python socket programming
- TCP networking
- Multithreading
- Exception handling
- Logging
- Basic cybersecurity concepts

This project is intended for educational purposes and was developed as part of a cybersecurity internship project at Syntecxhub
