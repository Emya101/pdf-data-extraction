# PDF Data Extraction

A small Python/PyMuPDF learning project demonstrating word-level extraction from PDF documents, including page numbers, word order, text blocks, lines, and bounding-box coordinates.

## Files
- `pdf_data_extraction.ipynb` — runnable notebook
- `sample-sdf-document.pdf` — **synthetic** three-page example, created for this public project (not the original sample used during the exercise)

## Run
```bash
pip install -r requirements.txt
jupyter notebook pdf_data_extraction.ipynb
```
Run cells from top to bottom. Results in this public version refer to the synthetic sample document.

## Skills shown
Python loops, dictionaries, PyMuPDF, PDF metadata, layout-aware word extraction.

## Limitations
This is a text-based extraction demo, not OCR and not a complete Safety Data Sheet parser. PDFs containing only scanned images won't yield useful words without OCR. The original PDF was not supplied for publication.
