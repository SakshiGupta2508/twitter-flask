MIICWWIBAAKBgQCimr4pKLnkY565Xvq0QSGFf6XZZEAZ6+gbN8qM2X8165pi/PGG jMSdZruumTwfZrIIdQyUGoRBPGpk2/4+jt+PJEPHmrgWe33FZp+oA19epC90P70K kkBrYXL1pyiT6c8TID1jc+do6sE+JX6jSLa7zpj76r+2jSHWs6R113KzCQIBJQKB gOCZOKYLOjNNg1ffyIxJpWTmEPbt]3roFoGdNMaFPHFARvnTOkxBAbMRbWSOZ3A5
YSTZPkor062J0V25WnrhOwrSASOWDFPTSOIEwozq3zmPgbHyqGmwsg+BWKDS1dQL SoUuCk/as4YCXSz25w0Fnte9GAUuvKE1WL21I1LI851500JBAM7G18th362tS/Yb n3eOLKZqfrVyRTD9mIUfYUm3qL3060AhwEzy2F90YLt9Gr61aqpmeZIEz/DZZKu0 xjrTj48C00D]UAC6/IDYLW0X4G9WSZpIxt21Dj3JmNUYO9pRVj5SQCzHeh05oW15 7+cICbXMJJCOdixeHxvuA435mBvYZMfnAkBkmBX0PRo40N1Y19EJusmdETa5ItWN dH02YksBRJdHIRdYR8VV3ey4v1iSj+N/Xyz485UWmo6shW8+xqWgE+T5AkEAs4yL B6SNSy9vIyIeHOOXcVdrvLmsuri+DrHsOrS0H9hfSiDFfAyAqo0aKcN40VELT9C/ yZFeGXiKvA00gxeB2WJACTbZBXZXgURYgsbWWPD3+YWXBEA3bELIEx+/YVV44Rbb
½86G+/TEKTofUFQwfe27Fcbz+Coh/1zH80BrD+JKmg==

<div id="top"></div>

  <h3 align="center">RESTful Flask API</h3>

  <p align="center">
    RESTful API Endpoints developed using Twitter APIs!
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#steps">Steps</a>
      <ul>
        <li><a href="#authentication">Authentication</a></li>
        <li><a href="#run-application">Run Application</a></li>
        <li><a href="#run-tests">Run Tests</a></li>
        <li><a href="#documentation">Documentation</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#project-description">Description</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project


The main job is to develop two RESTful API endpoints to provide data from Twitter. 
The data can be fetched from Twitter using Twitter API.

This project has been developed using Twitter API.


<p align="right">(<a href="#top">back to top</a>)</p>



### Built With


* [Python](https://www.python.org/)
* [Flask](https://flask.palletsprojects.com/en/2.0.x/)
* [Twitter Developer Account](https://developer.twitter.com/en/apply-for-access)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

* Twitter developer account 


### Installation

* Git clone project
* Install requirements (pip install -r requirements.txt)

## Steps


### Authentication

* In this project, bearer token authentication has been used.
* To set the bearer token in your environment variable run the following commands:
  ```sh
   export 'BEARER_TOKEN'='<your_bearer_token>'
   ```
  
### Run Application

```sh
   python app.py
   ```

### Run Tests

```sh
   python test.py
   ```
   
## Documentation

### Swagger UI

Detailed documentation of the APIs can be accessed through 

* [Swagger](http://127.0.0.1:5000/swagger/)
* Note: This can be accessed when application is running.


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [Sakshi](https://www.linkedin.com/in/sakshi-gupta-0aa978140/)

Project Link: [Twitter Flask](https://github.com/SakshiGupta2508/twitter-flask)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Project Description -->
## Project Description

1. Get tweets by a hashtag : Get the list of tweets with the given hashtag.</br> 
Optional parameters:</br>
limit: integer, specifies the number of tweets to retrieve, the default should be 30</br></br>
Example request:</br>
curl -H "Accept: application/json" -X GET http://127.0.0.1:5000/hashtags/{hashtag}?limit=20 


2. Get user tweets : Get the list of tweets that the user has on his feed in JSON format.</br>
Optional parameters:</br> 
limit: integer, specifies the number of tweets to retrieve, the default should be 30 </br></br>
Example request:</br>
curl -H "Accept: application/json" -X GET http://127.0.0.1:5000/users/{user}?limit=20 
3. 
