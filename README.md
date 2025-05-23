# Proyecto-IA-Grupo-2

**Caso de Estudio:** Transición Energética Justa en Zonas No Interconectadas de Colombia

1. **Descripción del problema**

    En Colombia existen numerosas zonas no interconectadas (ZNI), especialmente en departamentos como Amazonas y Chocó, donde el acceso a la energía eléctrica es limitado o de baja calidad. La base de datos analizada refleja esta problemática, mostrando que muchas localidades tienen promedios diarios de servicio eléctrico por debajo de las 10 horas, y algunas incluso menos de 4 horas al día.

    Esta situación afecta negativamente el desarrollo económico, el acceso a la educación, la salud y la calidad de vida en general, perpetuando condiciones de desigualdad.

2. **Interesados (Stakeholders)**

    - Comunidades rurales y étnicas en las ZNI, directamente afectadas.
    - Gobiernos locales y nacional, encargados de garantizar el acceso equitativo a servicios básicos.
    - Empresas energéticas e inversionistas en energías limpias.
    - Organizaciones sociales que promueven la equidad territorial.
    - Investigadores y académicos interesados en soluciones de desarrollo sostenible.

3. **Análisis del conjunto de datos**

    El conjunto contiene variables como:

    - Energía activa/reactiva consumida.
    - Potencia máxima demandada.
    - Promedio diario de horas con servicio eléctrico.
    - Información geográfica por departamento, municipio y localidad.

    La variable más crítica es el promedio diario en horas de energía, que permite detectar niveles de exclusión energética.

4. **Propuesta de solución con Machine Learning**

    Para abordar el problema de acceso desigual a la energía en zonas no interconectadas, proponemos utilizar un modelo de aprendizaje supervisado basado en regresión. Este modelo permite predecir el número promedio de horas de servicio eléctrico en una localidad en función de variables técnicas y geográficas disponibles en el conjunto de datos.

    ¿Por qué regresión?
    Porque nuestro objetivo es estimar una variable continua (número de horas de energía al día), no clasificar ni agrupar en categorías discretas.

    **Aplicación:**

    - Entrenar el modelo con datos históricos.
    - Predecir el acceso energético en localidades que aún no han sido priorizadas.
    - Simular mejoras al modificar variables como la potencia instalada.

5. **Visualizaciones recomendadas**

    - Mapa de calor de Colombia por departamento con el promedio de horas de servicio diario.
    - Gráfico de barras comparando el acceso promedio diario en diferentes municipios.
    - Clusters de zonas críticas con acceso deficiente (si se desea extender a clustering).

6. **Conclusión**

    Este análisis puede contribuir a una política pública más eficaz, orientada a cerrar la brecha energética. Aplicar machine learning en este contexto no solo permite priorizar recursos, sino también anticipar necesidades futuras.
