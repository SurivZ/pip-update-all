# pip-update-all

[![License](https://img.shields.io/badge/license-BSD-blue.svg)](LICENSE)

`pip-update-all` es una herramienta sencilla para actualizar todos los paquetes instalados mediante `pip` en un solo comando.

## Características

- Actualiza automáticamente todos los paquetes instalados con `pip`.
- Opción de modo verboso para más detalles durante la ejecución.

## Instalación

Puedes instalar `pip-update-all` directamente desde PyPI:

```bash
pip install pip-update-all
```

O clonar el repositorio e instalarlo manualmente:

```bash
git clone https://github.com/SurivZ/pip-update-all.git
cd pip-update-all
pip install .
```

## Uso

### Comandos básicos

Para actualizar todos los paquetes instalados:

```bash
update
```
Para listar los paquetes instalados que estén desactualizados:

```bash
outdated
```

### Modo Verboso

Si deseas ver más información durante la ejecución:

```bash
update --verbose
```
También puedes usar su versión abreviada:
```bash
update -V
```

### Versión del programa

Para ver el número de versión:

```bash
update --version
```
Versión abreviada:
```bash
update -v
```

## Contribuir

Si deseas contribuir a este proyecto, sigue los siguientes pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama con un nombre descriptivo:
   ```bash
   git checkout -b feature/nueva-funcionalidad
   ```
3. Realiza tus cambios y haz commit:
   ```bash
   git commit -m "Descripción de los cambios"
   ```
4. Envía tus cambios a tu fork:
   ```bash
   git push origin feature/nueva-funcionalidad
   ```
5. Abre un Pull Request en GitHub.

Por favor, asegúrate de seguir las mejores prácticas de desarrollo y pruebas. Se agradecen mucho las contribuciones que incluyan documentación y pruebas automatizadas.

## Contacto

Si tienes preguntas o sugerencias, siéntete libre de abrir un **issue** o contactarme a través de [franklinserrano23@email.com](mailto:franklinserrano23@email.com).

---

**Licencia:** Este proyecto está licenciado bajo la licencia BSD.