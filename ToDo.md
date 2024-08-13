## Posibles Objetivos 

[] Segmentacion de clientes. (Probar temas de clustering u analisis de similaridad) 

Puede ser interesante ver como se comportan los distintos grupos o clusters para ver oportunidades de negocio. 

[] Analisis de morosidad (con la segmentacion previa).

Para identificar factores de riesgo y posibles areas de mejora en la concesion de credito. 

[] Evaluacion del impacto post-pandemia. (posible analisis de series temporales)

[] Ver cuales son las features mas determinantes para el score de riego, y ver como afecta. 

[] Analisis de relaciones en hogares. 

Estudiar cómo la composición familiar (household) afecta el comportamiento crediticio y la morosidad, y cómo las relaciones interpersonales influyen en la toma de decisiones financieras.


## Problemas:

DF PERSONAS: 

* flag_prestamos -> solo tiene 1s y Nan s (categorico)
    
Decido excluir la variable si no encuentro una solucion mediante clustering. 

* situacion laboral -> regresion logistica, clustering, desicion tree (categorico)

DF OPERACIONES: 

* saldo_ref -> series temporales, investigar mas al respecto.  (continuo)

* tipo_entidad -> otro enfoque ya que el DF no corresponde siempre a personas distintas (categorico)

DF HOUSEHOLD: 

..... 