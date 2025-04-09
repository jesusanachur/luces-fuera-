# 🧪 Suite de Pruebas

## 🔍 Tipos de Pruebas Implementadas

1 Se implementaron pruebas unitarias utilizando pytest para verificar el comportamiento de funciones individuales. Estas pruebas aseguran que cada componente funcione
2 Se realizaron pruebas de integración para validar la interacción entre diferentes módulos

# Clone repository
git clone <URL_DEL_REPOSITORIO>
cd project-directory

# Install dependencies
pip install -r requirements.txt

# Run all tests
pytest tests/

# Run with coverage report
pytest --cov=./ tests/

# Generate HTML coverage report
pytest --cov=./ --cov-report=html tests/

### 1. Pruebas Unitarias
![pytest](https://img.shields.io/badge/Pytest-0A9EDC?logo=pytest&logoColor=white)
Verificación del comportamiento individual de cada componente:
#Estructura del Directorio de Pruebas

tests/
├── unit/            # Pruebas unitarias
│   ├── test_posicion.py
│   └── test_tablero.py
├── integration/     # Pruebas de integración
│   └── test_tablero_integration.py
└── __init__.py
