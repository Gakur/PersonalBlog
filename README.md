#BLOGQUOTE APP

#### Author: 
* Peter Gakure


* Link to live site: [My blogs](https://pepeblogs.herokuapp.com/)

## Description
This is a personal blogging website where you can create and share your opinions and other users can read and comment on them. Additionally it has a feature that displays random quotes to inspire your users.

## User stories
The user would like to.... :
*  View the blog posts on the site
*  Comment on blog posts
*  View the most recent posts
*  An email alert when a new post is made by joining a subscription.
* See random quotes on the site

The writer would like to... :

* see random quotes on the site
* sign in to the blog.
* create a blog from the application.
* delete comments that I find insulting or degrading.
* update or delete blogs I have created.




## Behaviour Driven Development
| Behavior            | Input                         | Output                        | 
| ------------------- | ----------------------------- | ----------------------------- |
| View blog | Click on comment | Taken to the clicked post | Click on `Comment` | Taken to where you can comment | Signs In/ Signs Up |
| Click on `Click Add a blog` | If logged in, display form to add a blog| Redirected to the home page |
| Click on profile | Redirects to the profile page | User adds bio and profile picture |
| Click on Sign Out | Redirects to the home page | Signs user out |


### Prerequisites
* python3.8
* virtual environment
* pip3

### Cloning
* In your terminal:
        
        $ git clone https://github.com/Gakur/PersonalBlog
        $ cd BlogsQuote

## Running the Application
* Install virtual environment using `$ python3.8 -m venv --without-pip virtual`
* Activate virtual environment using `$ source virtual/bin/activate`
* Download pip in our environment using `$ curl https://bootstrap.pypa.io/get-pip.py | python`
* Install all the dependencies from the requirements.txt file by running `pip freeze -r requirements.txt`
* Create a `start.sh` file in the root of the folder and add the following code:

        export MAIL_USERNAME=<your-email-address>
        export MAIL_PASSWORD=<your-email-password>
        export SECRET_KEY=<your-secret-key>

* Edit the configuration instance in `manage.py` from `development` to `production`
* To run the application, in your terminal:

        $ chmod a+x start.sh
        $ ./start.sh
        
## Testing the Application
* To run the tests for the class file:

        $ python3.8 manage.py server
        
## Built With

* [Python3.6](https://docs.python.org/3/)
* Flask
* Boostrap
* HTML
* CSS


## Contact details
 Incase you come across errors, have questions, ideas ,concerns, or want to contribute to the application, feel free to reach me at: petergakure97@gmail.com

## License 

#### [*MIT*](LICENSE)
