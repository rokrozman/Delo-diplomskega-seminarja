# Delo-diplomskega-seminarja
V delu diplomskega seminarja smo s strojnim učenjem naredili napovedne modele za trgovanje s kriptovalutami.

Podatki se nahajajo v mapi **podatki** in so že pripravljeni za učenje klasifikacijskih modelov. 
Podatki vsebujejo štiri *csv* datoteke, ki predstavljajo gibanje tečaja v obliki japonskih svečnikov za različne časovne intervale.
- BTC-USDT, časovni interval 15min.
- BTC-USDT, časovni interval 1 ura.
- ETH-USDT, časovni interval 15min.
- ETH-USDT, časovni interval 1 ura.

V zvezku **Napovedni_modeli** se nahajajo vsi napovedni modeli, ki smo jih uporabili. 
To so:
- Model *k*-najbližjih sosedov.
- Model logistične regresije.
- Model odločitvenih dreves.

V zvezku se nahajajo tudi vsa navodila kako učenje in ocenjevanje modelov izvedemo.
Modele preverimo tudi s simulacijo trgovanja, kjer izračunamo  dobiček, ki ga je
model ustvaril. To naredimo s pomočjo funkcije, ki se nahaja v **Profit**.

