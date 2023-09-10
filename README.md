# Multicontainer application
# http://a647cc27301224ae8bd7294ade9ef2ed-1024933611.us-west-1.elb.amazonaws.com/
Codeching - video 9 - Multi container deployment kubernetes | React| Node.js | Postgres | Ingress Nginx | step by step


It contains React client, Node.js backend, PostgreSQL and Nginx

You should install Ingress Nginx with command:
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.46.0/deploy/static/provider/cloud/deploy.yaml

After that you can use the following command to start in main folder:

kubectl apply -f k8s

In this lesson, I will build simple website including reactjs app, nodejs app and nginx to redirect request.
I using ECR to store docker images and github action to build, deploy and trigger EKS
This is result http://a647cc27301224ae8bd7294ade9ef2ed-1024933611.us-west-1.elb.amazonaws.com/
Some images results, I will be attach below
AWS ECR
![Screenshot from 2023-09-10 14-14-01](https://github.com/phongvudai/final/assets/22408187/202adc1e-10ff-4b5f-a294-5a843db619ea)

Github action 
![image](https://github.com/phongvudai/final/assets/22408187/09df4a4c-a826-4065-8a95-e171d90367a9)

Kubectl pods
![image](https://github.com/phongvudai/final/assets/22408187/0a72c75a-2e14-470d-965e-c6b08da20b05)
