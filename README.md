#File-Reader-through-Voice
#Statement:
	A code which accepts file with any extension(.txt, .docx, .pdf) as input and reads the respective file through voice. 
#Installation and Packages:
•	Windows Environment
•	Python 2.7.10
•	Pyttsx
•	Voice
•	winsound
•	Python_docx
•	Microsoft C++ compiler
•	Microsoft visual studio 2008/2010
•	pyPdf
#The PYTTSX package and the VOICE package converts any text into a voice which is audible. By using these packages we can also adjust the rate and the volume of voice. 
#WINSOUND is used as a indication for the completion of reading the file. By the output of each process it plays a audio.
#In order to read a Document, it must be converted into a text. The PYTHON_DOCX package helps to implement this task. It converts the given document into a text and the rest is done by the PYTTSX package. The Package expects a softwares like Microsoft C++ compiler for python and Microsoft visual studio 2008/2010 to work. In my case it also expected a LXML file to install.
#The PYPDF package imports PDFFILEREADER to do the same thing as the document package. It converts  a given .pdf file into a text and gives the output to the PYTTSX.
