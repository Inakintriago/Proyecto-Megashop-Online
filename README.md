# Megashop Online - Proyecto de A/B Testing

## 📊 Descripción del Proyecto

En este proyecto, trabajas como analista en una tienda online que ha recopilado una serie de hipótesis sobre cómo aumentar los ingresos. El objetivo es priorizar estas hipótesis, lanzar un test A/B y analizar los resultados para tomar decisiones informadas.

## 🎯 Objetivos

### Parte 1: Priorizar Hipótesis

1. **Framework ICE**:
   - Evaluación de las hipótesis utilizando los criterios de **Reach**, **Impact**, **Confidence** y **Effort**.
   - Cálculo de la puntuación **ICE** para cada hipótesis y ordenación en función de la prioridad.

2. **Framework RICE**:
   - Evaluación de las hipótesis utilizando los mismos criterios más el esfuerzo.
   - Cálculo de la puntuación **RICE** para cada hipótesis y ordenación en función de la prioridad.

3. Comparación de los resultados entre los marcos **ICE** y **RICE**.

### Parte 2: Análisis del Test A/B

1. **Gráfico de Ingreso Acumulado**: Visualización del ingreso acumulado por grupo.
2. **Gráfico de Tamaño Promedio de Pedido Acumulado**: Análisis de la evolución del tamaño promedio de los pedidos por grupo.
3. **Diferencia Relativa en el Tamaño de Pedido Promedio**: Visualización de la diferencia entre los grupos A y B.
4. **Tasa de Conversión**: Cálculo y visualización de la tasa de conversión diaria para cada grupo.
5. **Gráfico de Dispersión del Número de Pedidos por Usuario**: Análisis de la distribución de los pedidos por usuario.
6. **Percentiles de Pedidos por Usuario**: Identificación de anomalías en los pedidos.
7. **Gráfico de Dispersión de los Precios de los Pedidos**: Visualización de la distribución de los precios de los pedidos.
8. **Percentiles de Precios de los Pedidos**: Identificación de anomalías en los precios.
9. **Análisis de Significancia Estadística**: Comparación de las diferencias de conversión y tamaño de pedido entre los grupos A y B.

## 📈 Resultados y Decisiones

### Análisis de Conversión y Tamaño de Pedido

- **Tasa de Conversión**: El grupo B mostró una tasa de conversión superior (0.0310 frente a 0.0268), indicando que el grupo B tiene un rendimiento superior en términos de conversión.
  
- **Tamaño Promedio de Pedido**: No se observó una diferencia estadísticamente significativa en el tamaño promedio de pedido entre los grupos (valor p = 0.4041), lo que sugiere que las diferencias en la conversión no están impulsadas por el tamaño de los pedidos.

### 💡 Decisión

**Parar la prueba y considerar al grupo B como el líder**:  
Dado que el grupo B presenta una tasa de conversión significativamente superior y no hay cambios relevantes en el tamaño de los pedidos, la decisión es concluir la prueba y considerar a B como el grupo líder.

## 🏁 Conclusión

El análisis de la prueba A/B sugiere que el grupo B tiene un rendimiento superior en términos de conversión, lo que justifica tomarlo como el grupo líder, aunque no se hayan observado cambios significativos en el tamaño de los pedidos.
