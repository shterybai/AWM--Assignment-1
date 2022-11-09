# AWM: Assignment 1

## Images of the website:
![login](https://raw.githubusercontent.com/shterybai/AWM--Assignment-1/main/READMEimages/login.png?token=GHSAT0AAAAAAB27PU3RERG563AI27QGGUPWY3MGM6A)
![register](https://raw.githubusercontent.com/shterybai/AWM--Assignment-1/main/READMEimages/register.png?token=GHSAT0AAAAAAB27PU3RR4BWSBHWMDBULBG2Y3MGNEQ)
![map](https://raw.githubusercontent.com/shterybai/AWM--Assignment-1/main/READMEimages/map.png?token=GHSAT0AAAAAAB27PU3RG2CEAD2DJBDGKWPUY3MGNBQ)
 
## Link to the website (broken): 
https://www.shterybai.xyz

## Issues I Encountered
Unfortunately, I was not able to get the deployment working in the end; I made my way all the way up to the end of Lab 6, however unfortunately I didn't have enough time to resolve an issue where, when starting the wmap_nginx_certbot Docker container, the port that it wanted to listen to (:443) was already being occupied, and could not deploy. Below is a screenshot of my final issue:

![console](https://raw.githubusercontent.com/shterybai/AWM--Assignment-1/main/READMEimages/console.png?token=GHSAT0AAAAAAB27PU3QH6YNEUVQ6PEJJAQUY3MGMYA)

As can be seen, the PostGIS, PgAdmin4, and Django container have been started, and are currently running as is expected. However, PgAdmin4 is currently occupying port :443, which is needed to start the wmap_nginx_certbot. As a result, the container cannot start, and therefore the website cannot be deployed. 
