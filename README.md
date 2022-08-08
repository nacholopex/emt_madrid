# EMT Madrid

Análisis histórico de la oferta de autobuses que la Empresa Municipal de Transportes de Madrid (EMT Madrid) ha puesto para disfrute de los usuarios en las diferentes franjas horarias establecidas durante los años 2019, 2020 y 2021.

# HISTORIA
Los datos han sido ofrecidos por la Empresa Municipal de Transportes de Madrid tras una solicitud al portal de transparencia. En un primer momento la EMT me denegó dicho conjunto de datos apoyándose en «tareas complejas» ya que dicen usar tecnologías offline y online.

Al no estar conforme con la resolución presente una reclamación al Consejo de Transparencia y Buen Gobierno, quien dictaminó que dichos datos debían serme cedidos. (RT 0919/2021)

Ha sido necesario la limpieza y elaboración nuevas columnas para poder realizar el estudio.

# CONTACTO
|🇪🇸 Español|🇬🇧 English|
|-|-|
|nacho.lopex2[arroba]gmail[punto]com|nacho.lopex2[at]gmail[dot]com|


# ARCHIVOS BRUTOS
https://anonfiles.com/Sb06Ja25yf/Coches_Cuadro_Oferta_Real_2020_zip

https://anonfiles.com/T201J42ay1/Coches_Cuadro_Oferta_Real_2021_zip

https://anonfiles.com/U202J627y7/Coches_Cuadro_Oferta_Real_2019_zip


# ESTRUCTURA DE LOS DATOS
| Nombre del campo | Descripción | Formato | 
| ---------------- | ----------- | ------- |
| CLinea           | Código interno de la línea     | Numérico |
| ELinea           | Etiqueta externa de la linea   | Alfanumérico |
| Denominación     | Denominación de la linea       | Alfanumérico |
| FServicio        | Fecha de servicio              | dd/mm/aaaa |
| IDFranja         | Identificación de la franja horaria {H00-H23 y M00-M10) (las franjas horarias identificadas por M00-M10, aunque corresponden al día siguiente, están asignadas a la fecha de servicio indicada)      | Alfanumérico |
| Intervalo        | Intervalo horario correspondiente a la identificación de franja horaria       | hhmmss - hhmmss |
| Coches            | Número de coches cuadro de la oferta real dotada al servicio       | Numérico |

