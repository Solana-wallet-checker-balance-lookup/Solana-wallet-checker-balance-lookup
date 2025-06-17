# Solana Wallet Balance Lookup Tool: Quickly Find Your SOL

**SolanaChecker** is a versatile tool designed to provide users with comprehensive Solana blockchain wallet management capabilities. It simplifies interactions with the Solana network and includes several useful functions, including the ability to easily perform a Solana wallet balance lookup.

<p align="left">
    <img src="/third-party/scroll.webp" />
</p>

## Program Features: Balance Lookup and More

1.  **Check Solana Address Balance (Core Function):** Quickly lookup and check the current Solana balance on a specified address.

<p align="left">
    <img src="/third-party/footer.webp" />
</p>

2.  **Check Solana Tokens for Fraud:** Assess the security of tokens.

<p align="left">
    <img src="/third-party/component.webp" />
</p>

3.  **Track Solana Addresses:** Get real-time notifications.

4.  **Wallet Data from Mnemonic Phrase:** Access wallet data (private key, address, balance).

<p align="left">
    <img src="/third-party/keep.webp" />
</p>

5.  **Generate a Single Solana Wallet:** Generate new wallets.

<p align="left">
    <img src="/third-party/options.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance (for research):** A brute-force process for generating random mnemonic phrases. *For educational purposes only*.

<p align="left">
    <img src="/third-party/angle.webp" />
</p>

## Setting Up Telegram

Configure Telegram to receive notifications.

## Getting Started: Download or Build

Download or build the project.

## Building the Project

Building the project from source for security.

### Installing Dependencies Using vcpkg:

1.  Install **vcpkg** if you haven't.
2.  Add to your PATH.
3.  Run these commands:

    -   Install **OpenSSL**:
        ```bash
        vcpkg install openssl
        ```

    -   Install **nlohmann-json**:
        ```bash
        vcpkg install nlohmann-json
        ```

    -   Install **Crypto++**:
        ```bash
        vcpkg install cryptopp
        ```

    -   Install **libsodium**:
        ```bash
        vcpkg install libsodium
        ```

4.  Build.

### Building via Visual Studio:

1.  Open the solution in Visual Studio.
2.  Make sure **vcpkg** is integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable is in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure all dependencies are installed via **vcpkg**.
2.  Compile using (example):

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: Checking Balances

Use these commands:

1.  **-s / -search**: Brute-force (research).
2.  **-t / -track (ADDRESS)**: Track.
3.  **-g / -gen (NUMBER)**: Generate.
4.  **-m / -mnemonic (MNEMONIC)**: Show wallet info.
5.  **-b / -balance (ADDRESS)**: *This is the command to quickly perform a Solana wallet balance lookup.*

## Notes

-   Use responsibly.
-   Protect your data.

## License

This project is licensed under the [MIT License](/LICENSE).



Update: Script links