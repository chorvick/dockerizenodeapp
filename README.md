# dockerize  node app
                                                                                                     

docker run -p 49160:8080 -d <your username>/node-web-app
  
docker ps

# Example
ID            IMAGE                                COMMAND    ...   PORTS
ecce33b30ebf  <your username>/node-web-app:latest  npm start  ...   49160->8080
