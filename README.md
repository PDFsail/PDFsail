# pdfsail 🚢

**[pdfsail](https://www.pdfsail.com/)** is an open-source PDF processing library designed to simplify operations, parsing, and conversion of PDF files. Whether you need to convert a PDF to another format or extract information from a PDF, **pdfsail** makes it easy.

## 🚀 Features

- **PDF Conversion**: [Convert PDF](https://www.pdfsail.com/pdf-to-word) files to images or text.
- **[Text Extraction](https://www.pdfsail.com/pdf-ocr)**: Extract text, metadata, images, etc., from PDFs.
- **Page Operations**: Merge, split, rotate, crop pages, and more.
- **Cross-platform**: Supports all major operating systems (Windows, macOS, Linux).
- **High Performance**: Optimized performance, smooth operation even with large files.

## 📦 Installation

Install via Python’s package manager `pip`:

```bash
pip install pdfsail
```

## 💻 Usage Examples

Here are a few simple examples to get you started with **pdfsail**.

### 1. [Convert PDF to Image](https://www.pdfsail.com/pdf-to-jpg)

```python
from pdfsail import PDFToImage

# Convert PDF to images (one image per page)
pdf_to_image = PDFToImage("example.pdf")
pdf_to_image.convert("output_folder/")
```

### 2. Extract Text from PDF

```python
from pdfsail import PDFTextExtractor

# Extract text from PDF
pdf_text = PDFTextExtractor("example.pdf")
text = pdf_text.extract_text()
print(text)
```

### 3. [Merge PDF Files](https://www.pdfsail.com/merge-pdf)

```python
from pdfsail import PDFMerger

pdf_merger = PDFMerger()
pdf_merger.merge(["file1.pdf", "file2.pdf"], "output_merged.pdf")
```

## 🛠️ Tech Stack

- **Python**: Main development language.
- **PyPDF2**: For basic PDF operations.
- **Pillow**: For converting PDF pages to images.
- **PDFMiner**: For text extraction.

## 📄 Documentation & Help

- [Project Documentation](https://pdfsail.readthedocs.io) — Detailed API documentation and usage examples.
- [GitHub Issues](https://github.com/yourusername/pdfsail/issues) — Report bugs or request new features.

## 🤝 Contributing

We welcome contributions in any form! If you have suggestions or find a bug, feel free to submit a Pull Request or open an Issue.

1. Fork the project and clone it to your local machine.
2. Create a new branch.
3. Commit your changes.
4. Submit a Pull Request.

## 📝 License

The **pdfsail** project is licensed under the [MIT License](LICENSE).
