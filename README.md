# Docker PHP

This repo will helps anyone to start their PHP development or even beginner to start to learn and experimented PHP without installing complicated app/software such as WampServer, Nginx, Apache, etc.

No need to worry if you have ZERO knowledge about Docker. You still can use this.

----
&nbsp;

##Requirement

- Docker

Yes, it only require Docker to run PHP web and CLI.

----
&nbsp;

##How to Use

###Basic Usage

1. `git clone https://github.com/syamsoul/docker-php.git <YOUR_APP_FOLDER_NAME>`
1. `cd <YOUR_APP_FOLDER_NAME>`
1. `sh soul up`

That's it, you can now access your PHP website by entering `http://php.localhost` in your browser.

###Customize Website

1. You can customize your website in `./src` folder.
1. `http://php.localhost` will only look into `./src/public`.


You can try edit `./src/public/index.php` file and access `http://php.localhost` to see the changes.

----

###Soul Command

```bash
sh soul <COMMAND>
#example: sh soul up
#example: sh soul composer init
```

| COMMAND | Description |
| ------------ | ------------ |
| up | Create and run www service |
| down | Stop and delete www service |
| restart | Recreate and restart www service |
| shell | Access shell of www container |
| root-shell | Access shell of www container with root privilege |
| composer | Run composer command inside www container |
| cli | Access PHP-CLI of www container |
| exec | Run docker compose exec |


----