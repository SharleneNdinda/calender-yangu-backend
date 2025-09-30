 <div id="top" align="center">

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
</div>

<br />
<h3 align="center"> 🍣 Calender Yangu 🍣 </h3>

  <p align="center">

    Your calender better than ever!
    
  </p>
    <br />
    <a href="#"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/SharleneNdinda/calender-yangu-backend/issues">Report Bug</a>
    ·
    <a href="https://github.com/SharleneNdinda/calender-yangu-backend/issues">Request Feature</a>
  </p>
</div>

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
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

##  About The Project

Calender Yangu is a robust, scalable service. It is meant to deliver the following:

    ✅ Be able to view and add events to your personal calender.

### 🚀 Getting Started

1. Clone this repository and setup virtual environment. Install all project requirements before proceeding.
```sh
  $ pip install -r requirements/base.txt
```

2. Setup your local `Postgres` database, update database configs and run migrations.
```sh
  $ python manage.py migrate
```

3. Run development server.
```sh
  $ python manage.py runserver
```

### 🔒 Authentication

1. This API uses `Basic Token authentication` to authenticate users. After successful local setup, run the server and paste the following call to create and account.
```sh
  $ api call here ...
```

[contributors-shield]: https://img.shields.io/github/contributors/SharleneNdinda/calender-yangu-backend?style=for-the-badge
[contributors-url]: https://github.com/SharleneNdinda/calender-yangu-backend/contributors
[forks-shield]: https://img.shields.io/github/forks/SharleneNdinda/calender-yangu-backend?style=for-the-badge
[forks-url]: https://github.com/SharleneNdinda/calender-yangu-backend/forks
[stars-shield]: https://img.shields.io/github/stars/SharleneNdinda/calender-yangu-backend?style=for-the-badge
[stars-url]: https://github.com/SharleneNdinda/calender-yangu-backend/stargazers
[issues-shield]: https://img.shields.io/github/issues/SharleneNdinda/calender-yangu-backend?style=for-the-badge
[issues-url]: https://github.com/SharleneNdinda/calender-yangu-backend/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: in/sharlene-mutuku-86571518b
[product-screenshot]: images/architecture.png
[x-ray-trace]: images/trace.png