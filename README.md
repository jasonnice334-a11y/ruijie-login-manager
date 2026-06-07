# Ruijie Login Manager (Obfuscated)

This repository contains an obfuscated Python script (`nay.pyc`) designed to automate the login process for Ruijie networks using a voucher system. The original key-based authentication system has been removed, and the code has been compiled into bytecode (`.pyc`) for basic obfuscation.

## Features

*   **Key System Removed**: The original Google Sheet-based key authentication and time integrity checks have been removed.
*   **Code Obfuscation**: The Python script has been compiled into bytecode (`.pyc`) to make it harder to read and reverse-engineer.
*   **Automated Login**: Automates the process of detecting the gateway, fetching a session ID, and logging in with a provided voucher.

## Usage

### Prerequisites

*   Python 3 installed on your system.

### How to Run

1.  Download the `nay.pyc` file from this repository.
2.  Open your terminal or command prompt.
3.  Navigate to the directory where you saved `nay.pyc`.
4.  Run the script using Python:

    ```bash
    python3 nay.pyc
    ```

5.  The script will prompt you to enter your voucher code:

    ```
    Enter Voucher Code : 
    ```

6.  Enter your voucher code and press Enter.

## Disclaimer

This script is provided as-is. The obfuscation method used (Python bytecode compilation) is a basic form and can be reversed with sufficient effort. It is intended to make the code less immediately readable, not to provide strong security against determined attackers. Use at your own risk.

---

**Manus AI**
