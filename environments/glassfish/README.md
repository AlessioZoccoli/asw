# GlassFish 

Questo � un ambiente di esecuzione per applicazioni Java EE, 
ed � composto da due macchine virtuali: 
un server **glassfish** e un **client**. 

## Descrizione delle macchine virtuali 

### glassfish

La macchina virtuale **glassfish**  
� per l'esecuzione di applicazioni Java EE *lato server*, 
ed ha il seguente software: 

* Ubuntu Precise (12.04 LTS) a 64 bit 

* Oracle Java SDK 

* Oracle Java EE 7u2 (GlassFish 4.1.1) 

Configurazione di rete 

* Indirizzo IP: 10.11.1.111 

* Porte pubblicate sull'host: 8080 
 
### client

La macchina virtuale **client**  
� per l'esecuzione di applicazioni Java EE *lato client*, 
ed ha il seguente software: 

* Ubuntu Precise (12.04 LTS) a 64 bit 

* Oracle Java SDK 

* appclient per Oracle Java EE 7u2 (GlassFish 4.1.1) 

* altre librerie client, come *curl* 

Configurazione di rete 

* Indirizzo IP: 10.11.1.211 

