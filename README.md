# NuBIS-OCR

## Description
This is a ground truth dataset for a selection of printed books from [NuBIS](https://nubis.bis-sorbonne.fr/), the digital library of the Bibliothèque Interuniversitaire de la Sorbonne.

The selected corpus consists of a sample of 3 pages taken from 19 printed books, making a total of 57 pages.
These books, in French and Latin, cover a period from 1602 to 1989, with roughly one book every 20 years.
They are thus representative of the printed documents available in the digital library.

We used [eScriptorium](https://escriptorium.inria.fr/) with the CATMuS Print \[Large] model to transcribe these documents and then corrected the errors manually using the same application.

## Content
The folders contain:
- the ALTO files for each page.
- the image files for each page.
- the model used for the OCR.
- the text files for each book.
