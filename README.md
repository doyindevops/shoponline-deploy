# shoponline-deploy

This Project is an Online Boutique is a cloud-native microservices demo application that I called online-shop-microservices

Online shop Microservice Boutique consists of 10-tier microservices application. The application is a web-based e-commerce app where users can browse items, add them to the cart, and purchase them.

This application works on any Kubernetes cluster, as well as Google, Digital Ocean , Linode Kubernetes Engines. It’s easy to deploy with little to no configuration.

I used a Digital Ocean server to provision and deploy the kubernetes cluster. Downloaded the Yaml config file and changed the user permission to allow only the owner permission to read with chmod 400.

Launch site with the node IP on the nodeport 30007
