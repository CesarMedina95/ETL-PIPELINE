# ETL-PIPELINE
Este es un proyecto donde construyo un Pipeline desde 0

futbol-etl-pipeline/
│
├── dags/                    # DAGs de Airflow
│   └── etl_pipeline.py
│
├── data/                    # Datos crudos (input)
│   └── partidos.csv
│
├── scripts/                 # Lógica de ETL
│   ├── extract.py
│   ├── transform.py
│   └── load.py
│
├── database/                # Salida del pipeline
│   └── futbol.db
│
├── tests/                   # (opcional) Pruebas unitarias
│   └── test_transform.py
│
├── requirements.txt         # Dependencias
├── README.md                # Explicación del proyecto
├── .gitignore               # Archivos a ignorar
└── LICENSE                  # Licencia del proyecto


