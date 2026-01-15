a new user naresh is onboarding to cluster and need permission to get, list, create, update, delete and watch pods, src, ns
 openssl genrsa -out naresh.key 4096
 cat naresh.key
 openssl req -new -key naresh.key -out naresh.crt
