# docker-introduction
Una breve guida pratica sui fondamenti di docker.

## Cos'è docker
Docker è un progetto open source per automatizzare la distribuzione di app come contenitori portabili e autosufficienti che possono essere eseguiti nel cloud o in locale.

Poiché i contenitori richiedono un numero molto ridotto di risorse rispetto a macchine virtuali, ad esempio non necessitano di un sistema operativo completo, sono facili da distribuire e si avviano rapidamente. In questo modo è possibile ottenere un aumento della densità, vale a dire che è possibile eseguire più servizi nella stessa unità hardware, riducendo i costi.

Come effetto collaterale dell'esecuzione sullo stesso kernel, si ottiene un isolamento minore rispetto alle macchine virtuali.

# Link utili
## Dockerfile
[Official docker documentation](https://docs.docker.com/engine/reference/builder/)

## Network settings
Comandi utili per `docker run`: [Official docker documentation](https://docs.docker.com/engine/reference/run/#network-settings)

[Network creation](https://docs.docker.com/engine/reference/commandline/network_create/#specify-advanced-options)

# Comandi rapidi
 * Creazione di un network bridge diverso da quello default:\
`docker network create leo_network --subnet 192.168.10.0/24 --gateway 192.168.10.1`
