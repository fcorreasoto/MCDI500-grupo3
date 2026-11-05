# Validación del dataset — MCDI500

**Archivo:** `Inventario_Publico_de_Glaciares_2022.csv` · 26180 filas × 45 columnas

## Perfil de variables

| variable | dtype | rol | unicos | pct_nulos |
| --- | --- | --- | --- | --- |
| OBJECTID | int64 | identificador | 26078 | 0.0 |
| Id | int64 | discreta | 1 | 0.0 |
| COD_GLA | str | identificador | 26180 | 0.0 |
| NOMBRE | str | alta cardinalidad | 431 | 0.0 |
| CLASIFICA | str | nominal | 5 | 0.0 |
| AREA_KM2 | float64 | continua | 2323 | 0.0 |
| REGION | str | alta cardinalidad | 16 | 0.0 |
| PROVINCIA | str | alta cardinalidad | 40 | 0.0 |
| COMUNA | str | alta cardinalidad | 84 | 0.0 |
| DATUM | str | nominal | 1 | 0.0 |
| HUSO | str | nominal | 1 | 0.0 |
| NORTE | int64 | identificador | 25948 | 0.0 |
| ESTE | int64 | continua | 24677 | 0.0 |
| FUENTE_DIG | str | alta cardinalidad | 19 | 0.0 |
| FUEN_FECHA | str | fecha | 264 | 0.0 |
| INVE_FECHA | int64 | discreta | 5 | 0.0 |
| NOM_CUEN | str | alta cardinalidad | 55 | 0.0 |
| COD_CUEN | int64 | discreta | 55 | 0.0 |
| COD_SCUEN | int64 | discreta | 179 | 0.0 |
| COD_SSCUEN | int64 | discreta | 484 | 0.0 |
| MZON_GLAC | str | nominal | 4 | 0.0 |
| CH_CASQ | str | nominal | 6 | 97.2 |
| CUBIERTO | float64 | vacía | 0 | 100.0 |
| LATITUD | str | identificador | 26180 | 0.0 |
| LONGITUD | str | identificador | 26180 | 0.0 |
| PERIMETRO | float64 | continua | 6757 | 0.0 |
| ORIENTA | str | nominal | 9 | 0.0 |
| HMEDIA | float64 | continua | 25996 | 0.0 |
| HMAX | float64 | continua | 4441 | 0.0 |
| HMIN | float64 | continua | 4492 | 0.0 |
| PENDIENTE | float64 | continua | 16897 | 0.0 |
| ESP_MED | float64 | continua | 14779 | 0.0 |
| F_ESP_MED | str | nominal | 1 | 0.0 |
| VOL_km3 | float64 | continua | 3441 | 0.0 |
| EQ_AGUAKM3 | float64 | continua | 3262 | 0.0 |
| WGI_1 | int64 | discreta | 5 | 0.0 |
| WGI_2 | int64 | discreta | 10 | 0.0 |
| WGI_3 | int64 | discreta | 15 | 0.0 |
| FRENTE_TER | str | nominal | 3 | 0.0 |
| RESOL_IMG | float64 | continua | 14 | 0.0 |
| ERROR | float64 | continua | 7378 | 0.0 |
| OBSERVACIO | float64 | vacía | 0 | 100.0 |
| CUT_REG | int64 | discreta | 16 | 0.0 |
| CUT_PROV | int64 | discreta | 40 | 0.0 |
| CUT_COM | int64 | discreta | 84 | 0.0 |

## Requisitos del curso

| estado | requisito | detalle |
| --- | --- | --- |
| OK | Al menos 2000 filas | 26180 filas |
| OK | Al menos 12 columnas | 45 columnas |
| OK | Combina al menos 3 roles analíticos | continua, discreta, nominal, alta cardinalidad, fecha |
| OK | Al menos una variable numérica | 23 numéricas (continuas o discretas) |
| OK | Al menos una variable categórica | 8 categóricas (nominales, binarias u ordinales) |
| OK | Presencia de valores faltantes | máximo 100.0% en una variable |
| AVISO | Ninguna variable sobre 60% de faltantes | máximo 100.0% |
| OK | Incluye alguna variable de fecha | 1 detectadas |
| OK | Incluye texto o categórica de alta cardinalidad | 6 detectadas |
| OK | Archivo bajo 100 MB | 9.5 MB |
| OK | Sin filas duplicadas exactas | ninguna |

## Resultado

El conjunto **cumple** los requisitos mínimos.