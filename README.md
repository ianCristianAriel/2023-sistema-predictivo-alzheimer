## Estado del Proyecto
- **Finalizado**

## Estructura de Directorios y Archivos Resultantes


    Sistema Predictivo de Alzheimer
    │
    ├── data # CSV's
    │ ├── processed # Clean CSV's
    │ └── raw # Original CSV's
    │
    ├── notebooks # Notebook's and Script's
    │ └── models # .PKL of the best ML model
    |   |   └── best_model.pkl
    |   |
    │   |-- 1_etl.ipynb 
    |   |__ 2_eda_enrichment_pre_prosesing.ipynb
    |   |__ 3_data_viz.ipynb
    │
    ├── .gitignore
    │
    ├── REQUIREMENTS.txt
    |
    │-- LICENSE.md
    │
    └── README.md # This file


## Funciones y Aplicaciones
- ETL, EDA, Data Viz y ML
- Prediccion entre el 65% y 70% de fiabilidad de la enfermedad de Alzheimer
  - Datos de entrada: edad, nivel cognitivo y presencia de gen APOE4

### Explicacion
- [Reunion de explicacion, 31/10/23](https://drive.google.com/file/d/1dbK42t-68MLVNwFlm56UufAlBa1XRli4/view)

## Tecnologías Utilizadas
- Python
  - Numpy
  - Pandas
  - Seaborn
  - Matplotlib
  - Scikit-Learn


## Instalación de Paquetes
```bash
pip3 install -r requerimientos.txt
```

## Personas Desarrolladoras del Proyecto:

- [goncor](https://github.com/GonCor)
- [tomasescobar25](https://github.com/tomasescobar25)
- [agustinar](https://github.com/agustinarr)
- [IanCristianAriel](https://github.com/ianCristianAriel)
- [ClaudineMeyer](https://github.com/ClaudineMeyer)
- [Francisco-B07](https://github.com/Francisco-B07)
