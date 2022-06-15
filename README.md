# kubernetes-with-microservices-learning
the goal of this project is buying a phone under a blackFriday scenario and check total sales of phone with microservices.


# anotaciones kubernetes service

NodePort: 
Expone un puerto publico que vincula pods en especifico mediante el selector asignado, el puerto interno 80 puede ser expuesto
con el puerto 30004 mediante nodeport.

# anotaciones kubernetes deployment

Podemos vincular a un pod con un Deployment, deployment configurado permite el escalado horizontal creando replicas
del pod vinculado.

kubectl scale deployment nombre-deploy --replicas=N (N es el numero de replicas que queremos) nos permite generar este escalado.
