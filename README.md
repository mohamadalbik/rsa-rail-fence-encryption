# Java Encryption & Decryption Tool

A desktop encryption application built in Java with a graphical user interface that combines two classic encryption algorithms — **RSA** and **Rail Fence Cipher** — into a single toolkit. Users can apply each algorithm independently or combine them together for layered encryption.

## Features

- **Three-tab GUI** for organized workflow:
  - **Tab 1 — Combined:** Apply both RSA and Rail Fence algorithms together on a single message
  - **Tab 2 — RSA Only:** Encrypt and decrypt messages using the RSA algorithm
  - **Tab 3 — Rail Fence Only:** Encrypt and decrypt messages using the Rail Fence cipher
- Clean and intuitive graphical interface
- Supports text input of any length

## Algorithms

### RSA (Rivest–Shamir–Adleman)
A widely used public-key cryptographic algorithm based on the mathematical difficulty of factoring large prime numbers. Used for secure data transmission in countless real-world systems.

### Rail Fence Cipher
A transposition cipher that rearranges the plaintext characters in a zigzag pattern across a number of "rails" (rows), then reads off each row to produce the ciphertext. A classic algorithm often used to teach the fundamentals of cryptography.

### Combined Mode
Applies both algorithms sequentially — the message is first encrypted with one algorithm, then the result is passed through the other. This demonstrates the concept of layered encryption for enhanced security.

### Sreenshots 

<img alt="photo_1_2026-06-24_04-39-03" src="https://github.com/user-attachments/assets/69019e86-6492-4254-8e03-db86c8cd707e" width = "300" height = "300" /><br>
<img alt="photo_3_2026-06-24_04-39-03" src="https://github.com/user-attachments/assets/3d5b7892-3024-47a7-af2c-e2604b23f6f9" width = "300" height = "300" /><br>
<img alt="photo_2_2026-06-24_04-39-03" src="https://github.com/user-attachments/assets/6309653e-aff5-46f7-82f7-3bf3b5920b96" width = "300" height = "300" />


## How to Run

### Prerequisites

- Java JDK 8 or higher

### Run the Application

1. **Clone this repository:**
   ```
   git clone https://github.com/mohamadalbik/rsa-rail-fence-encryption.git
   cd java-encryption-tool
   ```

2. **Compile:**
   ```
   javac Main.java
   ```

3. **Run:**
   ```
   java Main
   ```

## Usage

1. Select the desired tab (Combined, RSA, or Rail Fence)
2. Enter your message in the input field
3. Enter the number of Rails for rail fence algo and/or the bitlength for RSA 
4. Click **Encrypt** to encrypt the message
5. Click **Decrypt** to decrypt it back
6. View the result in the output field



## Notes

- The GUI requires a desktop environment to run
- RSA key generation may take a moment for longer key lengths
- This project was built for educational and demonstration purposes

## About This Project

Built as a cryptography course project to demonstrate the implementation and practical application of two fundamental encryption algorithms — a modern public-key algorithm (RSA) and a classical transposition cipher (Rail Fence) — combined into a single interactive desktop application.
