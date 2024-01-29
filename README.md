# db-first

## Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

| Nome colonna | Tipo di dato | Attributi |
|---|---|---|
| id | INT | primary key, auto_increment |
| car_brand | VARCHAR(32) | nullable |
| car_model | VARCHAR(32) | nullable |
| production_year | DATE | nullable |
| kilometres | INT | default(0) |
| car_color | VARCHAR(16) | nullable |
| price | INT | default(0) |
| available | BOOLEAN | default(TRUE) |
| discount | TINYINT | default(0) |
| state | TINYINT | default(0) |
