# Custom QR Code Generator

A simple and modern web application that generates custom QR Codes with optional logo support.

## Features

* Generate QR Codes from any URL
* Upload a custom logo to display in the center of the QR Code
* High error correction level (H) for better logo compatibility
* Rounded QR Code styling
* Download generated QR Codes as PNG images
* Responsive and lightweight design
* No backend required

## Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla)
* QR Code Styling Library

## Getting Started

### 1. Download the Project

Clone or download the repository:

```bash
git clone https://github.com/your-repository/custom-qrcode-generator.git
```

### 2. Open the Application

Simply open the `index.html` file in your browser.

No installation or build process is required.

## Usage

### Generate a QR Code

1. Enter a valid URL in the input field.
2. (Optional) Select a logo image from your computer.
3. Click **Generate QR Code**.
4. The QR Code will be displayed on the screen.

### Download the QR Code

After generating a QR Code:

1. Click **Download PNG**.
2. The QR Code will be saved to your device.

## Configuration

The QR Code appearance can be customized inside the JavaScript configuration:

```javascript
dotsOptions: {
    color: "#000000",
    type: "rounded"
}
```

### Supported Dot Styles

Examples:

* square
* rounded
* dots
* classy
* classy-rounded
* extra-rounded

### Error Correction Level

The generator uses:

```javascript
errorCorrectionLevel: "H"
```

This provides the highest level of error correction, making it ideal for QR Codes with embedded logos.

## Browser Support

Tested on:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

## Dependencies

The project uses the QR Code Styling library:

```html
<script src="https://cdn.jsdelivr.net/npm/qr-code-styling/lib/qr-code-styling.js"></script>
```

## Project Structure

```text
project/
│
├── index.html
├── README.md
└── assets/
```

## Notes

* Large logos may reduce QR Code readability.
* For best results, keep the logo size between 20% and 25% of the QR Code area.
* Always test generated QR Codes before printing or sharing.

## License

This project is released under the MIT License.

Feel free to use, modify, and distribute it for personal or commercial projects.
