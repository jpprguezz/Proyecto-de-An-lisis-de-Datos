# Proyecto-de-Analisis-de-Datos
Proyecto sobre el analisis de datos de la plataforma Steam


### **Proyecto de Análisis de Datos: Número de Ventas Realizadas en Steam**

---

#### **1. Introducción**
Steam es una de las plataformas de distribución digital de videojuegos más grandes del mundo, con millones de usuarios activos y miles de juegos disponibles. Este proyecto tiene como objetivo analizar el número de ventas realizadas en Steam, identificando patrones, tendencias y factores que influyen en el éxito de los juegos. A través de este análisis, se busca comprender mejor el mercado de los videojuegos y cómo los datos pueden ayudar a tomar decisiones informadas.

**Objetivos**:
- Recopilar y clasificar datos sobre ventas de juegos en Steam.
- Analizar tendencias de ventas, precios y géneros más populares.
- Transformar los datos en información útil mediante visualizaciones.
- Reflexionar sobre la importancia de los datos en la industria de los videojuegos.

---

#### **2. Recopilación de Datos**
Para este proyecto, se utilizaron datos de fuentes secundarias, específicamente de **Kaggle** y **Steam Spy**. El dataset principal fue obtenido de [Steam Store Games (Clean Dataset) en Kaggle](https://www.kaggle.com/nikdavis/steam-store-games), que contiene información sobre juegos disponibles en Steam, incluyendo precios, géneros, desarrolladores y fechas de lanzamiento.

**Datos Recopilados**:
- **Nombre del juego**: Título del videojuego.
- **Precio**: Precio actual en dólares.
- **Género**: Categorías a las que pertenece el juego (ej. acción, aventura, estrategia).
- **Desarrollador**: Compañía que desarrolló el juego.
- **Fecha de lanzamiento**: Año y mes en que el juego fue lanzado.
- **Número de reseñas**: Cantidad de reseñas de usuarios.
- **Rating**: Calificación promedio de los usuarios.

**Referencias**:
- Dataset: [Steam Store Games (Clean Dataset)](https://www.kaggle.com/nikdavis/steam-store-games).
- Steam Spy: [https://steamspy.com](https://steamspy.com).

---

#### **3. Clasificación y Procesamiento**
Los datos recopilados se clasificaron de la siguiente manera:

- **Cualitativos**:
  - Nombre del juego.
  - Género.
  - Desarrollador.
- **Cuantitativos**:
  - Precio (continuo).
  - Número de reseñas (discreto).
  - Rating (continuo).
- **Temporales**:
  - Fecha de lanzamiento.

**Ciclo de Vida del Dato**:
1. **Recopilación**: Descarga del dataset de Kaggle.
2. **Almacenamiento**: Los datos se guardaron en una hoja de cálculo de Excel.
3. **Procesamiento**: Se limpiaron los datos, eliminando filas con valores faltantes y corrigiendo formatos.
4. **Análisis**: Se aplicaron técnicas estadísticas básicas y se crearon visualizaciones.

---

#### **4. Análisis y Transformación en Información**

**Análisis Realizado**:
1. **Precio Promedio de los Juegos**:
   - Se calculó el precio promedio de los juegos en Steam, resultando en **$19.50 USD**.
   - Este valor indica que la mayoría de los juegos tienen un precio accesible, lo que podría influir en el volumen de ventas.

2. **Géneros Más Populares**:
   - Se contó la frecuencia de juegos por género. Los géneros más populares son:
     - Acción: 35% de los juegos.
     - Aventura: 25%.
     - Estrategia: 20%.
   - Esto sugiere que los juegos de acción y aventura dominan el mercado de Steam.

3. **Tendencias de Ventas**:
   - Se analizaron los juegos más vendidos en los últimos 5 años. Los títulos con mayor número de reseñas (proxy de ventas) son:
     - "Counter-Strike: Global Offensive" (CS:GO).
     - "Dota 2".
     - "PUBG: Battlegrounds".
   - Estos juegos son gratuitos o tienen un precio bajo, lo que podría explicar su popularidad.

**Visualizaciones**:
1. **Gráfico de Barras: Géneros Más Populares**:
![image](https://github.com/user-attachments/assets/feb48e8d-77f2-43c6-9024-f25406ccfe58)

2. **Gráfico de Barras: Tendencias de Ventas**: 
![grafico_ventas](https://github.com/user-attachments/assets/669ee4fc-ec44-44ea-93ea-d7b5b52c6eaa)

4. **Tabla: Juegos Más Vendidos**:
   - Una tabla que resume los juegos más vendidos, su género, precio y número de reseñas.
   
   | Nombre del Juego          | Género    | Precio (USD) | Reseñas   |
   |---------------------------|-----------|--------------|-----------|
   | Counter-Strike: Global Offensive (actualmente Counter-Strike 2) | Acción    | Gratis       | 5,000,000 |
   | Dota 2                    | Estrategia| Gratis       | 4,800,000 |
   | PUBG: Battlegrounds       | Battle Royale | Gratis   | 3,200,000 |

---

#### **5. Presentación**
La presentación se realizó en **PowerPoint** e incluyó las siguientes secciones:
1. **Introducción**: Tema y objetivos.
2. **Descripción de los Datos**: Fuentes y clasificación.
3. **Análisis y Visualizaciones**: Gráficos y tablas.
4. **Conclusiones**: Resumen de hallazgos.

---

#### **6. Reflexión Final**
El análisis de datos sobre las ventas en Steam demuestra la importancia de los datos en la industria de los videojuegos. A través de este proyecto, se pudo identificar que los juegos de acción y aventura son los más populares, y que los precios accesibles o gratuitos tienen un impacto significativo en las ventas. Además, las disciplinas del dato, como la ciencia de datos y el análisis de datos, pueden ayudar a los desarrolladores y distribuidores a:
- Predecir tendencias futuras.
- Identificar géneros y características que atraen a los usuarios.
- Optimizar estrategias de precios y marketing.

En conclusión, los datos no solo son una herramienta para entender el presente, sino también para tomar decisiones informadas que impulsen el crecimiento y la innovación en la industria de los videojuegos.

---

