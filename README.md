# QR Code Generator

The **QR Code Generator** is a web application designed to generate QR codes instantly based on user-provided text or URLs. With a simple yet powerful interface, this project offers a seamless way to create QR codes for various purposes such as website links, contact details, or text messages. Built using Node.js, Express, and EJS, the application combines speed, accuracy, and flexibility to deliver a smooth user experience.

## Features
- **Instant QR Code Generation:** Generates QR codes instantly upon user input.
- **Dynamic Input Handling:** Accepts URLs, text, and other types of data.
- **Customizable QR Codes:** Flexible sizing and format options.
- **Downloadable QR Codes:** Users can download the generated QR codes as image files.
- **Responsive Design:** Clean and intuitive interface ensuring smooth functionality across devices.

## Technologies Used
- **Frontend:**
  - HTML
  - CSS
  - EJS (Embedded JavaScript) for dynamic content rendering.
- **Backend:**
  - Node.js
  - Express.js
- **Libraries & Tools:**
  - `qrcode` (for QR code generation)
  - `body-parser` (for handling POST request data)
  - `dotenv` (for managing environment variables)
- **Other References:**
  - `.env` file for secure database and configuration handling.

## Project Structure
```
/QR-Code-Generator
├── /public          # Static files (CSS, Images)
├── /views           # EJS templates for dynamic content rendering
├── index.js         # Main server logic
├── package.json     # Project dependencies
├── package-lock.json # Dependency lock file
└── .env             # Environment variables for configuration
```

## Installation and Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Bhargav13304/QR-code-Generator.git
   cd QR-code-Generator
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure environment variables:**
   - Create a `.env` file in the root directory.
   - Add the following details:
     ```env
     PORT=3000
     ```

4. **Start the application:**
   ```bash
   node index.js
   ```

5. **Access the application:**
   - Open your browser and visit `http://localhost:3000`

## Usage
- **Generate QR Code:** Enter a URL or text in the input field and click "Generate" to create the QR code.
- **Download QR Code:** Click the "Download" button to save the generated QR code as an image file.

## Additional Notes
- Ensure all dependencies are installed properly before starting the application.
- The `.env` file should be kept secure and excluded from public repositories for security reasons.

