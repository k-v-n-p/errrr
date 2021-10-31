# MedicBot
An AI chatbot based on RASA framework to provide healthcare assistance. 

## Purpose
> "The ultimate aim of the medicbot chatbot is to significantly simulate exactly the way a human doctor would monitor a person’s health status and advise any medications or practices."

## Setup

* Download nodejs 
    <ul><li> On windows from [here](https://nodejs.org/en/download/) </li></ul>
    <li> On linux using the command <code> sudo apt install nodejs  </code> </li>

* Install the following dependencies with the command. <code> npm install [module_name] </code> 
<ul><ul>
    <li>  express  </li>
    <li>  mongoose  </li>
    <li>  jsonwebtoken  </li>
    <li>  bcrypt  </li>
    <li>  cookie-parser  </li>
    <li> dotenv  </li>
</ul></ul>

* (optional) Add the database URI and credentials in the .env file

## Usage
* If the optional step is omitted in the setup section 
remove <em>line 226 : "requireAuth," </em> from line 225 of src/app.js
* Download and extract the zip file contents.
* Run the application: execute node src/app.js
* Train and run our RASA model with the dataset
    <code> rasa train  </code>
    <code> rasa run -m models --enable-api --cors "*" </code>
* Open the localhost http://127.0.0.1:5000/ on any browser.

## Features
* The users could book appointments from registered health professionals.
* Recommend medicine through the chatbot.
* Medical advice on how to live a healthy lifestyle.
* Cool.

<!--- * Holds no record of the medical history for privacy purposes. -->

## Contact
[justprateek](justwriteprateek@gmail.com)
[k-v-n-p](kvnp.zyx@gmail.com)
