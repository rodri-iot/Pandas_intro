# Crear un entorno virtual `.venv`

Este documento muestra los comandos para crear y activar un entorno virtual de Python llamado `.venv` en Windows y Mac.

## Windows

### Usando PowerShell

1. Abre PowerShell.
2. Ejecuta:

```powershell
python -m venv .venv
```

3. Activa el entorno virtual:

```powershell
.venv\Scripts\Activate.ps1
```

> Nota: si PowerShell bloquea la ejecución por permisos, usa `Set-ExecutionPolicy -Scope CurrentUser RemoteSigned` como administrador o ejecuta PowerShell como administrador.

### Usando CMD

1. Abre el símbolo del sistema (CMD).
2. Ejecuta:

```cmd
py -m venv .venv
```

3. Activa el entorno virtual:

```cmd
.venv\Scripts\activate.bat
```

## Mac

### Usando Terminal

1. Abre la Terminal.
2. Ejecuta:

```bash
python3 -m venv .venv
```

3. Activa el entorno virtual:

```bash
source .venv/bin/activate
```

## Notas

- En Windows, si `python` no funciona, prueba `py`.
- En Mac, asegúrate de tener Python 3 instalado.
- Para desactivar el entorno virtual en cualquier plataforma, usa:

```bash
deactivate
```
