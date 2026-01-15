by default each pod gets default serviceAccountName - default. 
It doesn't not have permission to query the kubernetes objects

Lets create a service-account - hr-sa which can query the pods under hr namemespace
create role and role-binding
hr-role
hr-rolebinding
