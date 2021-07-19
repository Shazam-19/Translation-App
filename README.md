# Translation-App

## Before You Run the App

1. Make sure that you'av registered for an IBM Cloud account through this link (https://cloud.ibm.com/registration)
2. Install IBM Watson SDK(software development kit)
   Open an Anaconda Prompt (Windows; open as Administrator), Terminal (maxOS/Linux) or shell (Linux), then execute the following command:
   `pip install ibm_watson`
3. Install the needed Modules for Audio Recording and PLayback by executing the following commands as the previous step:

   `pip install pyaudio`
   
   `pip install pydub`
   
   If you get an error, try repacing `pip` with `conda`.
4. Register for the **Speech to Text**, **Text to Speech**, and **Language Translator** services using these links:
   1. Create a Service Instance:
      In each link you will find the default plan ***Lite***, and on the right bottom of the page click **Create**.
      
      *Speech to Text* (https://console.bluemix.net/catalog/services/speech-to-text)
      
      *Text to Speech* (https://console.bluemix.net/catalog/services/text-to-speech)
      
      *Language Translator* (https://console.bluemix.net/catalog/services/language-translator)
      
   2. Get your Service Credentials:
      To see you API key and url, click **Manage** at the top-left of the page. To the right of **Credentials**, click **Show credentials**, 
      then copy the ***API  Key*** and ***url***, and paste it into the the associated variable in ***keys.py*** file; each API Key and url of each service
      should be associated with it's variable name in the file.

5. You are all set now! just open Open an Anaconda Prompt (Windows; open as Administrator), Terminal (maxOS/Linux) or shell (Linux), then execute the following command:

   `cd <the direcory file>`
   
   `ipython SimpleLanguageTranslator.py`
   
### Thanks for Using the Translation-App!
