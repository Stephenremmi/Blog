# Blog
![Portfolio landing page Window](https://user-images.githubusercontent.com/61972580/84638670-f9428080-aeff-11ea-9d13-3ae2dc8ae4bf.png)
![SignUp Window](https://user-images.githubusercontent.com/61972580/84639431-09a72b00-af01-11ea-84a6-134898bdaa80.png)
![Login Window](https://user-images.githubusercontent.com/61972580/84639621-4bd06c80-af01-11ea-89a4-6ae8d7114694.png)
![Account settings Window](https://user-images.githubusercontent.com/61972580/84640504-72db6e00-af02-11ea-8e02-09a9d5781481.png)
![Settings Window](https://user-images.githubusercontent.com/61972580/84636060-ca76db00-aefc-11ea-8b3a-c05bec01d3ff.png)
![Login Window](https://user-images.githubusercontent.com/61972580/84638950-576f6380-af00-11ea-9ca6-de915e12ccb1.png)
![Landing page Window](https://user-images.githubusercontent.com/61972580/84636800-ab2c7d80-aefd-11ea-9573-7141ea2e5593.png)
![Comments view](https://user-images.githubusercontent.com/61972580/84637296-2db53d00-aefe-11ea-926d-e7a6f3a6517e.png)


## Author
[Stephen Remmi](https://github.com/Stephenremmi) ,6/8/2020

### Description
In life you only have 60 seconds to impress someone.1 minuite can make or break you.How do we make sure you use your 1 minute to actually say something useful.

### User Story
Here are the features in summary:
* User can create the account and sign in to the app.
* User receives a welcoming email he/she signs up.
* User can view pitches other people have posted
* User can to view the pitches i have created in his or her profile page.
* User can comment on the different pitches and leave feedback
* User can submit a pitch in any of the provided categories
* User can view the different categories

### Requirements
* This python program requires python 3+ (and pip) installed.A guide on how to install can be found [here](https://www.python.org/)
* Once python is installed install the following external libraries provided in the requirements.txt file using pip
* Example:
           **`pip install flask`**

### Installation and Set-up
To view the app, open the live site link provided below on the README.
Here is a run through of how to set up the application:
* **Step 1** : Clone this repository using **`git clone https://github.com/Stephenremmi/pitch-idea.git`**, or downloading a ZIP file of the code.
* **Step 2** : The repository, if downloaded as a .zip file will need to be extracted to your preferred location and opened
* **Step 3** : Go to the project root directory and install the virtualenv library using pip an afterwards create a virtual environment. Run the following commands respectively:
    * **`pip install virtualenv`**
    * **`virtualenv venv`**
    * **`source venv/bin/activate`**
        * Note that you can exit the virtual environment by running the command **`deactivate`**
* **Step 4** : Download the all dependencies in the requirements.txt using **`pip install <name>`**
* **Step 5** :
    * Create a file in your root directory called start.sh **`export API_KEY="<your-key>"`**
    * On the same file write down the command **`python3 manage.py server`** 
* **Step 6** : On your terminal, run the following command, **`chmod a+x start.sh`**
    * You can now launch the application locally by running the command **`./start.sh`** 
    * Open your preferred browser and view the app by opening the link **http://127.0.0.1:5000/**.
    
### Known Bugs 
* Subscription of users is registered in database but redirection after subscribing to the blog brings an error page.

### Technologies used
* Python 3.6
* Flask
* Postgre SQL
* SQLAlchemy
* HTML
* CSS
* Bootstrap 4.3.1
* Font Awesome 5.8.2
* JQuery 3.4.1
* Google Font API

### Support and Contact Details
You can provide feedback or raise any issues/bugs through the following means:
* stephenremmi@gmail.com

### Live Site Link
You can view the live application by following this [link]

### [License]()
MIT license Copyright(c) 2020 **Stephen Remmi**
