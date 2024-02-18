# Python module - PDF toolkit

The PDF Toolkit Python module provides a set of functions to perform various operations on PDF files. These operations include combining selected PDFs into one, slicing PDFs into smaller segments, inserting pages from one PDF into another, combining selected pages to create a new PDF, and removing unnecessary pages based on specified criteria.



## Prerequisites:
To use the PDF Toolkit module, ensure you have Python installed on your system along with the PyPDF2 library.
1. install [python3.7](https://www.python.org/downloads/release/python-372/)
2. install [pyPDF2 library](https://pypi.org/project/PyPDF2/)

## Functions
There are 6 operations which can be done. Most of the input and output is handled with help of `Tkinter` visualization.

None of the functions require any parameters.
><b>The module can do the following operations</b>:
>
>`merge()`: Combine selected pdfs into one.\
>`sub_pdf()`: Get a sliced piece of pdf which can have one or more pages.\
>`delete_pages_by_range()`: Slice out a set of pages and combine the rest of pdf.\
>`insert_at_position()`: Inserting pages of one pdf into another at a specified position.\
>`merge_pages()`: Combine selected pages of a pdf to create a new pdf.\
>`delete_pages()`: Remove unnecessary pages from pdf with respect to page numbers.\

Move the `pdf.py` file to the location where all the python modules and libraries are in your PC.
For example:
```
C:/Users/MOHAMMED RIYAZUDDIN/AppData/Local/Programs/Python/Python37/Lib
```

## Usage
Once this module is moved into the `Lib` folder, it can be used via `cmd` or `shell` as:
```
from pdf import *
sub_pdf()
```

## GUI
The module provides GUI built with tkinter for easier selection of files. The GUI is specified within the functions.

## Acknowledgement
This module utilizes the `PyPDF2` library for PDF manipulation and `Tkinter` for GUI development.

## Support
For any kind of queries, issues, feedbacks or inquiries, contact to riyazuddin9846@gmail.com

## Contribution
Contributions are welcome! Feel free to fork the repository and send pull requests.

## TODO
1. Enable it to be used by applications(Ex: web apps, desktop apps,..)
2. File format conversion(Ex: txt to pdf, excel to pdf, image to pdf,..)
3. Ensure cross-platform compatibility.
4. Performance optimization for better developer experience.
5. Looking forward to collaborations with developer community for feedback and improvement.