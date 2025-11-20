# Qiskit Hackathon

## Instalacion Requerimientos

### Clonacion de repositorio

```bash
git clone https://github.com/TrodriTen/Qiskit_Hackathon.git
```

### Instalacion version python (Windows)

- Para este se aconseja usar el **python install manager** el cual lo pueden descargar desde la microsoft store.

```shell
py list # ver versiones de python instaladas en tu sistema
py list online # ver las versiones de python disponibles a descargar
```
- Para esto se aconseja usar python 3.11

```shell
py install 3.11
```

- Despues se debe crear un virtual enviroment

```shell
py -3.11 -m venv .venv
```

- Finalmente, activar el virtual enviroment

```shell
. \.venv\Scripts\Activate.ps1
```

### Instalacion de librerias

- Actualizamos el manejador de paquetes pip

```shell
python -m pip install --upgrade pip
```

- Instalamos librerias

```shell
pip install -r .\requirements.txt
```