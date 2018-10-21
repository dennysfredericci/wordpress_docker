# WordPresss Docker

This is a simple WordPress installation to run Wordpress and MySQL with just one command line, really useful to run some tests locally and not recommended to the production environment.

## Built With

* [Docker](http://docker.com/) - Container Management - Build, Manage and Secure Your Apps Anywhere. Your Way.
* [WordPress](https://wordpress.org) - WordPress is open source software you can use to create a beautiful website, blog, or app.
* [MySQL](https://www.mysql.com) - Relational DataBase

## Running

1 - Execute the command on terminal: docker-compose up -d
2 - Open the url: http://localhost:8000/

To stop and remove just execute:

docker kill $(docker ps -q)
docker rm $(docker ps -a -q)

## Contributing

In general, we follow the "fork-and-pull" Git workflow.

 1. **Fork** the repo on GitHub
 2. **Clone** the project to your own machine
 3. **Commit** changes to your own branch
 4. **Push** your work back up to your fork
 5. Submit a **Pull request** so that we can review your changes


## Authors

* **Dennys Fredericci**

See also the list of [contributors](https://github.com/dennysfredericci/simple-rest-client/contributors) who participated in this project.
