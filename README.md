invoice-generator/
│
├── public/
│   ├── index.html
│   └── ...
│
├── src/
│   ├── components/
│   │   ├── InvoiceForm.js
│   │   ├── InvoicePreview.js
│   │   └── ...
│   ├── App.js
│   ├── index.js
│   └── ...
│
├── package.json
├── README.md
└── ...
# Invoice Generator - React App

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

An Invoice creator project built with React. Add itemized items, configure quantity, prices, tax rates, and discounts. Download invoices as PDFs to your device. Uses [jspdf-react](https://www.npmjs.com/package/jspdf-react) to capture the data from the modal and convert it from canvas to PDF.

### Screenshots

<img src="https://i.imgur.com/wRetnxk.png" style="width: 100%; height: auto;">
<img src="https://i.imgur.com/AZChaei.png" style="width: 100%; height: auto;">
<img src="https://i.imgur.com/Bz3K3DE.png" style="width: 100%; height: auto;">

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Artreeus/react-report
    ```
2. Install dependencies:
    ```sh
    npm install
    ```
3. Start the development server:
    ```sh
    npm start
    ```
4. For production build:
    ```sh
    npm run build
    ```

### To-Do
- [x] Finish parsing data into Preview Modal
- [x] Currency Picker
- [x] Calculate Tax and Discounts
- [ ] Store invoices in Firebase DB

### Meta

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file
