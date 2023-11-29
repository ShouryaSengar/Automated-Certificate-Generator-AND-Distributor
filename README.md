# Certificate Generator & Distributor

 [Live Link !!](https://shouryasengar.github.io/Automated-Certificate-Generator-AND-Distributor/).

This project is a Certificate Generator and Distributor developed during a 1-month internship for DIGIBHEM. The system allows users to upload a blank certificate template, dynamically add details such as name, date, and description, and place these fields on the certificate face using Canvas.js and Joystick.js. The generated certificates include a unique QR code for verification purposes.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Dynamic Certificate Generation:** Upload a blank certificate template and dynamically add details to generate unique certificates.

- **Field Placement:** Use Joystick.js to precisely place and position certificate details.

- **QR Code Verification:** Each certificate includes a unique QR code for easy verification.

- **Printing and Email Distribution:** Completed certificates can be printed or distributed to recipients via email.

## Technologies Used

- **JavaScript:** Core scripting language for dynamic content generation and interaction.
- **HTML/CSS:** Structure the web interface and styling.
- **Canvas.js:** Create and manipulate canvas elements for dynamic certificate generation.
- **Joystick.js:** Precise placement of fields on the certificate face.
- **DOM (Document Object Model):** Manipulate the document structure to update and display certificate details.
- **certificate-generator:** Custom tool/module used for managing the generation and distribution of certificates.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/ShouryaSengar/Automated-Certificate-Generator-AND-Distributor.git
```

2. Navigate to the project directory:

   ```bash
   cd Automated-Certificate-Generator-AND-Distributor
   ```
3. Open Live server to start project

## Usage 📝

### 4. Upload Blank Certificate Template:

On the web interface, use the "Upload Template" feature to upload a blank certificate template. Ensure the template is in a compatible format.

### 5. Add Certificate Details:

Fill out the provided form with the necessary details for the certificate, such as the recipient's name, date, and description.

### 6. Field Placement with Joystick.js:

Utilize the Joystick.js functionality to precisely position and place the added details on the certificate face. This ensures accurate and aesthetically pleasing certificate layouts.

### 7. Generate Certificate:

Click the "Generate Certificate" button to initiate the dynamic generation process. The system will use Canvas.js to incorporate the provided details onto the certificate template.

### 8. QR Code Verification:

Each generated certificate includes a unique QR code. Users can scan this QR code to verify the authenticity of the certificate.

### 9. Print Certificate:

After generating the certificate, users have the option to print the certificate directly from the web interface. This is useful for creating physical copies of certificates for distribution.

### 10. Distribute via Email:

Alternatively, users can choose to distribute the generated certificate to recipients via email. This is a convenient way to share digital copies of certificates.

### 11. Explore Additional Features:

Familiarize yourself with additional features and tools provided by the certificate-generator module. These may include customization options, export functionalities, and more.


## License 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
