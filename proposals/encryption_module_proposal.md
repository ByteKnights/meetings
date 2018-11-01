# Sandboxed Encryption Device

**Abstract**: With advanced malware attacks on secure messaging applications, sandboxing the secure parts of the application to a separate piece of hardware removes attack vectors. Therefore, creating a device that encrypts the text, and sends the cipher text to the phone which then sends the encrypted message via the internet.

**Parts**:
* Microcontroller (encrypts message)
* Photon (transmits data from cloud to Microcontroller)
* Input device (Keyboard)
* Output device (Screen showing typed message)
* Cable (Connects device to phone)

**How It Works**

*Creating and signing a message*
1. Receive public keys, and names them to a party
2. Types a message, choices which key to sign with
3. Transmits cipher text to device with messaging application

*Unencrypting messages*
1. Receive cipher-text from messaging app
2. Unencrypt cipher-text with private key
3. Display unencrypted message on LCD screen

![diagram](https://github.com/ByteKnights/meetings/blob/master/assets/sandbox_diagram.png)
