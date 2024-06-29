# a. Solución de Machine Learning:

La solución se realizará en dos etapas, las cuales se corresponden con un análisis descriptivo, predictivo y prescriptivo para la generación de valor.

Primero se realizará una *Clustering* debido a que la planta de abonados de la empresa operadora *XYZ* es variada, y la reducción de las ventas puede ser por algún grupo en particular. Es posible considerar tipos de abondos como: (i) aquellos que nunca renuevan los equipos, (ii) aquellos que renuevan cada año, (iii) aquellos que compran equipos caros y recientes, (iv) aquellos que solo les interesa funcionalidades básicas, entre otros. Así pues, será de interés hacer una segmentación de la planta de abonados.

Una vez que se tiene la segmentación (que tiene un objetivo más descriptiva), se aplicará una “Regression” con miras a predecir la tendencia que se espera sobre la línea base. Asimismo, una herramienta de regresión será de utilidad para encontrar una asociación significativa entre alguna de las palancas disponibles y el segmento de usuarios que sea de relevancia para la empresa operadora *XYZ*. Luego, con la línea base y una estimación del impacto de la palanca relevante, se tomará acción. Ello se corresponde con un análisis prescriptivo y de toma de decisión para resolver la problemática.

# b. What? So What? Now What?

  *¿Qué?: Entendiendo el negocio
    Dada la problemática, esta se mide por cantidad de equipos vendidos por mes. Es un enfoque directo del problema pero se podría mejorar si se evalua la cantidad de equipos vendidos mensual por segmentos de clientes. Actualmente, para aumentar las ventas de equipos móviles, se hacen campañas de marketing y descuentos ocasionales. Sin embargo, se sigue observando una disminución en la venta de equipos, presumiblemente por los distintos miembros de la competencia que realiza estrategias de venta similares. Esta disminución afecta los ingresos de la empresa de manera significativa. 

  *¿Entonces qué?: La esencia de la creación de valor en Ciencia Datos
    Con la solución de Machine Learning planteada, se usará la información sobre segmentos de clientes para mejorar las estrategias de marketing, pudiendo enfocarse estas en las necesidades de cada segmento. Otra palanca diferente del marketing que se puede utilizar es la atención al cliente, ya que la satisfacción del cliente con la atención brindada puede determinar si este volverá a comprar su equipo con la empresa o si recomendará la empresa a sus conocidos. Por esto también se medirá la tasa de satisfacción de los clientes, y dependiendo de los resultados se pueden sugerir capacitaciones para mejorar el servicio al cliente. Finalmente se analizará la eficacia de las ventas en linea de la empresa, para saber si es necesario realizar mejorar la página web de compra de equipos. 

  *¿Ahora qué?: Ser un proactivo
    Despué de obtener los resultados del análisis de Machine Learning planteado en la solución, se realizarán las siguientes acciones:
    *Se comunicará con el área de marketing para que con la información brindada sobre segmentos de clientes puedan elaborar campañas focalizadas.
    *Se comunicará con el área de finanzas para planear una estrategia de descuentos, planteando los beneficios y costos de la evaluación de la estrategia escogida.
    *Se comunicará con el área de recursos humanos para que puedan planear las capacitaciones necesarias para mejorar la atención al cliente.


# c. Métrica adecuada:


# d. Valor monetario incremental:

Si bien los ingresos se han reducido cada año, el ingreso promedio por celular vendido ha crecido en el tiempo. En ese sentido, las acciones de corto que tome la administración de la empresa operadora *XYZ* deben enfocarse en aumentar la venta de equipos celulares.

Para ello, en la siguiente tabla se describen los conceptos necesarios a efectos de poder calcular el impacto monetario de la acción llevada a cabo.

| CONCEPTO | VALOR | UNIDAD |
| --------- | --------- | --------- |
| Ingreso por venta de equipo | 654.80 | S/ |
| Tendencia en venta de equipos | -19.1% | Porcentaje |
| Modelo ML - reduce la tendencia a la mitad | -9.5% | Porcentaje |
| Modelo ML - reduce la tendencia a 8% | -8% | Porcentaje |

En primer lugar, se asume que el ingreso promedio por venta de equipos es de S/ 654.80 y que para el próximo año la tendencia en la venta de equipos seguirá la misma tasa de decrecimiento promedio de los últimos 6 años (-19.1%). Sin embargo, mediante el Modelo ML se ha podido comprobar que una campaña de descuento en equipos celulares no detendrá pero sí reducirá la tendencia de las ventas en la mitad (-9.5%). Finalmente, se asume que la *Regression* tiene espacio a ser mejorada, tal que hubiera reducido el decrecimiento en ventas ya no a -9.5% sino a -8%.

Con dicha información es posible calcular el valor monetario incremental de haber realizado el proyecto de ML y aplicado la campaña de descuento en equipos, así como estimar el costo de los falsos positivos y de falsos negativos. 

| CONCEPTO | VALOR EN S/ |
| --------- | --------- |
| Ingresos sin modelo | 652,429,176 |
| Ingresos con modelo | 729,382,529 |
| Ahorro del nuevo modelo | 76,953,353 |
| Costo de falsos positivos | -16,126,718 |
| Costo de falsos negativos | -12,446,483 |

PENDIENTE EXPLICACIÓN...............