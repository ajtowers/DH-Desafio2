# DH-Desafio 2

**Actualización:  22/9**

- *properatti_geo.csv_V2* no tiene la columna de habitaciones_final, con lo cual volví a poner en el repositorio el *properatti_geo.csv*  

En el notebook **palermos**:
- Filtrado por barrio de Palermo y eliminadas columnas sin uso o redundantes.  
- Cambie nombre de columnas 'habitaciones_final' por 'ambientes' y 'total' por 'superficie' para hacerlo más claro.  
- Agregado de columna *antiguedad* con 3 valores: *'nuevo', 'usado'* y *'pozo'* para corregir el dataset original.  
- Eliminados los registros sin *ambientes*  
- Guardado nuevo dataframe en *palermo.csv*  

**Para pensar:** 

- corr(ambientes, superfie) = 0.78  Evaluar si dejamos *ambientes* como variable o nos quedamos solo con *superficie* (~300 datapoints mas)


**Pendientes:**

- Armar dataset con sub-barrios de Palermo
- Modelos

