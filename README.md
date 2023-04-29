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

    *  kubectl rollout status {{name-deployment}}

    *  kubectl rollout history {{name-deployment}}

    *  kubectl set image deployment frontend-dp frontend-container={{image}} --record
    What it does?
        - Updates the image directly from the command line

    * kubectl rollout undo deployment/frontend-dp --to-revision={{revision}}

    * kubectl rollout undo deployment/frontend-dp

    * kubectl get namespaces

    * kubectl get pods -n {{namespace}}

    * kubectl get all -n {{namespace}}