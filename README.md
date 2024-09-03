# NLP_OCR_document_classification
Classifying documents by converting PDFs into images with PyMuPDF, using OCR with keras_ocr to extract the text, and using spacy NLP to classify the documents based on the semantics of the extracted text.

So far it is just proof of concept (I have only spent a couple of hours on it), so it just classifies two documents (correctly) as a resume and an invoice, respectively.

Next: I will find a larger data set (a few thousand) with labels, run it all through the script, and present the data with ROC curves, and confusion matrices.

Right now it only classifies between three predetermined classes. A better model will either have more classes or no need for predetermination.
