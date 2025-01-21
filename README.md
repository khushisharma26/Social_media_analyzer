# Social_media_analyzer
The Social Media Analyzer is a web-based application that allows users to upload PDF, image files and extracts text from them. Built using React for the frontend and Node.js with Express for the backend, the app leverages the pdf-parse library for PDF parsing and Tesseract.js for Optical Character Recognition (OCR) on image files.
Features
Drag-and-drop or file picker interface for uploading files.
Extracts text from:
PDF Files: Maintains text formatting.
Image Files: Uses Optical Character Recognition (OCR) to extract text.
Loading indicator during the file processing phase.
Displays extracted text in a clean, readable format.
Technologies Used
Frontend
React: User interface development.
Dropzone.js: For drag-and-drop file uploads.
Axios: For HTTP requests to the backend.
Backend
Node.js and Express: Server and API development.
Multer: For handling file uploads.
pdf-parse: For extracting text from PDF files.
Tesseract.js: For OCR processing of image files.
Setup and Installation
Prerequisites
Node.js and npm installed on your system.
A code editor like Visual Studio Code.
Steps to Run the Project
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/your-username/document-text-extractor.git
cd document-text-extractor
Backend Setup:

Navigate to the backend folder and install dependencies:
bash
Copy
Edit
cd backend
npm install
Start the server:
bash
Copy
Edit
node index.js
Server runs on http://localhost:5000/.
Frontend Setup:

Navigate to the frontend folder and install dependencies:
bash
Copy
Edit
cd frontend
npm install
Start the React app:
bash
Copy
Edit
npm start
App runs on http://localhost:3000/.
Usage
Open the app in your browser (http://localhost:3000/).
Drag and drop or select files (PDFs or images).
Click on the "Analyze" button to extract text.
View the extracted text in the app.
Project Structure
bash
Copy
Edit
document-text-extractor/
├── backend/
│   ├── index.js         # Backend server code
│   ├── package.json     # Backend dependencies
│
├── frontend/
│   ├── src/
│   │   ├── App.js       # React application logic
│   │   ├── index.js     # React entry point
│   ├── package.json     # Frontend dependencies
│
├── README.md            # Project documentation
Screenshots
File Upload Interface

Extracted Text Display

Future Enhancements
Add support for additional file formats like DOCX.
Multi-language OCR support.
Improved UI/UX for better user experience.
Enhanced error handling and notifications.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

