# Sistema de Deteccion bajo tierra

# Informacion 
El siguiente sistema de deteccion esta hecho para ser usado como software de deteccion de metales, gases y con la finalidad de separar las capas de terreno en subsuelo para el beneficio de la mineria u extraccion de petroleo como tambien en la geolocalizacion.
Esta aplicacion debe ser util para el perfil geofisico en estos procesos de alta demanda y se debe considerar la optimizacion como tambien la prediccion en excavaciones de fines industriales

Este sistema esta denominado como Sistema de Perforación Inteligente Guiada (SPIG), en la elaboracion de la idea se propone el uso de chips de deteccion por

- Ultrasonido (US)
- Radiofrecuencia (RF)
- Ondas Electromagneticas (GPR)

# Metricas establecidas
|Señal|Deteccion|Localizacion|Operacion|
|---|---|---|---|
|SNR|Anomaly Score|Error Vertical|Repetibilidad|
|Amplitud|Confianza|Error Radial/Direccional|Tiempo Por Estacion|
|Fase RF|Sensibilidad||Energia/Consumo|
|Frecuencia/Espectro|Tasa Falsos-Positivos||Almacenamiento Por Estacion|
|Energia|Persistencia Espacial||
|ToF|||
|Atenuacion|||
|Frecuencia Dominante|||
|Doppler|||
|Estabilidad De Estimacion|||

Conceptualmente y para beneficio del proyecto

                Adquisicion de datos
                        |
                        |
                   Procesamiento
                        |
                        |
                  Almacenamiento
                        |
                        |
                   Verificacion            Tiempo estimado por estacion: <=120seg
# Adiciones

Simbologia:
:white_check_mark: Aceptado
:grey_exclamation: En cuestionamiento
:white_circle: Pospuesto
:x: Rechazado

- :white_circle: Inclusion del metodo LIBS (Laser-Induced Breakdown Spectroscopy):
    Esta propuesta permanece como modalidad conceptual en vista de un uso activo en la identificacion de material extraido

# Metodos de ejecucion

El metodo operacional es

    Perforar Δz → detener completamente → estabilizar → medir → procesar → registrar con profundidad → volver a perforar → repetir

El metodo de medicion es:

    RF + US Pulse Echo + US Doppler




# Discusion