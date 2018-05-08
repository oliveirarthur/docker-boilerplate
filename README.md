# Docker for PHP applications

This is a simple docker boilerplate for the *development* environment of PHP applications.

## Instalation

You can start using this boilerplate after the following steps:

```sh
# Clone this repository
git clone -b php https://github.com/oliveirarthur/docker-boilerplate.git

# Config the 'public' folder according to your project inside the 'vhost.conf' file
vim vhost.conf
```

All the application code must live inside the `src` folder.

Once the boilerplate is installed, you'll be able to run the application with:

```sh
docker-compose -f docker/docker-compose.yml up --build
```

Now that your application is up and running, you can open <http://localhost:8080/> in your browser and start working!
