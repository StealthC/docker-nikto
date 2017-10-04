# docker-nikto

Nikto Docker container.

## Pulling the image

```
docker pull stealthc/nikto
```

## Typical usage

```
docker run --rm -it stealthc/nikto -h http://test.site.com/
```

There is a volume in folder `/work/` where the script is executed.

## Authors

* **Carlos Alberto Castelo Elias Filho** - [StealthC](https://github.com/StealthC)
