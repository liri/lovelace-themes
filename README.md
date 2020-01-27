# Google Home Theme

Following this request, I've been working on 2 themes to match the design of "google home":
https://community.home-assistant.io/t/why-can-t-we-have-ui-like-these-quite-inspiring/99740?u=naofireblade

Hope you'll like it!

## Installation on HASS
Set theme to true in your configuration file:
https://hacs.netlify.com/installation/configuration/

Afterwards, you have to do another manual step by adding the repository (https://github.com/liri/lovelace-themes) as a custom repository, as it has not been added to HACS by default

## Installation on HA
Simply download google-home.yaml file into your homeassistant configuration folder and inside your configuration.yaml file import the file:

```
frontend:
  themes: !include google-home.yaml
```


## Light
![Light](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Light/1.JPG)
![Light](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Light/3.JPG)

## Dark
![Dark](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Dark/1.JPG)
![Dark](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Dark/3.JPG)

## Additional Screenshots
![Light](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Light/2.JPG)
![Light](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Light/4.JPG)
![Light](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Light/5.JPG)
![Light](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Light/6.png)
![Light](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Light/7.png)
![Light](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Light/8.png)
![Light](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Light/9.png)
![Light](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Light/10.png)

![Dark](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Dark/2.JPG)
![Dark](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Dark/4.JPG)
![Dark](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Dark/5.JPG)
![Dark](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Dark/6.png)
![Dark](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Dark/7.png)
![Dark](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Dark/8.png)
![Dark](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Dark/9.png)
![Dark](https://raw.githubusercontent.com/liri/lovelace-themes/master/screenshots/Google%20-%20Dark/10.png)

Font I used for my HA dashboard: Open Sans & Rubik (for hebrew)
