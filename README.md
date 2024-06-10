# DevOps-task
To copy database into pod
kubectl cp database.sql mysql-test-0:/tmp -n test

used helm charts 
helm install mysql-test bitnami/mysql --namespace test --set auth.rootPassword=my-root-password,auth.database=mydatabase
