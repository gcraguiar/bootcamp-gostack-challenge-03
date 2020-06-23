<h1 align="center">
  <img alt="Gympoint" title="Gympoint" src=".github/logo.png" width="200px" />
</h1>

<h3 align="center">
  Challenge 3: Gympoint, continuing the application
</h3>

<blockquote align="center">“My ambition has always been to make dreams come true.” - Bill Gates</blockquote>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/gcraguiar/bootcamp-gostack-challenge-03?color=%2304D361">

  <a href="https://gostack.dev">
    <img alt="Made by gcraguiar" src="https://img.shields.io/badge/made%20by-gcraguiar-%2304D361">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">

  <a href="https://github.com/gcraguiar/bootcamp-gostack-challenge-03/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/gcraguiar/bootcamp-gostack-challenge-03?style=social">
  </a>
</p>

<p align="center">
  <a href="#rocket-about-the-project">About the Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#hammer-and-wrench-resources-and-libraries">Resources and Libraries</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-developed-features">Developed Features</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#scroll-installation">Installation</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#book-documentation">Documentation</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

## :rocket: About the Project

The goal of this challenge is to develop the second part of a gym management system, the Gympoint.
In the first step of this project was developed the API, with it can include, search and update information such as name, email,
age, weight and height of students enrolled in the academy. In addition to performing session control and validating user access in the application.

The second stage of this project aims to implement new functionality in the application, such as enrollment management, plan management, student access control through a checkin feature and a student support channel.

[Click here][challenge02] to follow the development of the first stage of the challenge.

## :hammer_and_wrench: Resources and Libraries

This project was developed with the following technologies:

**Libraries:**

- [Express][express]
- [Node.js][nodejs]
- [Sequelize][sequelize]
- [node-postgres][pg] and [pg-hstore][pg-hstore]
- [Nodemailer][nodemailer]
- [Bee Queue][bee]
- [Sentry][sentry]

**Tools:**

- [JSON Web Tokens][jwt]
- [dotenv][dotenv]
- [bcryptjs][bcryptjs]
- [date-fns][date-fns]
- [express-handlebars][exphbs]
- [VS Code][vc] with [EditorConfig][vceditconfig] and [ESLint][vceslint]

**Services:**

- [Docker][docker]
- [Postbird][postbird]
- [MongoDB Compass Community][mongodb]


## :computer: Developed Features

* Plan Management through CRUD operations
* Access control through check-in feature for students enrolled at the gym.
* Check-in consultation by enrolled student.
* Enrollment Management with CRUD Operations
* Emailing Queues to Enrolled Students.
* Resource to assist enrolled students through requests for help.
* Only administrator-level instructors can answer as questions asked by students.
* Email queues to notify students when their answers are answered.

---

### :scroll: Installation

To clone and run this application, you'll need [Git](https://git-scm.com), [Docker](https://www.docker.com), [Node.js v10.16][nodejs] or higher + [Yarn v1.19][yarn] or higher installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/gcraguiar/bootcamp-gostack-challenge-03.git gympoint-api

# Go into the repository
$ cd bootcamp-gostack-challenge-03

# Install dependencies
$ yarn install

# Run Postgres
$ docker run --name database -e POSTGRES_PASSWORD=docker -d -p 5432:5432 -d postgres:11

# Run MongoDB
$ docker run --name mongobarber -p 27017:27017 -d -t mongo

# Run Redis
$ docker run --name redis -p 6379:6379 -d -t redis:alpine

# Create a new database named "gympoint" in postbird and run the following commands:
# Run Migrations and Seeds
$ yarn sequelize db:migrate
$ yarn sequelize db:seed:all

# Run Nodemailer
$ yarn queue

# Run the Server
$ yarn dev
```

---

### :book: Documentation

> [Click here](http://www.google.com.br) for download documentation using [Insomnia][insomnia] for Unix.

> [Click here](http://www.google.com.br) for download documentation using [Postman][postman] for Windows.


&nbsp;

* Do you want to view the running project? [Click here][youtube-challenge-03]

&nbsp;

---


## 📅 Conclusion

Challenge completed in 2019/11/11 - [Click here][rocketseat-challenge-03] to access the challenge.

## :memo: License

This project is under the MIT license. See the [LICENSE](./LICENSE) for more information.

---

Made with ♥ by Gabriel Aguiar for Rocketseat :tm: [Come meet me!][linkedin]

[challenge02]: https://github.com/gcraguiar/bootcamp-gostack-challenge-02
[challenge03]: https://github.com/gcraguiar/bootcamp-gostack-challenge-03

[linkedin]: https://www.linkedin.com/in/gabriel-aguiar-740002197/

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
[express]: https://expressjs.com
[sequelize]: https://sequelize.org
[pg]:https://github.com/brianc/node-postgres
[pg-hstore]: https://github.com/scarney81/pg-hstore
[jwt]: https://jwt.io/
[nodemailer]: https://nodemailer.com/about/
[bee]: https://bee-queue.com/
[dotenv]: https://github.com/motdotla/dotenv#readme
[bcryptjs]: https://github.com/dcodeIO/bcrypt.js/
[date-fns]: https://date-fns.org/
[exphbs]: https://github.com/ericf/express-handlebars
[insomnia]: https://insomnia.rest/download/
[postman]: https://www.getpostman.com/downloads/
[sentry]: https://github.com/getsentry/sentry
[docker]: https://github.com/docker
[postbird]: https://electronjs.org/apps/postbird
[mongodb]: https://www.mongodb.com/download-center/compass

[youtube-challenge-03]: https://youtu.be/bLGGW-66z6Y
[rocketseat-challenge-03]: https://github.com/Rocketseat/bootcamp-gostack-desafio-03/blob/master/README.md#desafio-03-continuando-aplica%C3%A7%C3%A3o

