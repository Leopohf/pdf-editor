# PDF Editor

PDF Editor is a simple and easy-to-use tool for opening and editing PDF files. This project consists of a back-end built with Java and a front-end built with Angular 17. It aims to provide basic functionalities such as viewing, editing, and saving PDFs, making it convenient for users to manage their documents.

## Features

- Open and view PDF files
- Edit text and images within PDF files
- Annotate PDFs with highlights, notes, and drawings
- Save edited PDF files
- User-friendly interface

## Installation

### Prerequisites

- Java Development Kit (JDK) 17 or higher
- [Maven](https://maven.apache.org/)
- [Node.js](https://nodejs.org/) 20.13.1 (LTS version)
- [Angular CLI](https://angular.io/cli) 18.0.1

### Steps

#### Back-end (Java)

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/pdf-editor.git
    ```
2. Change to the back-end project directory:
    ```bash
    cd pdf-editor/backend
    ```
3. Build the project using Maven:
    ```bash
    mvn clean install
    ```
4. Run the back-end application:
    ```bash
    java -jar target/pdf-editor-backend-1.0.jar
    ```

#### Front-end (Angular)

1. Change to the front-end project directory:
    ```bash
    cd pdf-editor/frontend
    ```
2. Install the required dependencies:
    ```bash
    npm install
    ```
3. Run the front-end application:
    ```bash
    ng serve
    ```
4. Open your web browser and navigate to `http://localhost:4200`.

## Usage

1. Access the application via your web browser at `http://localhost:4200`.
2. Open a PDF file using the file menu or drag and drop a file into the application window.
3. Use the editing tools to modify the document as needed.
4. Save your changes by selecting `Save` from the file menu.

## Contributing

We welcome contributions from the community. To contribute:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Description of your changes"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
5. Create a pull request explaining your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Apache PDFBox](https://pdfbox.apache.org/) for PDF rendering and manipulation
- [Swing](https://docs.oracle.com/javase/tutorial/uiswing/) for the back-end GUI
- [Angular](https://angular.io/) for the front-end framework

