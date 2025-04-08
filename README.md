# Damn Vulnerable WordPress

## Installation

```
git clone https://github.com/cyber-courses/dvwp.git
cd dvwp/
docker compose up -d --build
sleep 10
docker compose run --rm wp-cli install-wp
```

## Stop
```
docker compose down
```

## Interface

* [http://127.0.0.1:31337](http://127.0.0.1:31337)
* [http://127.0.0.1:31337/wp-login.php](http://127.0.0.1:31337/wp-login.php)
* [http://127.0.0.1:31338/phpmyadmin/](http://127.0.0.1:31338/phpmyadmin/)
