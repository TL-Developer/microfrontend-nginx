# microfrontend-nginx
Microfrontend with Nginx Proxy

# Application Ports Running
Angular App => :80
Ember App => :81
React App => :82
Vue App => :83

# Docker build
```docker build -t orchestrator .```

# Docker run
```docker run --name orchestrator -d -p 80:80 orchestrator```

# Docker compose build all apps
```docker-compose build orchestrator angular-app ember-app react-app vue-app```

# Docker compose running all apps
```docker-compose up```