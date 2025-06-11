# 📉 TelecomX - Análisis de Evasión de Clientes (Churn)

Este proyecto forma parte de un desafío de análisis de datos para la empresa ficticia **Telecom X**, con el objetivo de comprender los factores que contribuyen a la evasión de clientes (Churn).

Se trabajó con un conjunto de datos en formato JSON, utilizando Python en Google Colab, para realizar limpieza, exploración y visualización de datos, así como un análisis detallado de correlaciones que pueden ser utilizados como base para modelos predictivos.

---

## 🧰 Tecnologías y dependencias utilizadas

Este proyecto se desarrolló en Python 3 con las siguientes bibliotecas:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `json`

Puedes instalar las dependencias ejecutando:

```bash
pip install pandas numpy matplotlib seaborn


¿Cómo ejecutar el proyecto?
Abre el archivo del notebook en Google Colab o Jupyter Notebook:

TelecomX_Churn_Analysis.ipynb

Carga el archivo de datos JSON en tu entorno Colab:

Nombre del archivo: TelecomX_Data.json

Ejecuta el notebook celda por celda. Se recomienda seguir este orden:

Carga de datos

Limpieza y transformación

Análisis exploratorio de datos

Visualización y correlación

Informe final

🧪 Funcionalidades del proyecto
Carga y normalización de datos JSON estructurados

Limpieza de columnas, tratamiento de datos faltantes

Generación de nuevas variables como Cuentas_Diarias y Total_Servicios

Visualización de churn por variables categóricas y numéricas

Análisis estadístico y gráfico de correlación

Informe automatizado en Markdown dentro del mismo notebook

⚠️ Posibles problemas y soluciones
Problema	Solución sugerida
KeyError: 'Churn' o columnas no encontradas	Verifica el nombre real de la columna tras limpiar o hacer dummies
Gráficos no se muestran en Colab	Asegúrate de tener %matplotlib inline y usar plt.show()
Error al leer el JSON	Verifica que el archivo esté en /content/ en Colab o use rutas correctas
Correlaciones vacías	Asegúrate de tener solo variables numéricas al usar .corr()

📚 Créditos
Este proyecto fue desarrollado por [Tu Nombre Aquí] como parte del challenge de análisis de datos de Telecom X.

📌 Contacto
¿Tienes dudas o sugerencias? Puedes escribirme a través de https://www.linkedin.com/in/cesarconstantino/.


---



