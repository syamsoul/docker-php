# Docker PHP

This repo will helps anyone to start their PHP development or even beginner to start to learn and experimented PHP without installing complicated app/software such as WampServer, Nginx, Apache, etc.

No need to worry if you have ZERO knowledge about Docker. You still can use this.

<br />

----

<br />

## Requirement

- Docker

Yes, it only require Docker to run PHP web and CLI.

<br /><br />

## How to Use

<br />

### Basic Usage

1. `git clone https://github.com/syamsoul/docker-php.git <YOUR_APP_FOLDER_NAME>`
1. `cd <YOUR_APP_FOLDER_NAME>`
1. `sh soul up`

That's it, you can now access your PHP website by entering `http://php.localhost` in your browser.

<br />

### Customize Website

1. You can customize your website in `./src` folder.
1. `http://php.localhost` will only look into `./src/public`.


You can try edit `./src/public/index.php` file and access `http://php.localhost` to see the changes.

##### Default accessible page
- `http://php.localhost` (Homepage)
- `http://php.localhost/about-us/` (About Us page)
- `http://php.localhost/simple.php` (directly render php file)

<br />

### Soul Command

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

<br /><br />

## Support me

If you find this repo helps you, kindly support me by donating some BNB (BSC) to the address below.

```
0x364d8eA5E7a4ce97e89f7b2cb7198d6d5DFe0aCe
```

<img src="https://info.souldoit.com/img/wallet-address-bnb-bsc.png" width="150">

<br /><br />