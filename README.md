This Project Perfect example for Docker and Kuberetes
# To chekc the mongodb server data commands
kubectl exec -it mongodb-deployment-6b466f4bd9-gftn7 -- mongosh

use myDatabase

db.users.find().pretty()
