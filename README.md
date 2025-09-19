# Excel to JSON Converter

This is a simple, single-page web application that converts data from an Excel file (`.xlsx` or `.xls`) into a structured JSON format. It's a convenient tool for quickly preparing data for use in web applications or APIs without needing any server-side processing.

---

## Features

* **Direct Conversion:** The application converts your Excel data to JSON right in your browser, ensuring your data remains private.
* **Common Format Support:** It works with both `.xlsx` and `.xls` file formats.
* **Instant Preview:** After uploading a file, you can immediately see the generated JSON data in a readable format.
* **Copy to Clipboard:** A single click on the copy button allows you to copy the entire JSON output for easy use.
* **User-Friendly Interface:** The application has a clean, modern design with a simple file upload process.

---

## How to Use

1.  **Open the File:** Open the `index.html` file in your web browser.
2.  **Upload File:** Click the "Click to upload your Excel file" area or drag and drop an `.xlsx` or `.xls` file onto it.
3.  **View JSON:** The application will automatically read the data from the **first sheet** of your Excel file and display the converted JSON in the text area below.
4.  **Copy Data:** Click the copy icon in the top right of the JSON output box to copy the entire JSON text to your clipboard.

---

## Technologies Used

* **HTML5:** Used for the foundational structure of the web page.
* **Tailwind CSS:** Provides the utility-first CSS framework for a responsive and modern design.
* **JavaScript:** Handles the core logic, including file input, data conversion, and user interactions.
* **SheetJS (xlsx):** A powerful, open-source JavaScript library that reads and parses the Excel file data.

---

## License

This project is open-source and available under the **MIT License**.
