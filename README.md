# PowerBI_EnergyInsights
Análisis de dispositivos de energía mediante visualizaciones interactivas en Power BI. Este proyecto explora la relación entre precio, eficiencia energética, durabilidad, y otros factores clave, ofreciendo insights valiosos para optimizar la selección de dispositivos.

# Proyecto: Análisis de Dispositivos de Energía
Descripción
Este proyecto se centra en el análisis de un conjunto de dispositivos relacionados con la eficiencia energética, su durabilidad, y su consumo de energía, entre otras características. Los dispositivos analizados incluyen cargadores, inversores solares, fuentes de alimentación y paneles solares. El análisis se presenta a través de una serie de gráficos que permiten observar tendencias y patrones en relación con los costos, la eficiencia energética, la durabilidad, la garantía, y el consumo de energía.

# Gráficos y Análisis
# 1. Costo Anual de Energía en Dólares por Eficiencia Energética (Gráfico de Dispersión)
Este gráfico muestra que a menor eficiencia energética, menor es el costo anual de energía. Se observa que los dispositivos con eficiencia baja (ENERGY STAR) tienen un costo anual de energía de 78 dólares, mientras que los dispositivos con eficiencia alta tienen un costo anual de 1200 dólares. La línea de tendencia ascendente indica que a medida que la eficiencia energética aumenta, el costo anual de energía también tiende a ser más alto, lo cual refleja una posible relación directa entre eficiencia energética y costo.

# 2. Durabilidad Estimada en Años por Precio del Dispositivo en Dólares (Gráfico de Barras)
Este gráfico muestra que no necesariamente a mayor precio, mayor es la durabilidad del dispositivo. Un dispositivo que cuesta 300 dólares tiene una durabilidad estimada de 25 años, mientras que otro de 120 dólares tiene 10 años de durabilidad. Esto evidencia que el precio no siempre se correlaciona de manera directa con la durabilidad del dispositivo.

# 3. Clasificación de la Eficiencia (Gráfico de Columnas)
En este gráfico podemos observar que ENERGY STAR predomina dentro de las tres categorías de eficiencia energética. Existen dos dispositivos con eficiencia energética baja (ENERGY STAR), uno con eficiencia media (80 PLUS GOLD) y otro con eficiencia alta (80 PLUS PLATINUM). La categoría ENERGY STAR es la más representada.

# 4. Costo Anual de Energía en Dólares por Tipo de Dispositivo (Gráfico de Columnas)
Este gráfico muestra que el inversor solar y la fuente de alimentación son los dispositivos que tienen mayor costo anual de energía, mientras que el cargador tiene un costo significativamente menor. Además, el panel solar tiene un costo de energía anual de 0 dólares, ya que absorbe energía del sol para transformarla en electricidad, eliminando así el costo anual de energía.

# 5. Precio del Dispositivo en Dólares por Fabricante (Gráfico de Barras)
El análisis revela que Delta es el fabricante con el dispositivo más costoso. Le siguen SunPower, Corsair y, por último, Anker. Esto muestra la variabilidad en los precios de los dispositivos según el fabricante.

# 6. Eficiencia Energética por Año de Lanzamiento (Gráfico de Líneas)
Este gráfico muestra que el dispositivo con mayor eficiencia energética fue lanzado en 2019, pero para 2022 la eficiencia energética baja, reflejando una tendencia hacia una eficiencia media. Esto sugiere que, con el tiempo, los dispositivos lanzados al mercado han tenido una eficiencia energética más moderada en comparación con los primeros.

# 7. Eficiencia Energética por Ubicación Geográfica y Eficiencia Categórica (Gráfico de Columnas Agrupadas)
Aquí se muestra que a nivel global predominan las eficiencias energéticas alta y baja, mientras que en Estados Unidos solo predomina la eficiencia baja y media. Esto sugiere que a nivel mundial existen más dispositivos con alta eficiencia energética, mientras que en Estados Unidos los dispositivos con eficiencia baja y media son los más comunes.

# 8. Eficiencia Energética por Voltaje (Gráfico de Dispersión)
En este gráfico se observa que a mayor eficiencia energética, mayor es el voltaje, a excepción de un caso específico en el que un dispositivo de baja eficiencia energética tiene un voltaje muy similar al de un dispositivo de eficiencia media. La línea de tendencia ascendente refleja que los dispositivos de mayor eficiencia tienden a tener mayores valores de voltaje.

# 9. Consumo de Energía en Kilovatios por Hora por Tipo de Dispositivo (Gráfico Circular)
Este gráfico revela que el inversor solar y la fuente de alimentación son los dispositivos que consumen la mayor parte de la energía, con un consumo de 52.2% y 44.4%, respectivamente. El cargador representa un 3.4%, y el panel solar tiene un consumo de 0%. El consumo de energía del panel solar es 0% porque este dispositivo absorbe la energía del sol para producir electricidad, lo que elimina su consumo de energía.

# 10. Durabilidad Estimada en Años por Garantía en Años (Gráfico de Líneas)
Este gráfico muestra que a mayor durabilidad, mayor es la garantía, aunque existe un punto de quiebre. Los paneles solares tienen una durabilidad estimada de 25 años y una garantía de 25 años, lo que puede ser una práctica estándar en la industria. Sin embargo, algunos dispositivos con durabilidades más bajas no necesariamente ofrecen una garantía proporcionalmente mayor.

# Conclusiones
Eficiencia energética y costo: A mayor eficiencia energética, mayor es el costo anual de energía, lo que podría indicar que dispositivos más eficientes requieren una mayor inversión.
Durabilidad no siempre está relacionada con el precio: El precio de un dispositivo no necesariamente refleja su durabilidad estimada. Algunos dispositivos más baratos pueden tener una durabilidad similar o incluso mayor que dispositivos más caros.
Predominancia de ENERGY STAR: Dentro de las categorías de eficiencia, ENERGY STAR es la más común en el conjunto de datos, lo que sugiere que este tipo de dispositivos es más accesible o está más presente en el mercado.
Panel solar y consumo energético: Los paneles solares tienen un consumo de energía de 0% porque generan su propia energía a partir del sol, mientras que otros dispositivos como el inversor solar y la fuente de alimentación consumen grandes cantidades de energía.

# Recomendaciones
Continuar analizando cómo las diferentes categorías de eficiencia energética impactan en los costos a largo plazo y en la sostenibilidad de los dispositivos.
Explorar más a fondo las relaciones entre la garantía y la durabilidad para identificar patrones que puedan ayudar a predecir la calidad de los dispositivos.


## Cómo usar el Dashboard

1. Carga el archivo de **Power BI** para acceder al dashboard interactivo.
2. Cada gráfico interactúa con los demás. Por ejemplo, si seleccionas un dispositivo en el gráfico de **clasificación de eficiencia**, los demás gráficos se actualizarán para reflejar solo los datos relacionados con ese dispositivo.
3. Utiliza las segmentaciones para filtrar los datos según **fabricante**, **tipo de dispositivo** o **clasificación de eficiencia**.

## Tecnologías Utilizadas

- **Power BI** para visualización interactiva.
- **Python (Pandas y Matplotlib)** para preprocesamiento de datos y visualizaciones estáticas.
- **Excel** para la organización inicial de los datos.


¡Gracias por explorar este proyecto! Si tienes preguntas o comentarios, no dudes en contactarme.
