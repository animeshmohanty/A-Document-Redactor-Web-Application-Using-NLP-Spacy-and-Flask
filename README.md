#For the summarization part:
The simulation environment is in such a way that the document or text summarization will done using a web application created using Python Flask and there will be 2 summarization methods used. There is also an API created for comparing the performance of two summarizers.The user has to open a proper CLI then run the localhost server for the application using the command "python app.py". This will start the localhost server and then the localhost server's url when opened in a browser of user's choice will open the index.html file which routes the home page API as default.Then the user should be able to access the web application and its features without any errors.
If your CLI prompts you about punkt module not being found, go to a new CLI and type python and then follow:
>>import NLTK
>>NLTK.download('punkt')

#For Document redactor part:
Follow the same steps as summarization but do not forget to access the proper directory while doing so.
