# cvv-encuestas-distribuidoras
Análisis de encuestas y datos de aplicación de distribuidoras de CRECE CON VALES: diagnóstico de datos, EDA, clustering y NLP para entender satisfacción, percepción y comportamiento.

## Estructura

```
data/
  raw/         archivo(s) fuente sin modificar (Excel original)
  processed/   datasets limpios generados por los notebooks
notebooks/
  01_diagnostico_datos.ipynb   Etapa 1: estructura, calidad y criterios de inclusión
requirements.txt
```

## Uso

```
pip install -r requirements.txt
jupyter lab
```

## Fuente de datos

`Encuesta de Experiencia Comercial DV_concentrado.xlsx` — encuesta telefónica a distribuidoras (P1–P5) más padrón de distribuidoras y datos de crédito/saldo, relacionados por `id_cliente`.
