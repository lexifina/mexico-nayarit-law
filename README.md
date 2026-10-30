# Nayarit: law history in git

The law of the State of Nayarit (Estado Libre y Soberano de Nayarit, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-nay/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

155 ordenamientos with 1005 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE NAYARIT | 153 | as first published, then each reform: 17 February 1918 to 4 September 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE NAYARIT | 58 | as first published, then each reform: 21 September 1981 to 18 December 2025 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO DE NAYARIT | 27 | as first published, then each reform: 19 February 1993 to 14 June 2022 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE NAYARIT | 1 | as first published: 1 January 2023 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO DE NAYARIT | 50 | oldest version available, then each reform: 31 December 2015 to 7 March 2026 |
| `ley-arancelaria-de-los-abogados/` | LEY ARANCELARIA DE LOS ABOGADOS PARA EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 4 October 2010 to 9 November 2016 |
| `ley-de-adquisiciones-arrendamientos-y-prestacion-de-servicio/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y PRESTACION DE SERVICIOS DEL ESTADO DE NAYARIT | 2 | as first published, then each reform: 15 January 2022 to 25 May 2023 |
| `ley-de-agua-potable-y-alcantarillado/` | LEY DE AGUA POTABLE Y ALCANTARILLADO DEL ESTADO DE NAYARIT | 13 | as first published, then each reform: 5 October 1995 to 14 June 2022 |
| `ley-de-amnistia/` | LEY DE AMNISTIA DEL ESTADO DE NAYARIT | 1 | as first published: 9 December 2021 |
| `ley-de-archivos/` | LEY DE ARCHIVOS DEL ESTADO DE NAYARIT | 4 | as first published, then each reform: 26 January 2021 to 7 March 2023 |
| `ley-de-asentamientos-humanos-ordenamiento-territorial-y-desa/` | LEY DE ASENTAMIENTOS HUMANOS, ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO PARA EL ESTADO DE NAYARIT | 3 | as first published, then each reform: 30 December 2019 to 8 April 2024 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO PRIVADAS DEL ESTADO DE NAYARIT | 4 | as first published, then each reform: 30 November 2006 to 23 December 2016 |
| `ley-de-atencion-y-proteccion-a-migrantes-y-sus-familias/` | LEY DE ATENCION Y PROTECCION A MIGRANTES Y SUS FAMILIAS DEL ESTADO DE NAYARIT | 4 | as first published, then each reform: 2 January 2019 to 3 October 2026 |
| `ley-de-austeridad/` | LEY DE AUSTERIDAD PARA EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 29 December 2021 to 24 February 2022 |
| `ley-de-benemeritos/` | LEY DE BENEMERITOS DEL ESTADO DE NAYARIT | 1 | as first published: 6 June 2019 |
| `ley-de-bienes/` | LEY DE BIENES DEL ESTADO DE NAYARIT | 1 | as first published: 28 October 2022 |
| `ley-de-catastro/` | LEY DE CATASTRO PARA EL ESTADO DE NAYARIT | 1 | as first published: 20 July 2022 |
| `ley-de-categorias-politicas-para-las-poblaciones-que-forman/` | LEY DE CATEGORIAS POLITICAS PARA LAS POBLACIONES QUE FORMAN EL ESTADO DE NAYARIT, EN RELACION CON SU DIVISION POLITICO TERRITORIAL | 1 | as first published: 31 January 1926 |
| `ley-de-ciencia-tecnologia-e-innovacion/` | LEY DE CIENCIA, TECNOLOGIA E INNOVACION DEL ESTADO DE NAYARIT | 8 | as first published, then each reform: 22 November 2010 to 18 December 2025 |
| `ley-de-conservacion-proteccion-y-puesta-en-valor-del-patrimo/` | LEY DE CONSERVACION, PROTECCION Y PUESTA EN VALOR DEL PATRIMONIO HISTORICO Y CULTURAL DEL ESTADO DE NAYARIT | 4 | as first published, then each reform: 29 October 1989 to 9 November 2016 |
| `ley-de-control-constitucional/` | LEY DE CONTROL CONSTITUCIONAL DEL ESTADO DE NAYARIT | 6 | as first published, then each reform: 3 June 2010 to 27 May 2023 |
| `ley-de-coordinacion-fiscal-y-de-gasto-publico/` | LEY DE COORDINACION FISCAL Y DE GASTO PUBLICO DEL ESTADO DE NAYARIT | 5 | as first published, then each reform: 17 December 1998 to 15 September 2020 |
| `ley-de-coordinacion-metropolitana/` | LEY DE COORDINACION METROPOLITANA DEL ESTADO DE NAYARIT | 1 | as first published: 2 January 2020 |
| `ley-de-cultura-fisica-y-deporte/` | LEY DE CULTURA FISICA Y DEPORTE PARA EL ESTADO DE NAYARIT | 6 | as first published, then each reform: 3 May 2010 to 28 April 2026 |
| `ley-de-cultura-y-justicia-civica/` | LEY DE CULTURA Y JUSTICIA CIVICA PARA EL ESTADO DE NAYARIT | 5 | as first published, then each reform: 1 January 2020 to 16 September 2025 |
| `ley-de-declaracion-especial-de-ausencia-para-personas-desapa/` | LEY DE DECLARACION ESPECIAL DE AUSENCIA PARA PERSONAS DESAPARECIDAS DEL ESTADO DE NAYARIT | 1 | as first published: 17 March 2022 |
| `ley-de-defensoria-publica-y-asistencia-juridica/` | LEY DE DEFENSORIA PUBLICA Y ASISTENCIA JURIDICA PARA EL ESTADO DE NAYARIT | 1 | as first published: 19 December 2014 |
| `ley-de-derechos-de-los-enfermos-en-etapa-terminal/` | LEY DE DERECHOS DE LOS ENFERMOS EN ETAPA TERMINAL PARA EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 10 January 2013 to 9 November 2016 |
| `ley-de-derechos-y-cultura-indigena/` | LEY DE DERECHOS Y CULTURA INDIGENA DEL ESTADO DE NAYARIT | 6 | as first published, then each reform: 19 December 2004 to 16 September 2025 |
| `ley-de-derechos-y-justicia-laboral-para-los-trabajadores-al/` | LEY DE DERECHOS Y JUSTICIA LABORAL PARA LOS TRABAJADORES AL SERVICIO DEL ESTADO DE NAYARIT | 4 | as first published, then each reform: 29 May 2022 to 8 May 2026 |
| `ley-de-desarrollo-cultural/` | LEY DE DESARROLLO CULTURAL PARA EL ESTADO DE NAYARIT | 4 | as first published, then each reform: 25 October 2011 to 16 September 2025 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE PARA EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 2 June 2023 to 3 September 2026 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA DEL ESTADO DE NAYARIT | 2 | as first published, then each reform: 22 October 2016 to 12 April 2022 |
| `ley-de-division-territorial/` | LEY DE DIVISION TERRITORIAL DEL ESTADO DE NAYARIT | 7 | as first published, then each reform: 5 February 1984 to 12 July 2022 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO DE NAYARIT | 35 | as first published, then each reform: 14 July 1994 to 14 April 2026 |
| `ley-de-educacion-superior/` | LEY DE EDUCACION SUPERIOR DEL ESTADO DE NAYARIT | 1 | oldest version available: 16 March 2024 |
| `ley-de-ejecucion-de-sanciones-penales-medidas-de-seguridad-y/` | LEY DE EJECUCION DE SANCIONES PENALES, MEDIDAS DE SEGURIDAD Y PRISION PREVENTIVA PARA EL ESTADO DE NAYARIT | 3 | as first published, then each reform: 1 January 2012 to 5 September 2013 |
| `ley-de-empresas-publicas-descentralizadas/` | LEY DE EMPRESAS PUBLICAS DESCENTRALIZADAS DEL ESTADO DE NAYARIT | 1 | as first published: 4 March 1973 |
| `ley-de-entrega-recepcion-de-la-administracion-publica/` | LEY DE ENTREGA-RECEPCION DE LA ADMINISTRACION PUBLICA DEL ESTADO DE NAYARIT | 1 | as first published: 30 May 2020 |
| `ley-de-expropiacion/` | LEY DE EXPROPIACION PARA EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 30 March 2022 to 23 July 2024 |
| `ley-de-firma-electronica-avanzada/` | LEY DE FIRMA ELECTRONICA AVANZADA PARA EL ESTADO DE NAYARIT | 1 | as first published: 14 June 2022 |
| `ley-de-fiscalizacion-y-rendicion-de-cuentas/` | LEY DE FISCALIZACION Y RENDICION DE CUENTAS DEL ESTADO DE NAYARIT | 7 | as first published, then each reform: 28 December 2016 to 24 December 2024 |
| `ley-de-fomento-a-las-actividades-de-las-organizaciones-de-la/` | LEY DE FOMENTO A LAS ACTIVIDADES DE LAS ORGANIZACIONES DE LA SOCIEDAD CIVIL EN EL ESTADO DE NAYARIT | 4 | as first published, then each reform: 8 June 2021 to 16 July 2025 |
| `ley-de-fomento-al-turismo/` | LEY DE FOMENTO AL TURISMO DEL ESTADO DE NAYARIT | 7 | as first published, then each reform: 5 May 2005 to 16 July 2025 |
| `ley-de-fomento-para-la-creacion-de-libros-y-la-lectura/` | LEY DE FOMENTO PARA LA CREACION DE LIBROS Y LA LECTURA DEL ESTADO DE NAYARIT | 4 | as first published, then each reform: 30 May 2010 to 16 September 2025 |
| `ley-de-fraccionamientos-y-acciones-de-urbanizacion/` | LEY DE FRACCIONAMIENTOS Y ACCIONES DE URBANIZACION DEL ESTADO DE NAYARIT | 2 | as first published, then each reform: 5 April 2023 to 8 April 2024 |
| `ley-de-gobierno-digital/` | LEY DE GOBIERNO DIGITAL PARA EL ESTADO DE NAYARIT | 1 | as first published: 14 June 2022 |
| `ley-de-hacienda/` | LEY DE HACIENDA DEL ESTADO DE NAYARIT | 15 | as first published, then each reform: 23 December 2012 to 29 December 2025 |
| `ley-de-hacienda-municipal/` | LEY DE HACIENDA MUNICIPAL DEL ESTADO DE NAYARIT | 14 | as first published, then each reform: 1 January 1984 to 8 October 2022 |
| `ley-de-igualdad-entre-mujeres-y-hombres/` | LEY DE IGUALDAD ENTRE MUJERES Y HOMBRES PARA EL ESTADO DE NAYARIT | 7 | as first published, then each reform: 24 April 2011 to 19 September 2026 |
| `ley-de-imagen-institucional/` | LEY DE IMAGEN INSTITUCIONAL PARA EL ESTADO DE NAYARIT | 3 | as first published, then each reform: 17 December 2017 to 16 September 2021 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO LIBRE Y SOBERANO DE NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-acaponeta-nayarit-para-el-e/` | LEY DE INGRESOS DEL MUNICIPIO DE ACAPONETA, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-ahuacatlan-nayarit-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE AHUACATLAN, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-amatlan-de-canas-nayarit-pa/` | LEY DE INGRESOS DEL MUNICIPIO DE AMATLAN DE CAÑAS, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-bahia-de-banderas-nayarit-p/` | LEY DE INGRESOS DEL MUNICIPIO DE BAHIA DE BANDERAS, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-compostela-nayarit-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE COMPOSTELA, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 2 | as first published, then each reform: 1 January 2026 to 12 January 2026 |
| `ley-de-ingresos-del-municipio-de-del-nayar-nayarit-para-el-e/` | LEY DE INGRESOS DEL MUNICIPIO DE DEL NAYAR, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-huajicori-nayarit-para-el-e/` | LEY DE INGRESOS DEL MUNICIPIO DE HUAJICORI, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-ixtlan-del-rio-nayarit-para/` | LEY DE INGRESOS DEL MUNICIPIO DE IXTLAN DEL RIO, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-jala-nayarit-para-el-ejerci/` | LEY DE INGRESOS DEL MUNICIPIO DE JALA, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-la-yesca-nayarit-para-el-ej/` | LEY DE INGRESOS DEL MUNICIPIO DE LA YESCA, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-rosamorada-nayarit-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE ROSAMORADA, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-ruiz-nayarit-para-el-ejerci/` | LEY DE INGRESOS DEL MUNICIPIO DE RUIZ, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-san-blas-nayarit-para-el-ej/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN BLAS, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-san-pedro-lagunillas-nayari/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN PEDRO LAGUNILLAS, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 2 | as first published, then each reform: 29 December 2025 to 9 January 2026 |
| `ley-de-ingresos-del-municipio-de-santa-maria-del-oro-nayarit/` | LEY DE INGRESOS DEL MUNICIPIO DE SANTA MARIA DEL ORO, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-santiago-ixcuintla-nayarit/` | LEY DE INGRESOS DEL MUNICIPIO DE SANTIAGO, IXCUINTLA, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 2 | as first published, then each reform: 1 January 2026 to 12 January 2026 |
| `ley-de-ingresos-del-municipio-de-tecuala-nayarit-para-el-eje/` | LEY DE INGRESOS DEL MUNICIPIO DE TECUALA, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-tepic-nayarit-para-el-ejerc/` | LEY DE INGRESOS DEL MUNICIPIO DE TEPIC, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 2 | as first published, then each reform: 1 January 2026 to 29 January 2026 |
| `ley-de-ingresos-del-municipio-de-tuxpan-nayarit-para-el-ejer/` | LEY DE INGRESOS DEL MUNICIPIO DE TUXPAN, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-xalisco-nayarit-para-el-eje/` | LEY DE INGRESOS DEL MUNICIPIO DE XALISCO, NAYARIT; PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-inversion-publica/` | LEY DE INVERSION PUBLICA PARA EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 20 December 1998 to 9 November 2016 |
| `ley-de-justicia-alternativa/` | LEY DE JUSTICIA ALTERNATIVA PARA EL ESTADO DE NAYARIT | 4 | as first published, then each reform: 22 July 2011 to 24 December 2016 |
| `ley-de-justicia-electoral/` | LEY DE JUSTICIA ELECTORAL PARA EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 8 October 2016 to 7 October 2020 |
| `ley-de-justicia-y-procedimientos-administrativos/` | LEY DE JUSTICIA Y PROCEDIMIENTOS ADMINISTRATIVOS DEL ESTADO DE NAYARIT | 5 | as first published, then each reform: 22 December 2016 to 27 May 2023 |
| `ley-de-la-administracion-publica-paraestatal-nayarit/` | LEY DE LA ADMINISTRACION PUBLICA PARAESTATAL, NAYARIT | 3 | as first published, then each reform: 14 April 1985 to 29 May 2017 |
| `ley-de-los-derechos-de-las-personas-adultas-mayores/` | LEY DE LOS DERECHOS DE LAS PERSONAS ADULTAS MAYORES PARA EL ESTADO DE NAYARIT | 5 | as first published, then each reform: 10 December 2015 to 16 September 2025 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES PARA EL ESTADO DE NAYARIT | 13 | as first published, then each reform: 5 November 2015 to 20 March 2026 |
| `ley-de-mejora-regulatoria/` | LEY DE MEJORA REGULATORIA PARA EL ESTADO DE NAYARIT Y SUS MUNICIPIOS | 2 | as first published, then each reform: 22 December 2019 to 14 June 2022 |
| `ley-de-movilidad/` | LEY DE MOVILIDAD DEL ESTADO DE NAYARIT | 12 | as first published, then each reform: 8 January 2020 to 21 July 2026 |
| `ley-de-obra-publica/` | LEY DE OBRA PUBLICA DEL ESTADO DE NAYARIT | 2 | as first published, then each reform: 17 January 2026 to 18 March 2026 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA DEL ESTADO DE NAYARIT | 2 | as first published, then each reform: 22 March 2013 to 24 May 2018 |
| `ley-de-pesca-y-acuacultura-sustentables/` | LEY DE PESCA Y ACUACULTURA SUSTENTABLES PARA EL ESTADO DE NAYARIT | 8 | as first published, then each reform: 24 June 2011 to 1 April 2026 |
| `ley-de-planeacion/` | LEY DE PLANEACION DEL ESTADO DE NAYARIT | 8 | as first published, then each reform: 1 June 2019 to 8 April 2024 |
| `ley-de-presupuestacion-contabilidad-y-gasto-publico-de-la-ad/` | LEY DE PRESUPUESTACION, CONTABILIDAD Y GASTO PUBLICO DE LA ADMINISTRACION DEL GOBIERNO DEL ESTADO DE NAYARIT | 9 | as first published, then each reform: 30 November 1989 to 5 November 2022 |
| `ley-de-prevencion-asistencia-y-atencion-de-la-violencia-intr/` | LEY DE PREVENCION, ASISTENCIA Y ATENCION DE LA VIOLENCIA INTRAFAMILIAR PARA EL ESTADO DE NAYARIT | 3 | as first published, then each reform: 13 May 2004 to 9 November 2016 |
| `ley-de-proteccion-a-la-fauna/` | LEY DE PROTECCION A LA FAUNA PARA EL ESTADO DE NAYARIT | 9 | as first published, then each reform: 17 December 2006 to 8 May 2026 |
| `ley-de-proteccion-a-la-industria-de-molinos-para-nixtamal-y/` | LEY DE PROTECCION A LA INDUSTRIA DE MOLINOS PARA NIXTAMAL Y SUS DERIVADOS, PARA EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 30 October 1957 to 22 July 1961 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL PARA EL ESTADO DE NAYARIT | 5 | as first published, then each reform: 24 July 2003 to 26 September 2019 |
| `ley-de-proteccion-de-agentes-polinizadores-y-fomento-apicola/` | LEY DE PROTECCION DE AGENTES POLINIZADORES Y FOMENTO APICOLA PARA EL ESTADO DE NAYARIT | 1 | as first published: 8 June 2021 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS PARA EL ESTADO DE NAYARIT | 4 | as first published, then each reform: 22 October 2017 to 2 June 2026 |
| `ley-de-proteccion-fomento-y-conservacion-del-arbolado-public/` | LEY DE PROTECCION, FOMENTO Y CONSERVACION DEL ARBOLADO PUBLICO DEL ESTADO DE NAYARIT | 1 | as first published: 17 December 2019 |
| `ley-de-remuneraciones-de-los-servidores-publicos/` | LEY DE REMUNERACIONES DE LOS SERVIDORES PUBLICOS DEL ESTADO DE NAYARIT | 1 | as first published: 14 December 2021 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE NAYARIT Y SUS MUNICIPIOS | 2 | as first published, then each reform: 1 January 2007 to 9 November 2016 |
| `ley-de-responsabilidades-administrativas/` | LEY DE RESPONSABILIDADES ADMINISTRATIVAS DEL ESTADO DE NAYARIT | 4 | as first published, then each reform: 24 November 2023 to 7 March 2026 |
| `ley-de-salud/` | LEY DE SALUD PARA EL ESTADO DE NAYARIT | 29 | as first published, then each reform: 1 May 1994 to 8 May 2026 |
| `ley-de-seguridad-integral-escolar/` | LEY DE SEGURIDAD INTEGRAL ESCOLAR PARA EL ESTADO DE NAYARIT | 3 | as first published, then each reform: 19 February 2010 to 3 June 2021 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE NAYARIT | 2 | as first published, then each reform: 30 December 2025 to 28 January 2026 |
| `ley-de-victimas/` | LEY DE VICTIMAS PARA EL ESTADO DE NAYARIT | 4 | as first published, then each reform: 26 August 2014 to 4 June 2019 |
| `ley-de-vivienda/` | LEY DE VIVIENDA PARA EL ESTADO DE NAYARIT | 4 | as first published, then each reform: 7 June 2009 to 16 September 2025 |
| `ley-del-fondo-de-ahorro-para-el-retiro-digno-de-las-trabajad/` | LEY DEL FONDO DE AHORRO PARA EL RETIRO DIGNO DE LAS TRABAJADORAS Y DE LOS TRABAJADORES DEL ESTADO LIBRE Y SOBERANO DE NAYARIT | 1 | as first published: 19 March 2023 |
| `ley-del-fondo-soberano-nuevo-nayarit/` | LEY DEL FONDO SOBERANO NUEVO NAYARIT | 2 | as first published, then each reform: 19 March 2023 to 22 February 2024 |
| `ley-del-notariado/` | LEY DEL NOTARIADO PARA EL ESTADO DE NAYARIT | 3 | as first published, then each reform: 30 April 2022 to 5 May 2023 |
| `ley-del-patronato-para-administrar-el-impuesto-especial-dest/` | LEY DEL PATRONATO PARA ADMINISTRAR EL IMPUESTO ESPECIAL DESTINADO A LA UNIVERSIDAD AUTONOMA DE NAYARIT -ANTES LEY DEL PATRONATO PARA ADMINISTRAR EL IMPUESTO ADICIONAL DEL 10% DESTINADO A LA UAN | 5 | as first published, then each reform: 1 January 1996 to 9 December 2021 |
| `ley-del-periodico-oficial/` | LEY DEL PERIODICO OFICIAL DEL ESTADO DE NAYARIT | 3 | as first published, then each reform: 11 December 2003 to 14 June 2022 |
| `ley-del-registro-publico/` | LEY DEL REGISTRO PUBLICO DEL ESTADO DE NAYARIT | 4 | as first published, then each reform: 20 July 2022 to 2 July 2024 |
| `ley-del-sistema-de-geografia-estadistica-y-evaluacion/` | LEY DEL SISTEMA DE GEOGRAFIA, ESTADISTICA Y EVALUACION DEL ESTADO DE NAYARIT- ANTES - LEY DEL SISTEMA DE INFORMACION ESTADISTICA Y GEOGRAFICA DEL ESTADO DE NAYARIT | 4 | as first published, then each reform: 28 December 2014 to 10 October 2023 |
| `ley-del-sistema-estatal-de-seguridad-publica-nayarit/` | LEY DEL SISTEMA ESTATAL DE SEGURIDAD PUBLICA, NAYARIT | 6 | as first published, then each reform: 24 May 2009 to 6 December 2025 |
| `ley-del-sistema-local-anticorrupcion/` | LEY DEL SISTEMA LOCAL ANTICORRUPCION DEL ESTADO DE NAYARIT | 3 | as first published, then each reform: 22 December 2016 to 20 November 2025 |
| `ley-electoral/` | LEY ELECTORAL DEL ESTADO DE NAYARIT | 10 | as first published, then each reform: 19 August 2010 to 21 October 2025 |
| `ley-en-materia-de-desaparicion-de-personas/` | LEY EN MATERIA DE DESAPARICION DE PERSONAS PARA EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 29 August 2020 to 27 July 2026 |
| `ley-estatal-del-equilibrio-ecologico-y-proteccion-al-ambient/` | LEY ESTATAL DEL EQUILIBRIO ECOLOGICO Y PROTECCION AL AMBIENTE DEL ESTADO DE NAYARIT | 20 | as first published, then each reform: 26 April 2001 to 16 September 2025 |
| `ley-municipal/` | LEY MUNICIPAL PARA EL ESTADO DE NAYARIT | 47 | as first published, then each reform: 5 August 2001 to 3 October 2026 |
| `ley-organica-de-la-comision-de-defensa-de-los-derechos-human/` | LEY ORGANICA DE LA COMISION DE DEFENSA DE LOS DERECHOS HUMANOS PARA EL ESTADO DE NAYARIT | 13 | as first published, then each reform: 17 August 2008 to 31 May 2024 |
| `ley-organica-de-la-escuela-normal-superior-de-nayarit/` | LEY ORGANICA DE LA ESCUELA NORMAL SUPERIOR DE NAYARIT | 3 | as first published, then each reform: 2 March 1974 to 16 May 1987 |
| `ley-organica-de-la-fiscalia-general/` | LEY ORGANICA DE LA FISCALIA GENERAL DEL ESTADO DE NAYARIT | 17 | as first published, then each reform: 16 May 2014 to 6 December 2025 |
| `ley-organica-de-la-universidad-autonoma-de-nayarit/` | LEY ORGANICA DE LA UNIVERSIDAD AUTONOMA DE NAYARIT | 6 | as first published, then each reform: 24 August 2003 to 12 April 2022 |
| `ley-organica-del-centro-de-conciliacion-laboral/` | LEY ORGANICA DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE NAYARIT | 2 | as first published, then each reform: 9 December 2021 to 9 December 2021 |
| `ley-organica-del-poder-ejecutivo/` | LEY ORGANICA DEL PODER EJECUTIVO DEL ESTADO DE NAYARIT | 41 | as first published, then each reform: 1 January 2001 to 14 February 2026 |
| `ley-organica-del-poder-legislativo/` | LEY ORGANICA DEL PODER LEGISLATIVO DEL ESTADO DE NAYARIT | 34 | as first published, then each reform: 18 August 2007 to 21 July 2026 |
| `ley-organica-del-tribunal-de-justicia-administrativa-de-naya/` | LEY ORGANICA DEL TRIBUNAL DE JUSTICIA ADMINISTRATIVA DE NAYARIT | 2 | as first published, then each reform: 27 May 2023 to 7 March 2026 |
| `ley-para-el-desarrollo-agricola-sustentable/` | LEY PARA EL DESARROLLO AGRICOLA SUSTENTABLE DEL ESTADO DE NAYARIT | 8 | as first published, then each reform: 1 January 2013 to 23 May 2026 |
| `ley-para-el-desarrollo-social/` | LEY PARA EL DESARROLLO SOCIAL DEL ESTADO DE NAYARIT | 4 | as first published, then each reform: 25 January 2020 to 28 April 2026 |
| `ley-para-el-ejercicio-de-las-profesiones-y-actividades-tecni/` | LEY PARA EL EJERCICIO DE LAS PROFESIONES Y ACTIVIDADES TECNICAS EN EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 2 March 1987 to 4 October 2022 |
| `ley-para-evaluar-el-desempeno-de-servidores-publicos/` | LEY PARA EVALUAR EL DESEMPEÑO DE SERVIDORES PUBLICOS DEL ESTADO DE NAYARIT | 2 | as first published, then each reform: 18 December 2012 to 15 July 2025 |
| `ley-para-fomentar-la-donacion-altruista-de-articulos-de-prim/` | LEY PARA FOMENTAR LA DONACION ALTRUISTA DE ARTICULOS DE PRIMERA NECESIDAD DEL ESTADO DE NAYARIT | 2 | as first published, then each reform: 12 November 2010 to 9 November 2016 |
| `ley-para-la-administracion-de-bienes-asegurados-decomisados/` | LEY PARA LA ADMINISTRACION DE BIENES ASEGURADOS, DECOMISADOS O ABANDONADOS PARA EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 27 March 2015 to 27 July 2021 |
| `ley-para-la-atencion-y-proteccion-a-personas-con-la-condicio/` | LEY PARA LA ATENCION Y PROTECCION A PERSONAS CON LA CONDICION DEL ESPECTRO AUTISTA DEL ESTADO DE NAYARIT | 2 | as first published, then each reform: 19 March 2021 to 10 December 2022 |
| `ley-para-la-competitividad-y-el-empleo/` | LEY PARA LA COMPETITIVIDAD Y EL EMPLEO DEL ESTADO DE NAYARIT | 6 | as first published, then each reform: 17 September 2009 to 12 September 2026 |
| `ley-para-la-creacion-fomento-y-proteccion-de-nuevos-conjunto/` | LEY PARA LA CREACION, FOMENTO Y PROTECCION DE NUEVOS CONJUNTOS, PARQUES Y CIUDADES INDUSTRIALES EN EL ESTADO DE NAYARIT | 1 | as first published: 18 October 1975 |
| `ley-para-la-inscripcion-de-nombres-en-el-muro-de-honor-del-r/` | LEY PARA LA INSCRIPCION DE NOMBRES EN EL MURO DE HONOR DEL RECINTO LEGISLATIVO DEL ESTADO DE NAYARIT | 2 | as first published, then each reform: 18 March 2021 to 16 July 2025 |
| `ley-para-la-juventud/` | LEY PARA LA JUVENTUD DEL ESTADO DE NAYARIT | 5 | as first published, then each reform: 20 September 2009 to 16 September 2025 |
| `ley-para-la-prevencion-de-la-obesidad-sobrepeso-y-trastornos/` | LEY PARA LA PREVENCION DE LA OBESIDAD, SOBREPESO Y TRASTORNOS ALIMENTICIOS EN EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 24 January 2011 to 6 September 2015 |
| `ley-para-la-prevencion-social-de-la-violencia-y-la-delincuen/` | LEY PARA LA PREVENCION SOCIAL DE LA VIOLENCIA Y LA DELINCUENCIA DEL ESTADO DE NAYARIT | 2 | as first published, then each reform: 4 July 2011 to 26 November 2015 |
| `ley-para-la-prevencion-y-erradicacion-de-la-trata-de-persona/` | LEY PARA LA PREVENCION Y ERRADICACION DE LA TRATA DE PERSONAS EN EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 13 September 2011 to 9 November 2016 |
| `ley-para-la-proteccion-de-personas-defensoras-de-derechos-hu/` | LEY PARA LA PROTECCION DE PERSONAS DEFENSORAS DE DERECHOS HUMANOS Y PERIODISTAS DEL ESTADO DE NAYARIT | 1 | as first published: 28 July 2017 |
| `ley-para-la-proteccion-e-inclusion-de-las-personas-con-disca/` | LEY PARA LA PROTECCION E INCLUSION DE LAS PERSONAS CON DISCAPACIDAD DEL ESTADO DE NAYARIT -- ANTES LEY DE DISCAPACITADOS DEL ESTADO DE NAYARIT -- ANTES LEY DE INTEGRACION SOCIAL DE PERSONAS CON DISCAPACIDAD DEL ESTADO DE NAYARIT-- | 17 | as first published, then each reform: 14 June 1996 to 30 May 2026 |
| `ley-para-la-proteccion-apoyo-y-promocion-a-la-lactancia-mate/` | LEY PARA LA PROTECCION, APOYO Y PROMOCION A LA LACTANCIA MATERNA DEL ESTADO DE NAYARIT | 1 | as first published: 3 June 2021 |
| `ley-para-prevenir-y-erradicar-la-discriminacion-en-el-estado/` | LEY PARA PREVENIR Y ERRADICAR LA DISCRIMINACION EN EL ESTADO DE NAYARIT | 8 | as first published, then each reform: 11 December 2005 to 23 May 2026 |
| `ley-para-prevenir-y-sancionar-la-tortura-en-el-estado-de-nay/` | LEY PARA PREVENIR Y SANCIONAR LA TORTURA EN EL ESTADO DE NAYARIT | 3 | as first published, then each reform: 28 August 2005 to 9 November 2016 |
| `ley-que-crea-el-consejo-estatal-de-armonizacion-contable-par/` | LEY QUE CREA EL CONSEJO ESTATAL DE ARMONIZACION CONTABLE PARA NAYARIT | 2 | as first published, then each reform: 18 December 2011 to 22 April 2016 |
| `ley-que-crea-el-fondo-de-garantia-de-bienes-y-valores-del-go/` | LEY QUE CREA EL FONDO DE GARANTIA DE BIENES Y VALORES DEL GOBIERNO DEL ESTADO, NAYARIT | 1 | as first published: 16 November 1966 |
| `ley-que-crea-la-comision-de-financiamiento-y-comercializacio/` | LEY QUE CREA LA COMISION DE FINANCIAMIENTO Y COMERCIALIZACION DE PRODUCTOS AGRICOLAS, GANADEROS, PESQUEROS Y ARTESANALES, EN EL ESTADO DE NAYARIT | 1 | as first published: 22 October 1966 |
| `ley-que-crea-la-escuela-normal-superior/` | LEY QUE CREA LA ESCUELA NORMAL SUPERIOR DEL ESTADO, NAYARIT | 1 | as first published: 7 January 1967 |
| `ley-que-crea-la-medalla-nayarit-al-merito/` | LEY QUE CREA LA MEDALLA NAYARIT AL MERITO | 2 | as first published, then each reform: 1 January 2014 to 23 October 2019 |
| `ley-que-crea-la-procuraduria-de-la-defensa-del-menor-y-la-fa/` | LEY QUE CREA LA PROCURADURIA DE LA DEFENSA DEL MENOR Y LA FAMILIA EN EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 1 January 1978 to 13 September 2006 |
| `ley-que-establece-el-derecho-de-via-y-su-aprovechamiento-en/` | LEY QUE ESTABLECE EL DERECHO DE VIA Y SU APROVECHAMIENTO EN LAS VIAS DE COMUNICACION TERRESTRE DEL ESTADO DE NAYARIT | 1 | as first published: 13 December 2025 |
| `ley-que-establece-las-bases-y-lineamientos-para-la-delimitac/` | LEY QUE ESTABLECE LAS BASES Y LINEAMIENTOS PARA LA DELIMITACION TERRITORIAL DEL ESTADO DE NAYARIT Y SUS MUNICIPIOS | 3 | oldest version available, then each reform: 18 December 2011 to 9 November 2016 |
| `ley-que-regula-el-regimen-de-propiedad-en-condominio-de-bien/` | LEY QUE REGULA EL REGIMEN DE PROPIEDAD EN CONDOMINIO DE BIENES INMUEBLES PARA EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 13 June 2002 to 9 November 2016 |
| `ley-que-regula-la-prestacion-de-servicios-para-la-atencion-c/` | LEY QUE REGULA LA PRESTACION DE SERVICIOS PARA LA ATENCION, CUIDADO Y DESARROLLO INTEGRAL INFANTIL PARA EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 30 May 2024 to 9 October 2024 |
| `ley-que-regula-las-casas-de-empeno-en-el-estado-de-nayarit/` | LEY QUE REGULA LAS CASAS DE EMPEÑO EN EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 3 April 2009 to 9 November 2016 |
| `ley-que-regula-los-establecimientos-dedicados-a-la-produccio/` | LEY QUE REGULA LOS ESTABLECIMIENTOS DEDICADOS A LA PRODUCCION, ALMACENAMIENTO, DISTRIBUCION Y ENAJENACION DE BEBIDAS ALCOHOLICAS EN EL ESTADO DE NAYARIT | 2 | as first published, then each reform: 1 January 2023 to 16 September 2025 |
| `ley-que-restringe-el-acceso-a-menores-de-edad-a-medios-de-co/` | LEY QUE RESTRINGE EL ACCESO A MENORES DE EDAD A MEDIOS DE COMUNICACION CON CONTENIDO EXCLUSIVO PARA ADULTOS DEL ESTADO DE NAYARIT | 2 | as first published, then each reform: 12 October 2011 to 9 November 2016 |
| `ley-sobre-el-sistema-estatal-de-asistencia-social/` | LEY SOBRE EL SISTEMA ESTATAL DE ASISTENCIA SOCIAL DEL ESTADO DE NAYARIT | 6 | as first published, then each reform: 2 November 1986 to 16 May 2026 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mazatlan, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
