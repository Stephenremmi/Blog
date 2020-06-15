# Blog
To be part of the remmisma-blog community Sign Up an account and plug in the exciting community;write a blog,share,like and comment.

![Portfolio landing page Window](https://user-images.githubusercontent.com/61972580/84638670-f9428080-aeff-11ea-9d13-3ae2dc8ae4bf.png)
![SignUp Window](https://user-images.githubusercontent.com/61972580/84639431-09a72b00-af01-11ea-84a6-134898bdaa80.png)
![Login Window](https://user-images.githubusercontent.com/61972580/84639621-4bd06c80-af01-11ea-89a4-6ae8d7114694.png)
![Account settings Window](https://user-images.githubusercontent.com/61972580/84640504-72db6e00-af02-11ea-8e02-09a9d5781481.png)
![Settings Window](https://user-images.githubusercontent.com/61972580/84636060-ca76db00-aefc-11ea-8b3a-c05bec01d3ff.png)
![Login Window](https://user-images.githubusercontent.com/61972580/84638950-576f6380-af00-11ea-9ca6-de915e12ccb1.png)
![Landing page Window](https://user-images.githubusercontent.com/61972580/84636800-ab2c7d80-aefd-11ea-9573-7141ea2e5593.png)
![Comments view](https://user-images.githubusercontent.com/61972580/84637296-2db53d00-aefe-11ea-926d-e7a6f3a6517e.png)


## Author
[Stephen Remmi](https://github.com/Stephenremmi) ,6/13/2020

### Description
A blog where users can view quotes from great techies and iconic figures,can share their passions and can focus on presentng solutions to problems.

## Behavior Driven Development

| Input                    | Behaviour                       | Output                                       |
| -------------------------| ------------------------------  | -------------------------------------------- |
| Subscribe to mail list              | Input the email               | Redirect you to the index page               |
| Writer login                    | Take you to home page           | Redirect you to the Homepage                 |
| Create a blog post by filling blog form          | Write your blog and post it to blogs    | Your blog is displayed  in index page                     | 
| User comment on the Blog post plus a nickname | Write your feedback and post it | Your feedback is displayed under the blog post   |
| Writer delete a blog post       | Deleting the blog post from the database    | The blog post will be deleted and not appear on the page                  |
| Writer update a blog post       | Updating the blog post in database    | The blog post will be updated                |
| Writer delete a comment         | Deleting the blog post in database    | The comment will no longer appear under the post           

### User Story
Here are the features in summary:
* User can view the blog posts on the site
* User sees random quotes on the site
* User can view the most recent posts
* User can subscribe to blog mailing list and receives an email alert when a new post is made.
* User can comment on blog posts
* User can like a blog post.

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

### Versioning
The second version of remmisma-blog is aimed at removing the above described bug.
A request from the user's community is adding followers and following features to add more excitement.

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
You can view the live application by following this [link](https://remmisma-blog.herokuapp.com/)

### [License](https://github.com/Stephenremmi/Blog/blob/master/LICENSE)
MIT license Copyright(c) 2020 **Stephen Remmi**
