PROJECT PURPOSE:

  Despite the abundances of technological writing tools,many people still choose to take their notes traditionally with pon and paper. However, there are drawbacks to handwriting text. It's difficult to store and access physical documents in an efficient manner, search through them efficiently and to share them with
others. The aim of this project is to further explore the task of classifying handwritten text and to convert handwritten text into the digital format. Handwritten text is a very general term and we wanted to narrow down the scope of the project byspecifying the meaning of handwritten text for our purposes. In this project, we took on the challenge of classifying the image of any handwritten word, which might be of the form of cursive or black writing and convert it into editable text and also to other languages.


INSPIRATION:

  Our main inspiration is Doctor's Handwriting and the judgement of the judges which is very difficult to understand. The OCR will help us to identify those handwritten words and convert it into normal text.Applications of offline handwriting recognition are numerous reading postal addresses, bank check amounts Doctor's prescription and forms. Furthermore, OCR plays an important role for digital libraries, allowing the entry of image textual information into computers by digitization, image restoration, and recognition methods.

  
  
TECH STACK:
 
1. PRE-PROCESSING 
   Extract the text from the image and process it

2. SEGMENTATION 
   The words are segmented into individual letters using OCR

3. FEATURE EXTRACTION
   The major goal of feature extraction is to extract a set of features, which maximizes the recognition rate elements.

4. CLASSIFICATION
   This is the decision making stage of recognition system. The classifier contains two hidden layers, using a log sigmoid activation function to train the algorithm
 
 
HOW DID WE BUILT IT?

  The main building block of this project is OCR. There are various types of OCR such as easyour, kerasor, pytesseract and so on. We searched for the OCR that would predict results with more accuracy. Thus Keras ocr and Pytesseract gave much accurate results.
  
  
PROBLEMS WE RAN INTO:

  The problems we faced were in the code itself such as importing the libraries, using the proper OCR and so on.Convering it into editable text was quite challenging.
  
FUTURE CHANGES AND IMPROVEMENTS:

  Though the OCR gives some pretty accurate results it is not pretty accurate. In the future this project could be developed with a much developed OCR or we could work on developing the OCR itself.

