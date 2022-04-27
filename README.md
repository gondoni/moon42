<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<!-- div align="center">
  <!-- a href="https://github.com/github_username/repo_name">
    <!-- img src="images/logo.png" alt="Logo" width="80" height="80">
  <!-- /a>

<h3 align="center">Timetracker backend code</h3>

  <p align="center">
    project_description
    <br />
    <a href="https://github.com/gondoni/timetracker"><strong>Explore the code »</strong></a>
    <br />
    <br />
    <a href="https://github.com/gondoni/timetracker/issues">Report Bug</a>
    ·
    <a href="https://github.com/gondoni/timetracker/issues">Request Feature</a>
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
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Here is my first training exercise to learn using Spring Boot, Docker, MySQL, Postman.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Spring Boot](https://spring.io/projects/spring-boot/)
* [Spring Tools Suite](https://spring.io/tools/)
* [Docker](https://www.docker.com/)
* [MySQL](https://www.mysql.com/)
* [MySQL Workbench](https://www.mysql.com/products/workbench/)
* [Postman](https://www.postman.com/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

You need the followings:
1. IDE to handle Spring Boot source code, for example the [Spring Tools Suite](https://spring.io/tools/).
2. [Docker](https://www.docker.com/) container environment
3. Any browser for login procedure and GET request tests
4. [Postman](https://www.postman.com/) for POST (and any) request tests

### Installation

1. Clone the repo to the Workspace of your IDE
   ```sh
   git clone https://github.com/gondoni/timetracker.git
   ```
2. At first time, once, run the timetracker/mysql/mysql_run.bat file. It makes and starts the MySQL Docker container environment (named timetracker-mysql) and all of its initialization with the timetracker_init.sql file.
   ```sh
   mysql_run.bat
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

## Usage

1. Run the Timetracker Spring Boot App. Tomcat webserver starts on localhost on port 8080
2. Browse this web address:
   ```sh
   http://localhost:8080/
   ```
At first, it redirects you to the login site: [http://localhost:8080/login](http://localhost:8080/login)
You can login with usernames and passwords of the user table stored in the MySQL database. Example usernames: 'nferi', 'kvili', 'totto', with the same password: 'pwd'.

3. After login, visit these websites for the specified GET requests:
* [http://localhost:8080/projects](http://localhost:8080/projects) - it gives JSON objects with projects of your user
* [http://localhost:8080/tasks](http://localhost:8080/tasks) - it gives JSON objects with tasks of your user
* [http://localhost:8080/fulfillments](http://localhost:8080/fulfillments) - it gives JSON objects with fulfillments of your user

4. Testing POST requests you need to use, for example [Postman](https://www.postman.com/)
* To login send a POST request, with body containing username and password as form-data keys and values:

    <img src="images/postman_login.png" alt="Login">
    
* To insert/edit fulfillments send a POST request, with body containing details as JSON raw data:
    <img src="images/postman_fulfillment_insert.png" alt="Fulfillment insert">


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the Moon42 License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

István Gondon - istvan.gondon@moon42.com

Project Link: [https://github.com/gondoni/timetracker](https://github.com/gondoni/timetracker)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
