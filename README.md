# Wordpress theme working with docker

## Install

- copy the file `example.env` and rename the copy `.env` and change the username and password in it.
- Get the theme [Twenty TwentyFour](https://fr.wordpress.org/themes/twentytwentyfour/) from Wordpress and put it in the `themes` folder. It will be used as a fallback.

## Start

```
docker-compose -f docker-compose.yml up
```

## Tips

Placeholder content for themes can be found [here](https://github.com/WPTT/theme-unit-test).