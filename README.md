# instagram_clone

### Instagram clone implemented with client-side dynamic pages and REST API
### images are from a local host run


## Login Page
![image](https://github.com/user-attachments/assets/f8d8658c-5530-44cb-a34e-230ba91e9ba9)

UI implemented in HTML/CSS

Backend utilized Flask sessions and route redirects in Python

Database of users and user-information was implemented with SQLite using this [documentation](https://flask.palletsprojects.com/en/1.0.x/appcontext/#storing-data)


## Sign Up Page
![image](https://github.com/user-attachments/assets/6145731f-5dd6-453f-8fcc-7cd307e3b72f)

Updating the Flask session user as well as inserting into the SQLite database


## Home Page
https://github.com/user-attachments/assets/d054de76-7888-4eee-b864-fddde2ae3156

- Liking and unliking posts functionality
- Adding and removing comments
- Timestamp of when post was posted
- Double-clicking on post image likes the post
- Clicking on poster's name links to poster's profile
- Clicking on commenter's name links to commenter's profile

Fetched information from the SQLite database corresponding to the user logged into the current session

## User Page
https://github.com/user-attachments/assets/b66ca646-ff59-45e1-9730-31502212985d

Flask sessions and database manipulation to add (INSERT) and remove (DELETE) posts


## Explore Page
![image](https://github.com/user-attachments/assets/939055ce-62d3-45c5-a4b1-621576bbbfa4)

Explore page listing users that the logged-in user doesn't currently follow

Utilized Flask sessions and the SQLite database









