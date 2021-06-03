### Goal

- frontend can connect to backend tcp port 80
- frontend can NOT connect to db port 80
- backend can connect to db port 80

### How to Use

1. cd to the directory. `cd networkpolicy/inter-namespace`
2. create resources. `kubectl create -f ./`
3. create additional resources of your choice to achieve the goal.
4. if stucked, examine contents in ./answer directory. You can create resources by using `kubectl create -f ./answer`
5. once finished, delete additional resources you created, and delete resources using `kubectl delete -f ./ --recursive`
