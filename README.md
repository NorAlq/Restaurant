# Restaurant Reviews App Stage 1

----
## Project Overview: Stage 1

For the **Restaurant Reviews** project, I converted a static webpage to a mobile-ready web application. I took a static design that lacks accessibility and I converted the design to be responsive on different sized displays and accessible for screen reader use. I also added a service worker to begin the process of creating a seamless offline experience for the users.

You can do the following in this project :-

* Filter some resturants according to some features.
* See the review of each restaurant.
* See the address of the resturant.
* See the work schedule in the restaurant weekly.
* If the user is blind, there is no problem because he/she can access the website via google chrome extention chromeVox.

In this Project I used:-

* Service-worker to make the website work offline.
* Aria roles to get the website accessabile to blind people.
* Google maps application to mark all needed restaurants on it.

# Install

you need to install :-

* python2 or python3 on your computer.
* webbrowser on your pc.


# Run The Application

1- In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on their computer. 

2- In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

3- With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.


