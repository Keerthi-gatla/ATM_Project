# ATM Machine using PYTHON

Welcome to the ATM Machine project! This project simulates an ATM machine that allows users to perform various banking operations such as checking account balance, withdrawing cash, depositing cash, and changing their PIN.

## Table of Contents

- [Introduction](#introduction)
- [Technology Stack](#technology-stack)
- [Features](#features)
- [Installation](#installation)
- [Environment Setup](#environment-setup)
- [Usage](#usage)
- [Contact](#contact)
- [License](#license)

## Introduction

This project simulates an ATM machine in a console-based application. Users can log in with their username and PIN to perform banking operations. It includes features such as balance inquiry, cash withdrawal, cash deposit, and PIN change.

## Technology Stack

- **Programming Language**: Python
- **Libraries Used**: None (Standard Python Libraries)

## Features

- Console-based user interface
- User authentication with username and PIN
- Balance inquiry
- Cash withdrawal
- Cash deposit
- PIN change

## Installation

1. Clone this repository to your local machine:
    ```sh
    git clone https://github.com/your-username/atm-machine.git
    ```
2. Navigate to the project directory:
    ```sh
    cd atm-machine
    ```

## Environment Setup

1. **Install Python:**
    - Download and install Python from the official website: [Python Downloads](https://www.python.org/downloads/)
    - Follow the instructions for your operating system (Windows, macOS, Linux).

2. **Verify the Installation:**
    - Open a terminal or command prompt.
    - Type `python --version` or `python3 --version` and press Enter to verify the installation. You should see the installed version of Python.

3. **Create a Virtual Environment (optional but recommended):**
    - Navigate to the project directory:
        ```sh
        cd atm-machine
        ```
    - Create a virtual environment:
        ```sh
        python -m venv venv
        ```
    - Activate the virtual environment:
        - **Windows**:
            ```sh
            venv\Scripts\activate
            ```
        - **macOS/Linux**:
            ```sh
            source venv/bin/activate
            ```

4. **Install Required Packages:**
    - Once the virtual environment is activated, install any required packages (if applicable) using pip:
        ```sh
        pip install -r requirements.txt
        ```

## Usage

1. Run the ATM script:
    ```sh
    python atm_machine.py
    ```
2. Follow the on-screen prompts to interact with the ATM machine.

### How to Use

1. **Login:**
   - Enter your username.
   - Enter your 4-digit PIN.

2. **Main Menu:**
   - Select from the following options:
     - **Statement**: Check your account balance.
     - **Withdraw**: Withdraw cash from your account.
     - **Deposit**: Deposit cash into your account.
     - **Change PIN**: Change your account PIN.
     - **Quit**: Exit the ATM system.

3. **Perform Operations:**
   - Follow the prompts for each operation. For example, enter the amount to withdraw or deposit, confirm PIN changes, etc.

## Contact

For any queries or support, feel free to reach out:

- **Email**: [keerthi.ece.software@gmail.com](mailto:keerthi.ece.software@gmail.com)
  
## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

