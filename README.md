# paper-towel-roller-redesign
### 1-Descrizione del problema:  
All’interno del distributore della carta per asciugare le mani, c’è un cilindro di materiale plastico.   
Ho quattro distributori di carta, con all’interno un rullo. In ciascuno dei quattro distributori, i quattro rulli si sono rotti tutti nello stesso punto. Il che non è una coincidenza.  
Essendo il rotolo di carta lungo quanto il cilindro, il carico distribuito può essere pensato come una forza concentrata al centro del cilindro di plastica.   
A questo punto, chiaramente, questo cilindro può essere schematizzato come una trave incastrata in entrambi gli estremi; quindi il momento flettente è massimo alle estremità, da qui la rottura della parte.    
###   
### 2-Fotografia del vecchio rullo:  
![pezzo_rotto](https://github.com/user-attachments/assets/1f42476b-0ed5-4be2-9e5f-85186191beb1)
###   
### 3-Spiegazione vincoli di progetto:  
Nella progettazione,ho dovuto tenere conto, chiaramente, di alcuni vincoli dettati dall’utilizzo della stampante 3D.   
La mia stampante ha un piatto di 120mm x 120mm. Il cilindro è di 253mm, quindi fuori dimensione massima, anche considerandolo con un diametro di dimensione infinitesimale e mettendolo in diagonale.  
Ho quindi deciso di dividerlo in due metà esatte di lunghezza 126.5mm ciascuna, e di unirle attraverso l’uso di una spina di lunghezza 20mm, inserita nei fori ricavati su entrambi i cilindri. I fori hanno entrambi 10mm di profondità e un diametro di 5mm.   
La spina è stata fatta anch’essa di 5mm, per avere un’accoppiamento con leggera interferenza (considerando le tolleranze di una stampa 3D), evitando così l’uso di una colla.   
###   
### 4-Disegno del primo prototipo:  
![schizzo_primo_prototipo](https://github.com/user-attachments/assets/a1d11178-77e4-4a18-b131-bc5cad75c832)
###   
### 5-Stampa del primo prototipo:  
 ![Uploading primo_prototipo.jpg…]()
###   
### 6-Problemi con il primo prototipo:  
L’accoppiamento si è rivelato essere poco solido. Se flesso con una certa forza e insistenza la spina all’interno del cilindro si rompe abbastanza facilmente.   
Il problema più grave però è dovuto allo spessore della parte che era fragile nel prodotto originale, che è stata ingrandita, ma troppo. Adesso,nel processo in cui, manualmente, va tolto il cilindro dalla sua scatola, rimane spesso incastrato e rende il procedimento lento e abbastanza difficile.
###   
### 7-Migliorie:  
Per garantire un accoppiamento più solido basta aumentare al dimensione della spina. Per quanto riguarda l’estremità, invece, va diminuito lo spessore. Idealmente in una via di mezzo tra quello attuale di 3mm (troppo grosso) e quello originale di (troppo sottile, punto debole dell’oggetto). Opto per una misura di   
2.2mm.   
###   
### 8-Disegno del secondo prototipo:  
 ###   
### 9-Stampa del secondo prototipo:  
![Uploading secondo_prototipo.jpg…]()
