This workflow shows how to use XPS Activities

Steps:
1. Read an xps file using ReadXPSFile activity. The result of the reading is stored in variable 'ExactString'
2. Read xps file using ReadXPSWithOCR activity. The result of the reading is stored in the variable 'ExtractWithOCRString'. Note that only the images from the xps file are analyzed with this activity (the texts are ignored).
Any OCR engine activity can be used instead of Microsoft activity chosen by us