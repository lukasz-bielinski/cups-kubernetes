    k apply -f  psp-privileged.yaml
    k apply -f  role-psp.yaml
    k apply -f  rolebinding-psp.yaml
    k apply -f cups-sa.yaml
    k apply -f cups-deployment.yaml
