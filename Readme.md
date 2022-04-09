**Description**

This is the repo I use to host my microservices that I use for my home-server. 
I have classified and organised them in individual folders as per their use-cases.

1. dev-tools - contains some dev-tools like theia a code editor.
2. duckdns - for automatically updating global ip with duckdns dns name.
3. home-server - contains main microservices like jackett, sonarr, jellyfin etc.
4. nextcloud - for deploying nextcloud and nextclouddb for private cloud.
5. nginx - for nginx proxy manager.
6. stash - for stash microservice.
7. tick - telemetry stack.

You need to deploy each folder individually. I kept it that way so I can chose to what to deploy as per my needs.

Steps -

1. Download and install docker and docker-desktop
2. Clone Repo and run after going into each directory based on your needs

To Start
```
docker-compose up -d
```

To Stop
```
docker-compose down
```

Guide to help understand what tools you are installing, and additional configurations after you have set them up - 
1. https://www.smarthomebeginner.com/docker-home-media-server-2018-basic/
2. https://zacholland.net/a-complete-guide-to-setting-up-a-plex-home-media-server-with-automated-requests-downloads/
