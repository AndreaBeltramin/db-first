# Cars table

| name                     | type        | attributes                          | key     | note                                             |
| ------------------------ | ----------- | ----------------------------------- | ------- | ------------------------------------------------ |
| id                       | BIGINT(20)  | NOT NULL - AUTOINCREMENT - UNSIGNED | PRIMARY |                                                  |
| numero_telaio            | CHAR(17)    | NOT NULL                            |         |                                                  |
| targa                    | CHAR(7)     | NOT NULL                            |         |                                                  |
| marca                    | VARCHAR(30) | NOT NULL                            |         |                                                  |
| modello                  | VARCHAR(30) | NOT NULL                            |         |                                                  |
| prezzo                   | SMALLINT    | NOT NULL - FLOAT(8, 2) - UNSIGNED   |         |                                                  |
| paese_di_origine_sigla   | CHAR(2)     | NOT NULL                            |         |                                                  |
| anno_mmatricolazione     | DATE        | NOT NULL                            |         |                                                  |
| tipo_cambio              | VARCHAR(15) | NOT NULL                            |         |                                                  |
| km_tot_percorsi          | SMALLINT    | NOT NULL - UNSIGNED                 |         |                                                  |
| tipo_carburante          | VARCHAR(15) | NOT NULL                            |         |                                                  |
| data_ultima_revisone     | DATE        | NOT NULL                            |         |                                                  |
| data_ultimo_tagliando    | DATE        | NOT NULL                            |         |                                                  |
| numero_posti             | TINYINT     | NOT NULL - UNSIGNED                 |         |                                                  |
| numero_porte             | TINYINT     | NOT NULL - UNSIGNED                 |         |                                                  |
| stato_usura              | CHAR(1)     | NOT NULL                            |         | 'n'= nuovo, 'o'= ottimo, 'b'=buono, 'd'=discreto |
| pronta_consegna          | CHAR(1)     | NOT NULL                            |         | 's'= si, 'n'= no                                 |
| n_proprietari_precedenti | TINYINT     | NOT NULL - UNSIGNED                 |         |                                                  |
| potenza_motore_cv        | SMALLINT    | NOT NULL - UNSIGNED                 |         |                                                  |
| colore                   | VARCHAR(20) | NOT NULL                            |         |                                                  |
| tipo_carrozzeria         | VARCHAR(15) | NOT NULL                            |         |                                                  |
| tipo_trazione            | VARCHAR(15) | NOT NULL                            |         |                                                  |
| cilindrata               | SMALLINT    | NOT NULL - UNSIGNED                 |         |                                                  |
| peso_kg                  | SMALLINT    | NOT NULL - UNSIGNED                 |         |                                                  |
| lunghezza_cm             | SMALLINT    | NOT NULL - UNSIGNED                 |         |                                                  |
| classe_emissioni         | TINYINT     | NOT NULL - UNSIGNED                 |         |                                                  |
| consumi                  | VARCHAR(10) | NOT NULL                            |         |                                                  |
