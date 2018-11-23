# PDF2TXT

It's a python script that  convert PDF to txt using PDFMiner. 

There are two main functions that you can choose to use.

```python
onePdfToTxt(filepath, outpath)
```

```Python
manyPdfToTxt(fileDir)
```

The first function will convert one PDF file to TXT file.

And the second function will convert all PDF files in the folder to TXT files 

**Example**

onePdfToTxt('myPDF.pdf', 'myTXT.txt')  

manyPdfToTxt('myPDFFolderPath')  