# asw-655-docker-composizione

Questo progetto contiene alcune applicazioni che esemplificano 
il rilascio di applicazioni composte da uno o pi� servizi,  
da eseguire su un nodo [docker](../../environments/docker/) 
oppure in un cluster [docker-swarm](../../environments/docker-swarm/). 

In particolare, le applicazioni sono delle varianti di quelle mostrate 
nel progetto [asw-885-spring-cloud/](../asw-885-spring-cloud/). 
Gli esempi sono relativi a due applicazioni principali, mostrate in pi� versioni: 

* l'applicazione **lucky-word**  

* l'applicazione **sentence**  


### Applicazione **lucky-word**

L'applicazione **lucky-word**, in questo caso, � formata da un solo servizio. 
Dopo essere stata compilata, pu� essere eseguita creando ed avviando un contenitore Docker. 


### Applicazione **sentence**

L'applicazione **sentence** � invece formata da pi� servizi, e realizzata in pi� versioni: 
  
* **b-sentence** pu� essere eseguita in un nodo Docker ([docker](../../environments/docker/)), con *Docker* oppure con *Docker Compose* 

* **c-sentence-swarm-eureka-zuul** pu� essere eseguita in un cluster Docker ([docker-swarm](../../environments/docker-swarm/)), come *stack Docker* 

* anche **d-sentence-swarm-zuul** pu� essere eseguita in un cluster Docker ([docker-swarm](../../environments/docker-swarm/)), come *stack Docker* 

### Ambiente di esecuzione 

Queste applicazioni vanno eseguite negli ambienti 
[docker](../../environments/docker/) 
oppure [docker-swarm](../../environments/docker-swarm/). 

