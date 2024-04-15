# Microfrontend NGINX with Docker
Microfrontend agnostic framework with Nginx Proxy Reverse

# Run all project by entrypoint automatically
```./entrypoint.sh```

# Application running on port 80
![alt text](image.png)

## /angular =>

![alt text](image-1.png)

## /ember =>

![alt text](image-2.png)

## /react =>

![alt text](image-3.png)

## /vue =>

![alt text](image-4.png)

# To run manually

## Docker compose build all apps
```docker-compose build orchestrator angular-app ember-app react-app vue-app```

## Docker compose running all apps
```docker-compose up```