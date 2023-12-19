### AUTO USATE
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Nella repo dovete consegnare un file con tutti i campi della tabella, tipo di dato ed eventuali attributi per ogni campo.
|Campo|Tipo di dato| Attributi |
|:---:|:---:|:---:|
|CodAuto|integer| Chiave primaria|
|Marca| not null - Varchar(255)| |
|Modello|not null -Varchar(255)| |
|Colore| not null -Varchar(255)|  | 
|Prezzo| not null - Float||
|Sconto| not null - Float||
|Iva| not null - Float||
|KmPercorsi|not null - Integer||
|AnnoImm| not null - Integer||
|CodProprietario|null - Integer | Chiave esterna - Proprietario|
