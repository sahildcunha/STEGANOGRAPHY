# INTERN ID: CITS4048 

#  Steganography Tool 

A simple Python project that hides and retrieves secret messages inside images using LSB (Least Significant Bit) technique along with basic AES encryption for security.

---

##  Features

- Hide secret messages inside PNG images  
- Retrieve hidden messages from images  
- Password-protected encryption  
- Capacity check before encoding  
- Simple command-line interface  

---

##  Technologies Used

- Python 3  
- Pillow  
- Cryptography (Fernet)  

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/loisFernandes/STEGANOGRAPHY_TOOL.git

Go to project directory:
cd STEGANOGRAPHY_TOOL

Install required libraries:
pip install -r requirements.txt

Run the program:
python stego_tool.py

Encoding a Message
Choose option 1
Enter image path (PNG only)
Enter secret message
Enter password
Enter output file name

Example:

Enter choice: 1
Image path: sample.png
Secret message: hello world
Password: 1234
Output file: output.png

Decoding a Message
Choose option 2
Enter image path
Enter password

Example:

Enter choice: 2
Image path: output.png
Password: 1234
