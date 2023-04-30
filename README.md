# VLSM

## Cos'è il VLSM?

Il VLSM (Variable Length Subnet Mask) è una tecnica utilizzata per suddividere una rete in sottoreti di dimensioni diverse. Questo permette di assegnare un numero di indirizzi IP appropriato a ciascuna sottorete, in base alle necessità. In pratica, si suddivide la rete in sottoreti più piccole, in modo da utilizzare solo gli indirizzi IP necessari per ogni sottorete e minimizzare gli sprechi.

## Svolgimento
In questo problema di laboratorio dovevamo creare una rete composta da :
<ul>
    <li>Tre Router</li>
    <li>Sei Switch</li>
    <li>Sei PC</li>
</ul>
e ad ogni pc dovevamo configurare l'ip e la subnet mask corrispondente alla slash notations che gli è stata assegnata.

![image](https://user-images.githubusercontent.com/116788504/235343521-392084c8-518f-499c-a45c-8571ac7d4ed5.png)

Successivamente diamo un ordine a queste sottoreti in ordine di grandezza: 

La sottorete A è quella che occupa 50 dispositivi :

![image](https://user-images.githubusercontent.com/116788504/235344874-80514803-81ad-41ba-9d41-72f5cefab6bf.png)

La sottorete B è quella che occupa 31 dispositivi: 

![image](https://user-images.githubusercontent.com/116788504/235344944-c5373e60-939a-45ce-ab2f-a77f55d24503.png)

La sottorete C è quella che occupa 25 dispositivi :

![image](https://user-images.githubusercontent.com/116788504/235344989-2c3026ad-0851-40ad-a17d-63594b04d6d5.png)

La sottorete D è quella che occupa 19 dispositivi :

![image](https://user-images.githubusercontent.com/116788504/235345031-374ad941-82ea-4c3e-9905-161be3dfe920.png)

La sottorete E è quella che occupa 12 dispositivi :

![image](https://user-images.githubusercontent.com/116788504/235345074-da3430fe-4c57-41d5-8d62-a4f9d0cbd0de.png)

La sottorete F è quella composta da 10 dispositivi :

![image](https://user-images.githubusercontent.com/116788504/235345102-7dc377e7-d305-4abf-864f-6db0c7bf83ed.png)

Le sottoreti G ed H sono quelle che occupano 2 dispositivi :

![image](https://user-images.githubusercontent.com/116788504/235345142-d7451ee8-1390-47ad-937d-d8e60950bc66.png)


ora guardando questa tabella :

![image](https://user-images.githubusercontent.com/116788504/235343706-810fc016-34ac-4671-bb5b-117d5d1748d6.png)

dobbiamo suddividere le reti assegnando uno specifico range di ip e il risultato sarà questo : 

![image](https://user-images.githubusercontent.com/116788504/235343866-275951fc-61e1-4913-b433-1ba57b28c3c3.png)



Impostati poi gli ip e le subnet mask di ogni dispositivo per capire se si è volto un buon lavoro bisogna fare una simulazione e dobbiamo fare in modo che i dispositivi iniviino un messaggio ai router per poter comunicare con ii dispositivi di altre sottoreti e poi questo messaggio ritorna indietro e se la comunicazione sarà andata a buon fine avremo un risultato di questo tipo:

![img](https://user-images.githubusercontent.com/116788504/235344486-f5b97161-9412-445b-bb71-61ea3dedc1ad.jpg)


![img](https://user-images.githubusercontent.com/116788504/235344496-eaceab5c-e2ba-41f7-8851-60ae7b84c065.jpg)


![img](https://user-images.githubusercontent.com/116788504/235344508-86a8e4ff-f23d-4e49-bd97-6aa51532e1ce.jpg)


![img](https://user-images.githubusercontent.com/116788504/235344520-52404860-6fe8-41b0-bf45-4deb5862baff.jpg)


![img](https://user-images.githubusercontent.com/116788504/235344534-7d1849bc-1504-480a-af71-e7a4f3ee4d83.jpg)

## Conclusione

Questa tecnica è molto utile quando si ha a che fare con reti di grandi dimensioni, in cui gli indirizzi IP possono essere un fattore critico per il funzionamento corretto della rete stessa. Inoltre, consente di minimizzare gli sprechi di indirizzi IP, che altrimenti potrebbero non essere utilizzati e quindi sprecati.

Per implementare correttamente il VLSM, è necessario conoscere bene le reti e le loro esigenze, in modo da suddividere correttamente la rete in sottoreti di dimensioni adeguate. Inoltre, è importante prestare attenzione alla configurazione dei dispositivi di rete, in modo da assicurarsi che ogni dispositivo abbia l'indirizzo IP corretto e sia configurato correttamente per la sottorete in cui si trova.

In sintesi, il VLSM è una tecnica importante per la configurazione di reti di grandi dimensioni, in cui la gestione degli indirizzi IP è un fattore critico per il funzionamento corretto della rete stessa. La sua corretta implementazione richiede una buona conoscenza delle reti e delle loro esigenze, nonché una attenzione alla configurazione dei dispositivi di rete.


