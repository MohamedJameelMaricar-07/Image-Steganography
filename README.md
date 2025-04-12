# Image Steganography

This project implements **Image Steganography**, a technique for securely hiding messages within images. The goal is to embed hidden text or data within an image file, which can later be extracted without altering the visual appearance of the image. This ensures secure communication, as the hidden information is not visible to the naked eye.

## Features
- Embed text into an image using the Least Significant Bit (LSB) method.
- Extract hidden text from an image without any loss of data.
- Support for different image formats (e.g., PNG, BMP).
- Simple Python implementation with a focus on security and efficiency.

## Technologies Used
- **Python**: The main programming language.
- **Pillow**: Python Imaging Library for image processing.
- **Tkinter** (optional): For GUI-based interaction.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/jameelmaricar711/image-steganography.git
   cd image-steganography
   pip install -r requirements.txt
   Usage
Embedding Text into an Image
Run the following Python script to embed text into an image:

bash
Copy
Edit
python embed_text.py --image input_image.png --text "Your secret message here"
This will create a new image (output_image.png) with the hidden message embedded.

Extracting Text from an Image
To extract the hidden message from the image:
                         python extract_text.py --image output_image.png
The hidden text will be displayed in the console.

#Example
Input Image: input_image.png

Hidden Message: "This is a secret."

Output Image: output_image.png (Visually identical to the input image)

After extracting from output_image.png, the message "This is a secret." will be recovered.

Contributing
Feel free to fork this project, submit issues, or create pull requests. Contributions are welcome!

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For any questions, feel free to reach out to me at jameelmaricar711@gmail.com.











