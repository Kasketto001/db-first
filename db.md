# DB FOR USED CARS DATA

>Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

DB_NAME: usedcar_dealership

TABLE_NAME: cars

-   **id** | PK | INDEX | INT | NOTNULL | AI | UNIQUE
-   **model**  | VARCHAR(50) | NOTNULL 
-   **cost** | MEDIUMINT(255) | NOTNULL
-   **seller_id** | FK | INT | NOTNULL | INDEX
-   **docs_id** | FK | INT | NOTNULL | INDEX 
-   **note** | TEXT