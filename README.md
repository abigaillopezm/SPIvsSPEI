# Comparación entre el índice SPI y el SPI
En este repositorio se encuentra toda la documentación y trabajo técnico detrás del análisis comparativo entre dos índices de sequía.
-----

# Estructura del repositorio

| DIRECTORIO | DESCRIPCIÓN | SUB-DIRS
|------------| ------------| --------
|**00_SCRIPTS** | Contiene los códigos creados para el trabajo, en teoría todo se ejecuta desde acá (las rutas ya están específicadas) | *ninguno* 
| **01_DATA** | Contiene los datos originales e intermedios | **for_indices:** datos limpios y listos para proceder a la descarga de los datos <br> **raw:** archivos originales (sin modificar nada) <br> **SMN_limpios:** archivos intermedios de limpieza 
| **02_OUTPUTS** | CSV de salida con los índices calculados | **ven3:** indices calculados con ventana de 3 meses <br> **ven12:** índices calculados con ventana de 12 meses



-----
# Cambios importantes
*09/02/2025* - inicialización del proyecto y repositorio.
*14/02/2026* - Se hace el cálculo de los índices solo para dos estaciones (las que tienen la serie más completa). esto también con el fin de hacer más eficiente el análisis d elos resultados para la propuesta preliminar del proyecto.