# EMT Madrid
Análisis histórico de la oferta de autobuses que la Empresa Municipal de Transportes de Madrid (EMT Madrid) ha puesto para disfrute de los usuarios en las diferentes franjas horarias establecidas durante los años 2019, 2020 y 2021.


# HISTORIA
Los datos han sido ofrecidos por la Empresa Municipal de Transportes de Madrid tras una solicitud realizada mediante el portal de transparencia.

En un primer momento la EMT me denegó dicho conjunto de datos apoyándose en:
> _Sería necesario el desarrollo de programas y consultas informáticas específicas que, a partir de los datos básicos del servicio, realizaran el análisis, extracción, agregación, segmentación y conformación para obtener el informe solicitado._

> _Dado que la solicitud hace referencia a datos históricos, se debería examinar, seleccionar, extraer y procesar un volumen alto de información que se encuentran en distintos soportes físicos (online y offline). Con el empleo de un importante tiempo de proceso y recursos técnicos y humanos._

Tras esta resolución port parte de EMT (desestimatoria), presenté reclamación al Consejo de Transparencia y Buen Gobierno quien dictaminó que dichos datos debían ser cedidos al considerarlos de interés [RT 0919/2021](https://www.consejodetransparencia.es/ct_Home/dam/jcr:feb996d5-7f97-4233-9779-bed65d15e622/RT_0919_2021.pdf).


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


# METODOLOGÍA
Para la realización de un análisis objetivo de los datos, ha sido necesario cruzar la información suministrada por EMT Madrid con diferentes conjuntos de datos (calendario laboral, número de viajeros e incidencias).

Se ha usado el lenguaje de progrmación `Python` para realizar tareas de limpieza y concordancia de datos entre conjuntos.


# QUEJAS Y DEFENSAS
| TIPO | Política | MENSAJE | MÁS INFORMACIÓN | FECHA |
| ---- | -------- | ------- | --------------- | ----- |
| ANUNCIO | Partido Popular | Servicio gratutito día 3 de octubre de 2022 | [Twitter Presidente Ayto. Madrid](https://twitter.com/AlmeidaPP_/status/1575774047643779073) | 2022/09/30 |
| QUEJA| MÁSMADRID| Recortes en 16 líneas de EMT | [Twitter MásMadrid](https://twitter.com/MasMadrid__/status/1527248140444872705) - [LaTilde MásMadrid](https://latilde.masmadrid.org/recortes-emt-transporte-publico-autobuses-almeida/)| 2022/05/19 |
| DEFENSA | Partido Popular | No hay recorte de servicio en EMT | [EuropaPress](https://www.europapress.es/madrid/noticia-carabante-asegura-no-hay-recorte-servicio-emt-mas-madrid-alerta-casi-40-autobuses-menos-16-lineas-20220523120756.html) | 2022/05/23 |
| QUEJA | PSOE | Reducción de turnos y autobuses | [Twitter - Ignacio Benito](https://twitter.com/ignaciobenitop/status/1308060022476333058) | 2020/09/21 |
| HUELGA | Partido Popular | Con la mitad de los autobuses en circulación, los viajeros han sufrido largas colas y esperas de 45 minutos. | [Periódico ABC](https://www.abc.es/espana/madrid/abci-tercera-jornada-paros-parciales-colas-45-minutos-mitad-autobuses-201911271019_noticia.html) | 2019/11/27 | 