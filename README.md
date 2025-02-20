# IBM-Cyberseurity-Internship

**Steganography-Based Secure Data Transmission System**

**Overview**

In the era of increasing cyber threats, ensuring secure data transmission is crucial. This project leverages steganography and encryption to embed sensitive information within images and DOCX files, making it invisible to unauthorized users. By implementing hybrid encryption techniques, it ensures confidentiality, integrity, and security in covert communication.

**Features**

✅ **Dual File Type Steganography **– Supports both image-based and DOCX-based data hiding.
✅** Hybrid Encryption** – Uses AES, RSA, or other encryption methods before embedding for enhanced security.
✅ **Key-Based Extraction** – Only authorized users with the correct decryption key can retrieve hidden information.
✅ **Optimized Payload Management** – Ensures secure data embedding without compromising file integrity.
✅ **User-Friendly Implementation** – Designed for easy encryption and decryption of hidden messages.

**Technologies Used**

**Programming Language:** Python

**Libraries:** OpenCV, Pillow, Stegano, Cryptography, Python-docx

**Platforms:** IBM SkillsBuild, Jupyter Notebook/PyCharm

**Installation & Setup**

**1. Clone the Repository**

git clone https://github.com/YeshitaMotwani/IBM-Cybersecurity-Internship.git
cd IBM-Cybersecurity-Internship

**2. Install Required Dependencies**

pip install opencv-python pillow stegano cryptography python-docx

**3. Run the Encryption & Decryption Scripts**

To Encrypt & Hide Data:

python encrypt_hide.py

To Extract & Decrypt Data:

python decrypt_extract.py

Usage Instructions

Encrypt & Hide Data in an Image/DOCX

Select an image (PNG/JPG) or a DOCX file.

Input the secret message to be hidden.

The data is encrypted before embedding.

The output is a stego-image or modified DOCX that appears unchanged.

Extract & Decrypt Data

Upload the stego-image or DOCX.

Enter the decryption key.

Retrieve the hidden message securely.

**End Users**

👨‍💻 **Cybersecurity Professionals** – Secure covert communication.
📰 **Journalists & Whistleblowers** – Protect sensitive sources.
🏛️ **Government & Defense Agencies** – Ensure classified document security.
🏢 **Corporate Firms & Legal Professionals** – Safeguard intellectual property and business data.
🕵️ **Ethical Hackers & Security Researchers** – Learn and test steganography techniques.

**Future Enhancements**

🚀 **GUI-Based Web App** – Develop an interactive React + Flask/Django interface.
📱 **Mobile App Integration** – Implement secure steganography in Android/iOS.
☁️ **Cloud-Based Secure Storage** – Use AWS/Firebase for encrypted file storage
🗂️ **Multi-File Format Support** – Expand to PDF, audio, and video steganography.
🔑 **Blockchain-Based Key Management** – Store encryption keys securely.💬 Secure Encrypted Messaging System – Enable steganography-based chat.

**Contributors**

👤 Yeshita – Developer & Cybersecurity Intern📧 Email: yeshita.motwani2006@gmail.com 


**Acknowledgments**

🙏 AICTE IBM SkillsBuild Cybersecurity Internship for mentorship & learning.

