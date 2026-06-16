commands used  in POD  

kubectl get node

kubectl get pod

kubectl get service

kubectl apply -f . 
this will deploy entire folder, we can also deploy all the files one by one  all the will get deployed
to check run the get pod, node and services command again

kubectl get node    -o wide
we will get IP address which we can run in the browser

To scale the application use the below command

kubectl scale deployement vote --replicas=5 

