# Command line tool (kubectl)

    kubectl [command] [TYPE] [NAME] [flags]
    
    * kubectl get pods 
    What it does?
        - List All Container Images Running in a Cluster

    *  kubectl create -f pod.yaml OR  kubectl apply -f pod.yaml
    What it does?
        - Creates the pod with the definitions in pod.yaml

    *  kubectl get replicationcontroller
    What it does?
        - Query the number of existing replicas

    *  kubectl get replicaset
    What it does?
        - Query the number of existing replicaset

    *  kubectl scale replicaset frontend-rs --replicas=6
    What it does?
        - Scale replicas - UP

    *  kubectl describe replicaset {{name-replicaset}}

    *  kubectl get all
  
    *  kubectl describe deployment {{name-deployment}}

    