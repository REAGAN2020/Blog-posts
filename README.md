# Blog-posts

This is a python web application that allows users to create and share opinions and other users can read. Users can also generate random quotes .Users can also viiew most recent posts and can also create blog using our application.

## Author 

*   Owiti Reagan

## Project Description

    This is web application that allows users to posts blogs comment on them also view them on their profile.
## Project setup  installation

1.  From the repository, click + in the global sidebar and select Clone this repository under Get to work.
2.  Copy the clone command.
3.  From terminal you use
    '$ git clone <https://github.com/REAGAN2020/Blog-posts/>'


## BDD  

| BEHAVIOUR | INPUT | OUTPUT|
|:------------------|:--------|:-----------|
| User sign-up | User puts his/her email, username and password |  User gets an Email and new account is created |
| User logins | User puts his/her account email and password | User is authenticated and home page is displayed|
| User clicks on create blog button | User adds his/her blog | Blog is added to list of blogs and is displayed on users profile|
| User clicks on profile | ....... |  List of blogs created by the user is displayed|


## Technologies Used

* Python
* Flask
* Bootstrap
* CSS
* HTML
* Git  



3. Exporting Configurations

```bash
export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}
```

4. Running the application

```bash
python3.8 manage.py server

```

5. Testing the application

```bash
python3.8 manage.py test
```

Open the application on your browser `127.0.0.1:5000`.

## Technology used

- [Python3.8](https://www.python.org/)
- [Flask](http://flask.pocoo.org/)
- [Heroku](https://heroku.com)

## Known Bugs

<!-- - The delete function is not working as per now but working on how to fix it. -->
- The comments section is currently unvailable but working on it .
- Getting to update your profile picture has a problem too.

## Contact Information

If you have any question or contributions, please email me at [owitireagan1gmail.com]


## License

[MIT](LICENSE.md) © @ **Owiti Reagan**