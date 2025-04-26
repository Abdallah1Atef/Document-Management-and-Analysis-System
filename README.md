# 📄 Document Management and Analysis System

## Overview
This project is a Python-based **Document Management System** designed to import, store, search, and analyze documents within a **MongoDB** database. It supports multiple file formats including **PDF**, **DOCX**, and **TXT**, and offers advanced features such as document similarity analysis and detailed text analytics.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Future Enhancements](#future-enhancements)

## ✨ Features
- **File Import:**  
  Import and store documents (PDF, DOCX, TXT) in MongoDB using GridFS, enabling scalable storage and retrieval.
  
- **File Management:**  
  Manage documents by deleting or updating records in the database as needed.
  
- **Document Search:**  
  Perform efficient searches based on metadata (filename, upload date, modification date) and document content. Supports multi-condition combination searches.
  
- **Text Analysis:**  
  Automatically extract and display detailed metadata, including:
  - Word count
  - Character count
  - Page count
  
- **Document Similarity Comparison:**  
  Compare two documents using various similarity metrics:
  - Cosine Similarity
  - Jaccard Similarity
  - Euclidean Distance
  
- **User Interface:**  
  Provides an intuitive **Command-Line Interface (CLI)** for seamless user interaction.

## 🛠️ Technologies Used
- **Python** — Core programming language.
- **MongoDB** — NoSQL database for storing documents and metadata.
- **GridFS** — Efficiently stores and retrieves large documents in MongoDB.
- **PyPDF2** — Extracts text and metadata from PDF files.
- **python-docx** — Processes DOCX files for text extraction.
- **NLTK (Natural Language Toolkit)** — Handles text processing, tokenization, and stopword removal.
- **win32com.client** — Interfaces with Microsoft Word to access advanced DOCX metadata.

## 📚 Future Enhancements
- Develop a web-based user interface (UI) for enhanced accessibility.
- Implement document versioning and edit tracking.
- Add machine learning models for document classification.
