### Goal

- create an ingress rule to forward the request as below:
  - /service1 goes to service:service1
  - /service2 goes to service:service2

### Prerequisite

- Install ingress controller: `kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.46.0/deploy/static/provider/baremetal/deploy.yaml`

### How to use

1. cd to the directory.
2. create resources. `kubectl create -f ./`
3. create additional resources of your choice to achieve the goal.
4. if stucked, examine contents in ./answer directory. You can create resources by using `kubectl create -f ./answer`
5. once finished, delete additional resources you created, and delete resources using `kubectl delete -f ./ --recursive`

