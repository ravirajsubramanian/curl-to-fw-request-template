# cURL to Request Template Converter

A simple web application that converts cURL commands to Freshworks Request Template format.

## Description

This tool helps developers quickly convert cURL commands into the Freshworks Request Template format, making it easier to integrate API calls into Freshworks products.

## Setup

1. Fork this repository
2. Clone your forked repository:
```bash
git clone https://github.com/ravirajsubramanian/curl-to-fw-request-template.git
cd curl-to-fw-request-template
```

## Usage

1. Install a local HTTP server (if you don't have one):
```bash
npm install -g http-server
```

2. Start the server:
```bash
http-server ./ -c-1
```

3. Open your browser and navigate to `http://localhost:8080`

4. Paste your cURL command and click "Generate Template"

## Making Changes

1. The main conversion logic is in `index.html`
2. Make your changes and test locally
3. Ensure all changes are working as expected

## Contributing

1. Create a new branch for your changes:
```bash
git checkout -b feature/your-feature-name
```

2. Commit your changes:
```bash
git add .
git commit -m "Description of your changes"
```

3. Push to your fork:
```bash
git push origin feature/your-feature-name
```

4. Open a Pull Request from your fork to the main repository

## License

GNU GENERAL PUBLIC LICENSE