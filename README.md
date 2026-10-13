ai-stock-trading/
│
├── backend/
│   │
│   ├── app/
│   │   ├── __init__.py
│   │   ├── main.py
│   │   │
│   │   ├── core/
│   │   │   ├── __init__.py
│   │   │   └── config.py
│   │   │
│   │   ├── models/
│   │   │   ├── __init__.py
│   │   │   └── schemas.py
│   │   │
│   │   ├── api/
│   │   │   ├── __init__.py
│   │   │   ├── analysis_routes.py
│   │   │   ├── chat_routes.py
│   │   │   └── file_routes.py
│   │   │
│   │   ├── services/
│   │   │   ├── __init__.py
│   │   │   ├── csv_file_service.py
│   │   │   ├── market_data_service.py
│   │   │   ├── news_service.py
│   │   │   └── chat_service.py
│   │   │
│   │   ├── crew/
│   │   │   ├── __init__.py
│   │   │   ├── trading_crew.py
│   │   │   ├── agents.py
│   │   │   └── tasks.py
│   │   │
│   │   └── utils/
│   │       ├── __init__.py
│   │       └── indicators.py
│   │
│   ├── requirements.txt
│   ├── .env
│   ├── .env.example
│   └── run.py
│
└── frontend/
