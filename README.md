PDF Power Suite

A professional-grade PDF processing suite built directly into Microsoft Word using VBA. This tool provides a powerful, portable, and secure way to handle complex PDF workflows without needing to install third-party software or upload sensitive documents to cloud-based services.

Overview
PDF Power Suite brings enterprise-level PDF manipulation capabilities to your local desktop environment. By utilizing the Poppler engine and Word's internal PDF reflow capabilities, this tool ensures that your document processing remains private, local, and fully compliant with corporate End-User Computing (EUC) policies.

Features
Extract PDF to Images: Extract each page of a multi-page PDF into high-quality JPEG files.

Split PDF: Break multi-page PDFs into individual single-page files.

Merge Images to PDF: Combine multiple images into a single PDF document.

PDF Binder: Merge multiple PDF files into one master PDF.

Text Extraction: Pull raw text directly from PDFs into a .txt file.

Watermarking: Apply dynamic text watermarks (e.g., "Confidential," "Specimen") with customizable transparency and colors using a native Windows color picker.

Batch Processing: Handle folder-level operations for high-volume tasks.

PNG Extraction: Extract images at high resolution (300 DPI) for high-quality printing.

Remove Pages: Easily delete specific pages or ranges from a PDF.

Extract Embedded Images: Retrieve original, high-resolution embedded images directly from PDF structures.

Convert to Word: Convert PDF documents into editable .docx files using Word's native engine.

Metadata Viewer: View technical info, page counts, and metadata of PDF files.

Extract Specific Pages: Extract only the pages you need into a new PDF.

System Requirements & Setup
Mandatory Dependency
This tool relies on the Poppler open-source PDF engine to perform its heavy-duty processing tasks.

Setup: Ensure the poppler folder is located in the same directory as the PDF_Power_Suite.docm file.

Warning: Do not rename or move the files inside the poppler folder, as this will break the connection between the VBA engine and the processing binaries.

Security & Privacy
100% Local Processing: Your documents never leave your machine. No data is sent to external servers or cloud APIs.

Portable: The tool does not require administrator privileges or installation of system-wide software.

Automated Cleanup: All temporary rasterized files are automatically deleted by the system immediately after processing.

How to Use
Macro Enabled: Upon opening the file, ensure you click "Enable Content" if Word prompts you with a security warning regarding macros.

Main Interface: The tool is designed with a user-friendly interface. Open the main menu to select your desired feature.

About/Help: Click the [?] button on the tool's interface to view security details and dependency information at any time.

Support & Troubleshooting
If a feature fails: Double-check that the poppler folder is in the same directory as this document.

Security Blocks: If macros are not firing, check File > Options > Trust Center > Trust Center Settings > Macro Settings to ensure macros are permitted.

Developed as an internal utility for streamlined document workflow management.
