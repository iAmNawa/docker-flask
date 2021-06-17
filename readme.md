# docker flask app
## how to run
clone repo   
cd docker-flask   
pip3 freeze > requirements.txt    
docker build --tag docker-flask .   
docker run --publish 5000:5000 docker-flask       

## to view images
docker images
