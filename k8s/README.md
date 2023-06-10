# Kubernetes focussed - CKA/CKS tips from Deengineers

## CKA Topics to revise

## CKS Topics to Revise On

Here are the CKS (Certified Kubernetes Security Specialist) topics ranked on a scale of 1 to 5, with 1 being easy and 5 being hard:

- Trivy (1)
- Imagepolicywebhook (4)
- PSPs (3)
- NetPols (all types) (4)
- Dockerfile best/security practices (3)
- K8s yaml best/security practices (3)
- RBAC + Service Accounts (3)
- AppArmor (3)
- Secret mounted to Pod (3)
- Seccomp (3)
- Runtimeclass (2)
- Kube-bench (3)
- Audit policy (basic and advanced) (4)
- Falco (5)
- Automounting service token on pod/deployment (on K8s docs) (2)
- Kube-sec scan (1)
- Etcd encryption (4) (not covered in Mumshad's but covered in Kim's course)

### Tip/Trick

A helpful tip/trick that people often don't mention:

- MAKE SURE to make a COPY of your kube-api config file to your root directory in case it messes up
- Always restart kube-api whenever you change the YAML for it

### Additional Points

To add on:

- Be comfortable with kube-api server debugging (you'll adjust this a lot!)

This overview provides a ranking of CKS topics along with a useful tip/trick. Make sure to revise and study these topics to prepare for the CKS certification exam.