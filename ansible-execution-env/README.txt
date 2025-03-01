Install command:
helm install ansible-execution-env ./ansible-execution-env --create-namespace

Change namespace:
kubectl config set-context --current --namespace=ansible-execution-env

Upgrade command:
helm upgrade ansible-execution-env ./ansible-execution-env
