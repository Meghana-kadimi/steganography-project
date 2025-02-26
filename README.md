**Steganography Project**

**Overview**
This project is a **GUI-based steganography application** that allows users to securely hide and retrieve secret messages in images. It is built using **Python, Tkinter for the GUI, OpenCV for image processing, and PIL for image handling**.

**Features**
- **Select an image**: Users can choose an image from their file system.
- **Encrypt a message**: Hide a secret message inside the selected image.
- **Decrypt a message**: Retrieve the hidden message from the encrypted image.
- **Password protection**: Users must enter a password for encryption and decryption.
- **GUI-based interface**: A user-friendly graphical interface for easy interaction.

**Technologies Used**
- **Python**
- **Tkinter** (GUI)
- **OpenCV (cv2)** (Image Processing)
- **PIL (Pillow)** (Image Handling)
- **NumPy**

**Installation**
**Prerequisites**
Ensure you have **Python 3.8+** installed on your system. You can download it from [Python's official website](https://www.python.org/).
  
**Install Required Packages**
Run the following command to install dependencies:
```sh
pip install opencv-python numpy pillow tkinter
```

**How to Run the Application**
1. **Clone or download** the project repository.
2. **Navigate** to the project directory:
   cd internship-project/Stenography
3. **Run the application**:
   python stegography.py
   

Usage Instructions
**1. Select an Image**
Click the **"Select Image"** button to choose an image file (PNG, JPG, or JPEG).

**2. Encrypt a Message**
- Enter the **secret message** in the input field.
- Enter a **password** to secure the encryption.
- Click **"Encrypt"** to embed the message into the image.
- The encrypted image is saved as `encryptedImage.png`.

**3. Decrypt a Message**
- Click **"Decrypt"** to extract the hidden message.
- The application will prompt the **decrypted message** in a pop-up window.

**File Structure**
Stenography/
│-- stegography.py       # Main Python script
│-- pic1.jpg            # Background image for the GUI
│-- encryptedImage.png  # Encrypted image (Generated after encryption)
│-- README.md           # Documentation


**Troubleshooting**
"ModuleNotFoundError: No module named 'cv2'"
Run:
pip install opencv-python

**"Invalid Image File" Error**
Ensure the selected image is in **PNG, JPG, or JPEG** format.

 **License**
This project is open-source and can be modified as needed.

**Author**
MEGHANA KADIMI

