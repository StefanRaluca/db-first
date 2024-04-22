## Descrizione:
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## table: used cars for sale

- ID INT UNIQUE PRIMARY_KEY AUTO_INCREMENT | NOTNULL
- Brand  VARCHAR(15) | NOTNULL
- Model  VARCHAR(25) | NOTNULL
- Year YEAR | NULL
- Km FLOAT(7,2) | NOTNULL
- Power VARCHAR(4) | NULL
- Color VARCHAR(15) | NULL
- Type_fuel VARCHAR(10) |NULL
- Doors TINYINT | NULL
- Cover_image VARCHAR() |NULL
- Sold  VARCHAR(10) | NOTNULL | DEFAULT false
- Price DECIMAL(8,2) |NOTNULL
- Insertion_date DATE |NULL
- Note TEXT | NULL



| ID  | Brand | Model | Year | Km | Power | Color | Type_fuel | Doors | Cover_image | Sold | Price | Insertion_date | Note |
