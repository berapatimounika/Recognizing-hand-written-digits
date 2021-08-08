# Recognizing-hand-written-digits
Recognizing hand written digits using python
Recognizing handwritten text is a problem that can be traced back to the first automatic machines that needed to recognize individual characters in handwritten documents. Think about, for example, the ZIP codes on letters at the post office and the automation needed to recognize these five digits. Perfect recognition of these codes is necessary inorder to sort mail automatically and efficiently. included among the other applications that may come to mind is OCR (Optical Character Recognition) software. OCR software must read handwritten text, or pages of printed books, for general electronic documents in which each character is well defined.
But the problem of handwriting recognition goes farther back in time, more
precisely to the early 20th Century (1920s), when Emanuel Goldberg (1881–1970) began his studies regarding this issue and suggested that a statistical approach would be an optimal choice.
To address this issue in Python, the scikit-learn library provides a good example to better understand this technique, the issues involved, and the possibility of making predictions.

Recognizing Handwritten Digits with scikit-learn:
The scikit-learn library (http://scikit-learn.org/) enables you to approach this typeof data analysis in a way that is slightly different from what you’ve used in Project 1. Thedata to be analyzed is closely related to numerical values or strings, but can also involveimages and sounds.
The problem you have to face in this Internship project involves predicting a numericvalue, and then reading and interpreting an image that uses a handwritten font.
So even in this case you will have an estimator with the task of learning througha fit() function, and once it has reached a degree of predictive capability (a modelsufficiently valid), it will produce a prediction with the predict() function. Then we willdiscuss the training set and validation set, created this time from a series of images.

implementation:

Thus, you have to import the svm module of the scikit-learn library. You can createan estimator of SVC type and then choose an initial setting, assigning the values C and gamma generic values. These values can then be adjusted in a different way during the course of the analysis.
