# DH-Desafio 2

**Actualización:  23/9**

- *properatti_geo.csv_V2* no tiene la columna de habitaciones_final, con lo cual volví a poner en el repositorio el *properatti_geo.csv*  

En el notebook **Palermos_1**:

- Lee *properatti_geo.csv*
- Filtrado por barrio de Palermo y eliminadas columnas sin uso o redundantes.  
- Cambie nombre de columnas 'habitaciones_final' por 'ambientes' y 'total' por 'superficie' para hacerlo más claro.  
- Agregado de columna *antiguedad* con 3 valores: *'nuevo', 'usado'* y *'pozo'* para corregir el dataset original.  
- Eliminados los registros sin *ambientes*  
- Guardado nuevo dataframe en *palermo_deptos.csv*  

En el notebook **Palermos_map**:

- Cree el shapefile *palermos_map.zip* que tiene los sub-barrios que componen Palermo
- Devuelve el archivo *palermos_map.csv* con las coordenadas de cada sub-barrio

En el notebook **Palermos_2**:

- Lee *palermo_deptos.csv* y *palermos_map.csv*
- Hace ´sjoin´ para ubicar los deptos en los barrios que componen Palermo.
- Devuelve *palermo_deptos_final.csv* con la nueva columna con el barrio
 
En el notebook **LinearRegression, LassoRegression, RidgeRegression**:

- Tomo el csv, y se subsetea sacando algunas columnas sin uso.
- Se discretiza *antiguedad* y *barrio*
- Se corren varios modelos de LinearRegression, LassoRegression y RidgeRegression

- Los resultados no llegan a un R2=0.5 como en el notebook de Juan.

En el notebook **Model_JM**
- Los resultados son mejores.


**Pendientes:**

- Definir que modelos presentamos. 
- Powerpoint

