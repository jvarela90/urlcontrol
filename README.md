# Security Fuzzing System

Sistema profesional de fuzzing web con alertas inteligentes y automatizaci�n.

## Instalaci�n R�pida

```bash
python scripts/install.py
```

## Uso

```bash
# Configurar sistema
python scripts/setup_environment.py

# Ejecutar escaneo
python -m core.fuzzing_engine --scan

# Iniciar dashboard
python -m web.app

# Iniciar API
python -m api.app
```

## Documentaci�n

Ver `docs/` para documentaci�n completa.
