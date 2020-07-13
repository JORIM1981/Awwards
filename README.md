

# Awwards

#### 10/07/2020
#### By **Jorim Midumbi Okong'o Opondo**

## Description
The application allows a user to post a project he/she has created and get it reviewed by his/her peers. A project can be rated based on design, usability and content. These criterii can be reviewed on a scale of 1-10 and the average score is taken.

You can view the site at:[Heroku](https://awwards-jorim.herokuapp.com/)


## User Stories
As a user, I would like to:
* View posted projects and their details
* Post a project to be rated/reviewed
* Rate/ review other users' projects
* Search for projects
* View projects overall score
* View my profile page
  

  
## Setup and Installation  
To get the project ....... 
  
##### Cloning the repository:  
 ```bash 
 https://github.com/JORIM1981/Awwards.git 
```
##### Navigate into the folder and install requirements  
 ```bash 
cd Awwards pip install -r requirements.txt 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv venv - source venv/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations pictures 
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Running the application  
 ```bash 
 python manage.py server 
```
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`. 

### Api Endpoints
 * https://awwards-jorim.herokuapp.com/api/users/
 * https://awwards-jorim.herokuapp.com/api/profile/
 * https://awwards-jorim.herokuapp.com/api/posts/

  




## Technology used

* [Python3.8](https://www.python.org/)
* [Django3.0.7](https://docs.djangoproject.com/en/2.2/)
* [Heroku](https://heroku.com)


## Known Bugs
* There are no known bugs currently but pull requests are allowed incase you spot a bug

## Contact Information 

If you have any question or contributions, please email me at [okongo.midumbi.opondo@gmail.com]

## License:

- _MIT License:_[LICENSE MIT](./LICENSE)

- Copyright (c) 2020 **Jorim Midumbi Okongo Opondo**


