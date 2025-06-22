# 📚 PDF Splitter

A simple and user-friendly Python script to split a PDF file into two parts at a specified page.

## ✅ Features

- Splits any PDF file into two parts.
- Easy to use via command line.
- Automatically creates output directory if not found.
- Clear instructions and beginner-friendly.

## 🛠️ Requirements

- Python 3.x
- `PyPDF2` library

Install the required library using:

```bash
pip install PyPDF2
```

## 🚀 Usage

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/pdf-splitter.git
cd pdf-splitter
```

2. **Run the Script**

```bash
python pdf_splitter.py
```

3. **Follow the Prompts**

- Enter the path of your PDF file.
- Enter the page number where you want to split it.
- Enter the output directory where split files should be saved.

## 🧠 How It Works

### `split_pdf` Function

```python
def split_pdf(input_pdf, output_dir, split_page):
```

- **input_pdf**: Full path to the source PDF file.
- **output_dir**: Directory where the split files will be saved.
- **split_page**: Page number at which to split the PDF
