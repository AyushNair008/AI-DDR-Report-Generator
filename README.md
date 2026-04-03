# AI-DDR-Report-Generator
## Description
This project builds an AI-powered system that converts building inspection and thermal reports into a structured Detailed Diagnostic Report (DDR).
It processes raw PDF data, extracts insights, and generates a professional report with identified issues, root causes, and recommended actions.
## Features
- PDF text extraction using pdfplumber
- Thermal image extraction using PyMuPDF
- LLM-based report generation (Gemini/OpenAI)
- Structured DDR output
- Image-integrated reporting
## Workflow
1. Upload Inspection + Thermal PDFs
2. Extract text and images
3. Process inputs through LLM
4. Generate structured DDR
5. Export final report
## TechStack
- Python
- Google Colab
- pdfplumber
- PyMuPDF
- Google Gemini API / OpenAI API
## Limitations
- Does not directly interpret images (manual mapping used)
- Depends on the extracted text quality
## Future Improvements
- Automated thermal image interpretation
- Structured JSON pipelines
- Validation and consistency checks

**“The system is designed to be model-agnostic and can integrate with multiple LLM providers.”**
