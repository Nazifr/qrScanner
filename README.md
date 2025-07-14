# QR Code Scanner

A simple web-based QR code scanner built with HTML, CSS, and JavaScript using the html5-qrcode library.

## Features

- Real-time QR code scanning using device camera
- Clean and responsive user interface
- Automatically opens scanned URLs in a new tab
- Cross-platform compatibility (works on desktop and mobile)

## Demo

The scanner automatically starts when you open the page and grant camera permissions. Simply point your camera at a QR code to scan it.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Nazifr/qrScanner.git
   cd qrScanner
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000`

## Usage

1. Open the application in your web browser
2. Grant camera permissions when prompted
3. Point your camera at a QR code
4. The decoded result will appear below the scanner
5. If the QR code contains a URL, it will be displayed as a clickable link

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- [html5-qrcode](https://github.com/mebjas/html5-qrcode) library
- http-server for local development

## Browser Compatibility

This application requires a modern browser with camera access support:
- Chrome 53+
- Firefox 50+
- Safari 11+
- Edge 79+

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
