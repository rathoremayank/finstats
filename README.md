# finstats


```
project-root/
├── backend/                  # FastAPI backend
│   ├── main.py               # API entrypoint
│   ├── auth.py               # JWT and password handling
│   ├── database.py           # SQLAlchemy DB connection
│   ├── models.py             # SQLAlchemy models
│   ├── schemas.py            # Pydantic schemas
│   ├── requirements.txt      # Python dependencies
│   └── __init__.py
│
└── frontend/                 # React + TailwindCSS frontend
    ├── public/
    ├── src/
    │   ├── api/
    │   │   └── axios.js       # Axios instance config
    │   ├── pages/
    │   │   ├── Login.jsx      # Login UI
    │   │   └── Register.jsx   # Signup UI
    │   ├── App.jsx            # App routes
    │   ├── index.css          # TailwindCSS entry
    │   └── main.jsx           # React DOM entrypoint
    ├── tailwind.config.js     # Tailwind config
    ├── postcss.config.js      # Tailwind PostCSS config
    ├── package.json           # React project config
    └── vite.config.js         # (if using Vite instead of CRA)
```
