## Quick Start
*Create .env file*

```.env
NAME=[git local user name]
EMAIL=[git local user email]
SRC=[blog project name]
STARTER=[Gatsby starter repository url]
```

*Init blog*

```
docker-compose run blog-init   
```

*Start Developing*
```
docker-compose run --service-ports blog-dev   
```

