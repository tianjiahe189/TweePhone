*********************************** CONFIGURATION ***********************************
--------------API Accounts------------------------
In order to use TweePhone application, a user need to register an account for the Twitter API. After successfully registered, a user will be provided with keys and tokens. User need to put those keys and tokens in a JSON file called credential.json in the format below.
 
{
    "CONSUMER_KEY": "XXXXXXXXXXXXXXXXXXXXXXXXXXXXX",
    "CONSUMER_SECRET": " XXXXXXXXXXXXXXXXXXXXXXXXXXXXX ",
    "OAUTH_TOKEN": " XXXXXXXXXXXXXXXXXXXXXXXXXXXXX ",
    "OAUTH_TOKEN_SECRET":" XXXXXXXXXXXXXXXXXXXXXXXXXXXXX "
}

--------------Gender Predictor Configuration--------------
In order to utilize the gender library in TweePhone, a user need to run the following command in terminal(for mac and linux user) or Anaconda Prompt(for windows user) : “pip install gender”. 

--------------Race Predictor Configuration--------------
In order to utilize the ethnicity library in TweePhone, a user need to run the following command in terminal(for mac and linux user) or Anaconda Prompt(for windows user) : “pip install ethnicity ”. 

--------------Bokeh Server Requirement--------------
In order for showing graphic contents correctly, the Bokeh package version inside Anaconda need to be at least 0.13.0


--------------Authentication File--------------

Once accounts are setup with the two API services, the keys and tokens will need to be stored in JSON format in a file called credential.json.  This file should be placed in the same directory as the main Jupyter Notebook. A sample file containing dummy keys currently exists in the TweetPhone zip file.

The file must contain the following key value pairs all at the initial level in the JSON file.


    "CONSUMER_KEY": "XXXXXXXXXXXXXXXXXXXXXXXXXXXXX",
    "CONSUMER_SECRET": "XXXXXXXXXXXXXXXXXXXXXXXXXXXXX",
    "OAUTH_TOKEN": "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX",
    "OAUTH_TOKEN_SECRET":"XXXXXXXXXXXXXXXXXXXXXXXXXXXXX"


--------------Data Subdirectory--------------
The feature_keywords.json is used to support extracting feature data from tweets. The cities_and_states .json is used to remove fictional location and extract only US cities. Two supporting data are included in the TweePhone project zip file in the same directory as TweePhone Jupyter Notebook.



*********************************** Running the Code ***********************************
After all requirements mentioned are met, TweePhone is ready to run. In the TweePhone Jupyter Notebook, in order to start TweePhone properly, all codes must be run in order from top to bottom. The last line of codes will launch the Bokeh server that users can use to interact with TweePhone. Reminder: The port number in the last line of codes must match the port number for Jupyter Notebook.


