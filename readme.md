# DB structure
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

# Table name
 - Veicoli_usati

# Table structure
- ID | BIGINT - AUTO INCREMENT - PK(UNIQUE) - NOT NULL
- Marca | VARCHAR(20) -  NOT NULL
- Modello | VARCHAR(40) - NOT NULL
- Anno | YEAR NOT NULL
- Data_acquisto | DATE NOT NULL
- Colore | VARCHAR(20) NULL
- Chilometraggio | INT
- Prezzo | DECIMAL(10,2)
- Carburante | VARCHAR(15)
- Potenza_cv | INT
- Cambio | VARCHAR(15)
- Tipologia | VARCHAR (50)
- Numero_porte | INT
- Numero_posti | INT
- Foto_veicolo | VARCHAR(260) 
- garanzia | BOOLEAN

