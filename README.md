# Challenge Telecom X Parte 2
#### **DESCRIPCIÓN DEL PROYECTO**
La empresa de telecomunicaciones Telecom X enfrenta una alta tasa de cancelación de clientes, y necesita comprender los factores que llevan a esto.

El objetivo es identificar que factores impulsan la cancelación y anticipar este comportamiento a través de modelos predictivos.
<br/><br/>
#### **ESTRUCTURA DEL PROYECTO**
+ Extracción y Preparación de datos
+ Análisis y Selección de variables
+ Modelamiento Predictivo
+ Evaluación de Modelos
+ Interpretación de resultados
+ Conclusiones<br/><br/>

#### **ORGANIZACIÓN DEL REPOSITORIO**
En la raíz se encuentran los siguientes archivos:
+ **README:** contiene un resumen del proyecto
+ **TelecomX_2:** contiene el código del proyecto
+ **TelecomX_Data_Depurada:** contiene la base de datos del proyecto

Las siguientes carpetas:
+ **img:** contiene imágenes con los análisis realizados en el proyecto<br/><br/>

#### INSTRUCCIONES DE EJECUCIÓN
El proyecto fue desarrollado en *Python* para ejecutarse en un entorno de *Google Colab*. El código está dividido en secciones que a su vez se dividen en bloques que siguen un orden secuencial de ejecución.<br/><br/>
**Tecnologías utilizadas**<br/><br/>
![python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)&nbsp;
![colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=flat&logo=google-colab&logoColor=white)&nbsp;
![github](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

**Bibliotecas utilizadas**<br/><br/>
![python](https://img.shields.io/badge/Python-3.11-blue)&nbsp;
![pandas](https://img.shields.io/badge/Pandas-2.2-blue)&nbsp;
![numpy](https://img.shields.io/badge/Numpy-2.0-blue)&nbsp;
![scikit-learn](https://img.shields.io/badge/Imblearn-0.13-blue)&nbsp;
![scikit-learn](https://img.shields.io/badge/Matplotlib-3.10-blue)&nbsp;
![scikit-learn](https://img.shields.io/badge/Seaborn-0.13-blue)&nbsp;
<br/><br/>
#### EJEMPLO DE INSIGHT (TODO)
Participación de variable objetivo (Churn): 26% fuga, 74% permanece.
<br/>
```python
plt.figure(figsize=(4, 3))
plt.pie(df['Churn'].value_counts(), labels=['No','Si'], autopct='%1.0f%%', startangle=90)
plt.title('Participacion de Churn', fontsize=14)
plt.show()
```
<img alt='Participacion de churn' src='img/participacion_churn.png' style='width: 300px; height: 315px;' />
<br/>

> [!NOTE]
> El informe final se encuentra dentro del archivo *ipynb*.
