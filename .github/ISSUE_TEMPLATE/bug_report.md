---
name: Bug report
about: Create a report to help us improve

---

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. 

**Desktop (please complete the following information):**
 - OS: [e.g. iOS]
 - Browser [e.g. chrome, safari]
 - Version [e.g. 22]

**Versions and OS**
Describe your OS and provide the output of the following commands:
- ``bash --version``
- ``awk --version``
- ``grep --version``
- ``ag --version``
- ``xargs --version``
- ``xxh64sum --version``
- ``pdftotext -v``

**Filenames**
Is the behavior correct when run from a directory with only PDFs that have ASCII filenames?

**pdftotext**
Try the command ``pdftotext -f 1 -l 2 some_of_your_pdf.pdf`` with some of your PDF. Does it extract the first two pages as expected?
