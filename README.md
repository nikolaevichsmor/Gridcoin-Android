# Gridcoin Android

An Android companion app and Windows bridge (`GridcoinBridge.exe`) for monitoring and controlling your home Gridcoin Core node from your phone. It shows your live balance, staking status, BOINC research metrics, and transaction history, and lets you send GRC or lock and unlock your wallet for staking over local Wi-Fi or encrypted cloud relay.

Your `wallet.dat` and private keys never leave your PC. Initial pairing works strictly over a physical USB cable, all traffic between the phone and the bridge is end-to-end encrypted, and pairing keys are locked inside Windows DPAPI on the desktop and the hardware Android Keystore (`AES-256-GCM` with biometric and PIN protection) on the phone.
