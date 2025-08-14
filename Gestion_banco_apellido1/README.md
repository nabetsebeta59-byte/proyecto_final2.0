Proyecto final

![alt text](image.png)

# gestion_banco_apellido

Paquete educativo para la gestión de clientes, cuentas de ahorros y transacciones bancarias usando **Programación Orientada a Objetos (POO) en Python**.

> 🔁 **Importante:** Reemplaza `apellido` por tu apellido real en el nombre del paquete, por ejemplo: `gestion_banco_nicolalde`.

---

## 📦 Instalación (desde PyPI)

```bash
pip install gestion_banco_apellido

#en la imagen se detalla la estructura de como esta hecha la estructura

Prepara los archivos del proyecto

Coloca tus módulos de Python dentro de gestion_banco_apellido/ (la carpeta del paquete).

Asegúrate de tener:

pyproject.toml con los metadatos.

README.md (este archivo).

LICENSE (opcional, recomienda MIT).

2) (Recomendado) Crea y activa un entorno virtual

Windows (PowerShell):

python -m venv .venv
.venv\Scripts\Activate.ps1


macOS / Linux:

python3 -m venv .venv
source .venv/bin/activate

3) Actualiza pip e instala herramientas
python -m pip install --upgrade pip
python -m pip install build twine

4) Construye el paquete

Desde la carpeta raíz del proyecto (donde está pyproject.toml):

python -m build


Esto genera la carpeta dist/ con dos archivos:

gestion_banco_apellido-<version>.tar.gz

gestion_banco_apellido-<version>-py3-none-any.whl

5) Verifica el paquete antes de subir
python -m twine check dist/*

6) (Opcional pero aconsejable) Publica primero en TestPyPI

Crea una cuenta en TestPyPI.

Sube:

python -m twine upload --repository testpypi dist/*


Cuando te pida credenciales:

username: __token__

password: tu token de TestPyPI (empieza con pypi- o pypi-AgEI...).

Prueba la instalación desde TestPyPI:

pip install -i https://test.pypi.org/simple/ gestion_banco_apellido==0.1.0
