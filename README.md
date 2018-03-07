<!-- TOC -->

- [Leggimi](#leggimi)
    - [Dati](#dati)
        - [Anagrafica geografica](#anagrafica-geografica)
        - [Votanti](#votanti)
        - [Scrutini](#scrutini)

<!-- /TOC -->

## Leggimi

Degli script per scaricare i dati sulle elezioni politiche del 4 marzo 2018 in Italia.

### Dati

#### Anagrafica geografica

- per la Camera: [camera_geopolitico_italia.csv](./dati/camera_geopolitico_italia.csv)
- per il Senato: [senato_geopolitico_italia.csv](./dati/senato_geopolitico_italia.csv)

Sotto un esempio della struttura gerarchica per la Camera.

**Nota Bene**: alla voce denominata "Comune" su Eligendo non corrispondono sempre in modo univoco dei comuni, ma per città grandi anche parte di esse (come `24120550510`, che non è il Comune di Palermo per intero, ma una sua parte).

| ID          | Nome                          | Livello gerarchico     | URI                                                                                                                                                            | 
|-------------|-------------------------------|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------| 
| 24000000000 | SICILIA 1 | Circoscrizione | [http://elezioni.interno.gov.it/camera/scrutini/20180304/scrutiniCI24000000000](http://elezioni.interno.gov.it/camera/scrutini/20180304/scrutiniCI24000000000) | 
| 24100000000 | SICILIA 1 - 01 | Collegio plurinominale | [http://elezioni.interno.gov.it/camera/scrutini/20180304/scrutiniCI24100000000](http://elezioni.interno.gov.it/camera/scrutini/20180304/scrutiniCI24100000000) | 
| 24120000000 | 02 - PALERMO - LIBERTÀ | Collegio uninominale | [http://elezioni.interno.gov.it/camera/scrutini/20180304/scrutiniCI24120000000](http://elezioni.interno.gov.it/camera/scrutini/20180304/scrutiniCI24120000000) | 
| 24120550510 | PALERMO - SICILIA 1 - 01 - 02 | Comune | [http://elezioni.interno.gov.it/camera/scrutini/20180304/scrutiniCI24120550510](http://elezioni.interno.gov.it/camera/scrutini/20180304/scrutiniCI24120550510) | 



#### Votanti

- votanti per Comune Camera > [votantiCIComuni.csv](./dati/votantiCIComuni.csv)
- votanti per Comune Senato > [votantiSIComuni.csv](./dati/votantiSIComuni.csv)
- anagrafica con i codici delle province > [anagraficaProvince.csv](./dati/anagraficaProvince.csv)

**NOTA BENE**: manca la sezione Estero e Valle D'Aosta

#### Scrutini

- scrutini Camera per Circoscrizione: [scrutiniCI_c.csv](./dati/scrutiniCI_c.csv)
- scrutini Camera per Collegio Plurinominale: [scrutiniCI_p.csv](./dati/scrutiniCI_p.csv)
- scrutini Camera per Collegio Uninominale: [scrutiniCI_u.csv](./dati/scrutiniCI_u.csv)
- scrutini Camera per Comune (in realtà non sono strettamente i "Comuni", ma sono definiti come "Comuni" in Eligendo): [scrutiniCI_cm.csv](./dati/scrutiniCI_cm.csv)
- scrutini Senato per Circoscrizione: [scrutiniCI_c.csv](./dati/scrutiniSI_c.csv)
- scrutini Senato per Collegio Plurinominale: [scrutiniSI_p.csv](./dati/scrutiniSI_p.csv)
- scrutini Senato per Collegio Uninominale: [scrutiniSI_u.csv](./dati/scrutiniSI_u.csv)
- dati di riepilogo: [riepilogo.csv](./dati/riepilogo.csv)


**NOTA BENE**: manca la sezione Estero e Valle D'Aosta