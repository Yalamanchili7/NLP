# Contract Information Extraction with Flask and GraphQL

This repository contains a Flask application that extracts and classifies information from PDF contracts using Natural Language Processing (NLP). The application provides a REST endpoint and a GraphQL endpoint to access the extracted information.

## Features

- Extract text from PDF contracts
- Identify and extract parties, dates, and payment terms
- Classify contract clauses (e.g., Term, Obligation, Payment)
- Provide a REST API for file upload and information extraction
- Provide a GraphQL API for flexible queries

## Technologies Used

- Flask: Web framework
- Flask-GraphQL: Integration of GraphQL with Flask
- graphene: GraphQL library for Python
- PyMuPDF: Library to extract text from PDF files
- spaCy: NLP library
- scikit-learn: Machine learning library for clause classification
- nltk: Natural Language Toolkit

## Installation

### Prerequisites

- Python 3.x
- pip (Python package installer)
- Git (for cloning the repository)
