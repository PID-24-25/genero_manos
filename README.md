# Clasificación de Género a partir de Imágenes de Manos

Este repositorio contiene el desarrollo completo del proyecto de clasificación de género utilizando imágenes del conjunto de datos **11k Hands**. El trabajo se basa en técnicas de preprocesamiento combinadas con redes neuronales convolucionales, siguiendo como referencia un artículo científico y explorando variantes propias para mejorar la generalización del modelo.

## 📁 Estructura del repositorio

- `dataset/`: contiene las imágenes organizadas en carpetas `train`, `val` y `test`. El dataset usado es **11k Hands**.
- `models/`: incluye todos los cuadernos Jupyter correspondientes a cada modelo entrenado. Puedes ejecutar estos notebooks para replicar los resultados o experimentar con nuevas configuraciones.
- `notebooks/`: contiene cuadernos usados para experimentar con los distintos métodos de preprocesamiento (GaussianBlur, Sobel, Laplacian, etc.) y para automatizar la división del dataset original.

### 🛠️ Pasos para trabajar sobre el proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/PID-24-25/genero_manos.git
cd genero_manos
```

2. Crear un entorno virtual con Python 3.10:
Si no tienes Python 3.10 instalado, puedes hacerlo desde la página oficial de Python o, en sistemas basados en Debian/Ubuntu, mediante:
```bash
sudo apt update
sudo apt install python3.10 python3.10-venv
```
Luego, crea y activa el entorno virtual:
```bash
python3.10 -m venv venv
source venv/bin/activate
```

3. Instalar las dependencias necesarias:
```bash
pip install -r requirements.txt
```

## 📄 Licencia

Este proyecto ha sido desarrollado como parte de una práctica académica y se encuentra bajo una licencia educativa. Los modelos, resultados y código fuente han sido implementados con fines de aprendizaje.

Se ha tomado como referencia el artículo científico:

> **Jamshidi, K., Toosi, R., & Akhaee, M. A. (2024). Gender Recognition Based on Hand Images Employing Local and Global Shape Information. IEEE Computer.**

Este artículo fue utilizado como base teórica e inspiración para el diseño de los modelos y experimentos, pero no se ha reutilizado directamente ningún fragmento de código del mismo.
