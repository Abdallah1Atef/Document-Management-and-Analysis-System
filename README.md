# Document Management and Analysis System

This project is a Python-based document management system that allows users to import, search, and analyze documents stored in a MongoDB database. It supports various file formats (PDF, DOCX, TXT) and provides advanced features such as document similarity comparison and text analysis.

## Features

- **File Import**: Import and store documents (PDF, DOCX, TXT) in a MongoDB database using GridFS.
- **File Management**: Delete documents from the database.
- **Document Search**: Search documents based on metadata (name, upload date, modify date) or content. Supports combination searches with multiple conditions.
- **Text Analysis**: Extract and display metadata such as word count, character count, and page count for each document.
- **Document Similarity**: Compare two documents using Cosine Similarity, Jaccard Similarity, and Euclidean Distance metrics.
- **User Interface**: Command-line interface (CLI) for easy interaction with the system.

## Technologies Used

- **Python**: Core programming language.
- **MongoDB**: Database for storing documents and metadata.
- **GridFS**: For storing large files in MongoDB.
- **PyPDF2**: For extracting text and metadata from PDF files.
- **docx**: For extracting text from DOCX files.
- **NLTK**: For text processing and stopword removal.
- **win32com.client**: For interacting with Microsoft Word to extract metadata from DOCX files.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/document-management-system.git
   cd document-management-system
   
