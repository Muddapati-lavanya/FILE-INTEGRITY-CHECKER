# FILE-INTEGRITY-CHECKER

*COMPANY*:CODTECH IT SOLUTIONS

*NAME*:LAVANYA MUDDAPATI

*INTERN ID*:CT08DN1958

*DOMAIN*:CYBER SECURITY

*DURATION*:8 WEEKS

*MENTOR*:NEELA SANTOSH

The File Integrity Checker is a Python-based tool designed to ensure that files remain unaltered and trustworthy over time. This task is part of the CodTech internship program, aimed at helping interns learn and apply real-world cybersecurity and file management concepts using Python programming.
File integrity means that the contents of a file remain unchanged and exactly as originally saved. If even a single character is modified, added, or deleted, the file's integrity is compromised. Ensuring file integrity is especially important in cybersecurity, backup systems, and version control, where the authenticity of files must be verified to detect unauthorized or accidental modifications.
Tools and Technologies Used:
Python Programming Language:
Python was chosen for its simplicity and rich standard library, making it ideal for scripting and automation tasks like file hashing.
hashlib Module:
This built-in Python library provides access to many secure hash functions such as SHA-256.
It allows the tool to generate a unique fingerprint (hash value) for each file.
json Module:
Used to save and load hash values in a structured format.
The tool creates a file named file_hashes.json to store the hash values of the files to be monitored.
Visual Studio Code (VS Code):
A powerful and lightweight code editor used to write, run, and debug the Python script.
It offers great extensions and integration with Python interpreters for efficient development.
Command Line / Terminal:
Used to run the script and interact with the user through a simple menu-driven interface.
How the File Integrity Checker Works
The process begins by asking the user to provide the path of a file they want to monitor. The script then performs one of two actions:
Save Hash (Option 1):
The script reads the file in binary mode and calculates its SHA-256 hash.
This hash is saved in a JSON file, linking it with the file's path.
This stored hash represents the file's original, unaltered state.
Check Integrity (Option 2):
When the user chooses to verify the file’s integrity, the script re-calculates the hash of the file.
It then compares the current hash with the one stored previously.
If both hashes match, the file has not been changed.
If the hashes differ, the tool alerts the user that the file has been modified.
This project is a practical introduction to data security and validation. It shows how even simple tools can provide a strong foundation for detecting file tampering, malware infections, or corruption. By using cryptographic hash functions, the tool ensures that file verification is both accurate and secure.
CONCLUSION:
The File Integrity Checker project teaches key skills in Python programming, file handling, and cybersecurity. Using tools like hashlib and json, the project demonstrates how to build a simple yet effective solution for monitoring file changes. It’s a foundational step toward more advanced topics like digital signatures and intrusion detection systems.

*OUTPUT

![Image](https://github.com/user-attachments/assets/e51f3123-0314-4de4-a664-24b5c5ff7a62)













