# Restaurant Reviews App Stage 1

## Overview

For the Restaurant Reviews projects, you will incrementally convert a static webpage to a mobile-ready web application. In Stage One, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also begin converting this to a Progressive Web Application by caching some assets for offline use.

## Getting Started

### Requirements

This project will be evaluated by a Udacity code reviewer according to the Restaurant Reviews [project rubric](https://review.udacity.com/#!/rubrics/1090/view).

- The provided site fully responsive.
- The site accessible.
- The static site cache for offline use.

### Screenshot

![desktop](https://raw.githubusercontent.com/musaab-abdalla/musaab-abdalla.github.io/master/frontend-nanodegree-restaurant-stage-1/screenshot/Screenshot_desktop.png "Desktop")![tablet](https://raw.githubusercontent.com/musaab-abdalla/musaab-abdalla.github.io/master/frontend-nanodegree-restaurant-stage-1/screenshot/Screenshot_tablet.png "Tablet")![mobile](https://raw.githubusercontent.com/musaab-abdalla/musaab-abdalla.github.io/master/frontend-nanodegree-restaurant-stage-1/screenshot/Screenshot_mobile.png "Mobile")

### Live

[Live can be seen on](https://musaab-abdalla.github.io/frontend-nanodegree-restaurant-stage-1/)

## Instructions

### How to setup the app locally'?'

#### Locally

**1.** Clone this repo:

```git
git clone https://github.com/musaab-abdalla/frontend-nanodegree-restaurant-reviews-app.git
```

**2.** Get a MapBox API key

Head over to your account and create a token. Replace the text `your MAPBOX API KEY HERE` inside of `main.js` `restaurant_info.js` with your key

**3.** To run this project you'll need to use a local server. If you have Python on your machine, you can just do as follow:

1. cd to the project's parent directory
2. change port number in `js/dbhelper.js`.
3. run the commands below:

Python 2

```python
python -m SimpleHTTPServer 8000
```

Python 3

```python
python3 -m http.server 8000
```

#### `This PROJECT using browser-sync as local client server` port number `3000`

**4.** With your server running, visit the site: `http://localhost:8000`

### Style Guides

Make sure your code adheres to our HTML, CSS, JavaScript, and Git style guidelines

- HTML Style Guide
- CSS Style Guide
- JavaScript Style Guide
- Git Style Guide