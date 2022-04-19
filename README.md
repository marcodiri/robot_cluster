# Robots Cluster
## Modellazione e verifica di un algoritmo 2PC-like per il comportamento cooperativo di un pool di robot

Questo progetto affronta un caso di studio incentrato sul comportamento cooperativo tra robot,
al fine di coordinarsi per muovere oggetti pesanti.
I robot costituiscono i nodi di un sistema totalmente distribuito senza elementi di centralizzazione.
Il sistema è stato modellato su *Simulink* usando il formalismo *Stateflow*, descrivendo i robot
come **Extended Finite State Machine**.
Il progetto si è articolato su più fasi:
1. modellazione dei nodi robot e del sistema;
2. verifica formale delle proprietà di validity, liveness e agreement del sistema;
3. studio della scalabilità;
4. estensione alla possibilità di formazione di pool multipli contemporanei;
5. estensione alla possibilità di tollerare fallimenti di vario tipo.
