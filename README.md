# Cars Store

## Schema tabella `used cars`
| Nome Colonna | Tipo | Attributi | Index |
|---|---|---|---|
| id | UNSIGNED INT | NOT NULL AUTO INCREMENT | PRIMARY KEY |
| model | VARCHAR(50) | NOT NULL | INDEX |
| brand | VARCHAR(50) | NOT NULL | INDEX |
| body_type | VARCHAR(50) | NOT NULL | INDEX |
| year | DATE | NOT NULL | INDEX |
| price | DECIMAL(7,2) | NOT NULL | INDEX
| doors | TINYINT | NULL |
| seats | TINYINT | NULL
| fuel_type | ENUM('benzina', 'diesel', 'gpl', 'metano', 'ibrida', 'elettrica') | NOT NULL | INDEX
| horse_power | SMALLINT | NULL |
| transmission | ENUM('manuale', 'automatico') | NOT NULL | INDEX |
| mileage | UNSIGNED INT | NOT NULL | INDEX |
| color | VARCHAR(50) | NULL |  |
| engine_size | SMALLINT | NULL |
| weight | SMALLINT | NULL |  |
| emission_class | VARCHAR(50) | NULL | INDEX |
| description | TEXT | NULL |  |
| vin | CHAR(17) | NOT NULL | UNIQUE |
| status | ENUM('dispopnibile', 'prenotata', 'venduta') | NOT NULL | INDEX |
| license_plate | CHAR(7) | NOT NULL | UNIQUE |
