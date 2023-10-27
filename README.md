# learn-kubernetes

kubectl create secret docker-registry aws-ecr --docker-server=299627189740.dkr.ecr.us-east-1.amazonaws.com --docker-username=AWS --docker-password=$(aws ecr get-login-password)
