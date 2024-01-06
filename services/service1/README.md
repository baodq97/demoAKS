docker build -t flask-sample:latest .
docker run -d -p 5000:5000 flask-sample

kubectl apply -f deployment.yaml
kubectl apply -f service.yaml