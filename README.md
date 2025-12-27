# mlops-docker-demo
mlops-docker-demo


git add . | git commit -m"first commit" | git push

docker build -t flask-docker-demo .

docker build -t mlops-docker-demo .

docker pull hello-world

docker run hello-world

docker run -p 5000:5000 mlops-docker-demo

docker tag mlops-docker-demo rajeshkarel/mlops-docker-demo:latest1

docker push rajeshkarel/mlops-docker-demo:latest1
