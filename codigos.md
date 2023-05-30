# Kubernetes 

## Comandos Gerais

### Aplicar Alterações
``` kubectl apply -f  [diretorio / arquivo.yaml] ```

### Verificar Configurações
``` kubectl config view ```

### Gerar Proxy
``` kubectl proxy --port=[porta] ```

### Execultar Algo no Kubernetes Dentro de um Pod
``` kubectl exec -it  [nome do pod]  -- [comando que deseja executar]```


### Listar Contextos
``` kubectl config get-contexts ```

### Alterar Contexto
``` kubectl config use-context [nome do contexto] ```

## Pod

### Redirecionamento de Portas de um Pod
``` kubectl port-forward pod/[ nome do pod] [porta externa: porta do serviço interno] ```

### Mostrar o Consumo do Pod, em CPU e Memoria
``` kubectl top pod [nome do pod ] ```


## ReplicaSet


## Deployment


## Service

### Redirecionamento de Portas de um Service
``` kubectl port-forward svc/[ nome do service] [porta externa: porta do serviço interno] ```

### Lista todos os Serviços da API
``` kubectl get apiservices ```


### Listar Services
``` kubectl get services ```
``` kubectl get svc ```