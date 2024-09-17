To run this APi on your local machine follow these steps:-

1.  Start Minikube on your local machine by running the command Minikube start
2.  check the status of minikube by running the command Minkube status
3.  Run the command using kubectl kubectl apply -f Kubrenetes.yml
4.  This would run your deployment,services and pods
5.  To see if all of these are running execute commands like kubectl get pods, kubectl get deployment, kubectl get services and get your minikube ip by running minikube ip command
6.  Run command curl http://(minikube ip):(nodePort)/WeatherForecast to get response \*nodeport is 30443
7.  run command curl http://(minikube ip):(nodePort)/health to see if it is healthy or not \*nodeport is 30443
