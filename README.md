# Microservices-with-kubernetes

#login to database
kubectl exec -it webapp-86bd4996fc-c88jj sh
>etc/
mysql -h database -uroot -ppassword databasename

#create secret object
kubectl create secret generic name --from-literal key=value
