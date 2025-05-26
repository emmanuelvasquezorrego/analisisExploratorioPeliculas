
# 🎬 Análisis de Datos de Películas

Este proyecto realiza un análisis exploratorio del dataset `movie_metadata.csv`, que contiene información sobre diversas películas, incluyendo su duración, presupuesto, año de estreno, director, entre otros.

El objetivo es limpiar los datos, identificar valores atípicos, explorar relaciones entre variables y responder preguntas clave mediante estadísticas y visualizaciones.

---

## 📊 ¿Qué se hizo?

### Paso 1: Carga y exploración inicial
- Visualización de las primeras filas del dataset.
- Revisión de tipos de datos y estadísticas generales.

### Paso 2: Limpieza de datos
- Tratamiento de valores faltantes (NaN) en columnas como `duration`.
- Reemplazo de esos valores faltantes por su mediana, para no afectar el análisis.
- Cálculo de estadísticas como mediana y promedio.

### Paso 3: Análisis específicos
- Filtros por año y duración para contar películas.
- Análisis de la mediana del presupuesto.

### Paso 4: Retos
- Relación entre duración y presupuesto (gráfico de dispersión).
- Conteo de directores con más películas.
- Detección de valores atípicos en la duración de películas.


---

## 🧰 Librerías utilizadas

- `pandas` → para manipulación y análisis de datos.
- `matplotlib.pyplot` → para graficar datos.
- `matplotlib.ticker` → para formatear escalas de ejes.

---

## 🚀 Cómo ejecutar

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/nombre-del-repositorio.git
   cd nombre-del-repositorio
   ```

2. Instala las dependencias necesarias:
   ```bash
   pip install pandas matplotlib
   ```

3. Ejecuta el análisis en Google Colab o en Jupyter Notebook abriendo el archivo `.ipynb`.

---

## 🧠 Conclusión general

Este proyecto demuestra cómo el análisis exploratorio de datos (EDA) puede revelar patrones, inconsistencias y conocimientos valiosos en conjuntos de datos reales. A partir de información aparentemente simple como duración, año de estreno y presupuesto, es posible detectar tendencias, valores atípicos y relaciones (o la ausencia de ellas) que pueden ser de gran utilidad para la industria del cine, la investigación académica o simplemente para tomar decisiones más informadas.

Más allá de los números, este tipo de análisis permite desarrollar un pensamiento crítico, habilidades técnicas y capacidad para comunicar hallazgos de manera clara, lo cual es esencial en el mundo del análisis de datos y la ciencia de datos. Además, trabajar con datos reales refuerza la importancia de una limpieza cuidadosa y una interpretación consciente, ya que los errores o inconsistencias pueden llevar a conclusiones erróneas.

---

## 📄 Licencia

Este proyecto es de uso libre con fines educativos. Puedes modificarlo y compartirlo dando el crédito correspondiente.

---

## ✒️ Autor

**emmanuelvasquezorrego**
