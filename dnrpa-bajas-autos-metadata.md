DNRPA. Bajas de Autos
=====================

En este conjunto de datos se detallan los datos de vehículos y primer titular de los automotores dados de baja definitivamente. El trámite de baja del automotor se realiza en los Registros Seccionales de la Propiedad del Automotor y Créditos Prendarios dependientes de la Dirección Nacional de los Registros Nacionales de la Propiedad del Automotor y Créditos Prendarios. Se consideran automotores: automóviles, camiones, inclusive los llamados tractores para semirremolque, camionetas, rurales, jeeps, furgones de reparto, ómnibus, microómnibus y colectivos, sus respectivos remolques y acoplados, todos ellos aun cuando no estuvieran carrozados.

http://datos.jus.gob.ar/dataset/bajas-de-autos

Características
---------------

-   **Fecha de Primera Publicación:** 10/01/2019

-   **Tags o Etiquetas:** autos, registración, registros seccionales, titulares, bajas, trámites, vehículos, automotores, DNRPA

-   **Organización:** Ministerio de Justicia. Subsecretaría de Asuntos Registrales. Dirección Nacional de los Registros Nacionales de la Propiedad del Automotor y Créditos Prendarios

-   **Autor:** Ministerio de Justicia. Subsecretaría de Asuntos Registrales. Dirección Nacional de los Registros Nacionales de la Propiedad del Automotor y Créditos Prendarios
  
-   **Responsable:** Ministerio de Justicia. Subsecretaría de Asuntos Registrales. Dirección Nacional de los Registros Nacionales de la Propiedad del Automotor y Créditos Prendarios

-   **Grupo:** Sistema Registral

-   **Frecuencia de Actualización:** Mensualmente

Recursos disponibles
--------------------

### DNRPA. Bajas de autos - AAAAMM

-   **Nombre del archivo:** dnrpa-bajas-autos-AAAAMM.csv

-   **Descripción del contenido:** se detallan las bajas inscriptas en los Registros Seccionales de la Propiedad Automotor en el mes MM del año AAAA

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** bajas inscriptas en los Registros Seccionales de la Propiedad Automotor desde el 01-01-2018 a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **tramite_tipo (string):** indica el tipo de baja efectuada. Puede tomar los valores:

    -   AUTOMOTOR - BAJA C/RECUPERACION DE PIEZAS: baja definitiva del automotor con recuperación de las autopartes cuya comercialización regula la Ley Nº 25.761 y su Decreto Reglamentario Nº 744/04

    -   AUTOMOTOR - BAJA P/DEST/SIN/DESG/ENVEJ: baja definitiva del automotor por destrucción, siniestro, desarme, desgaste o envejecimiento

    -   AUTOMOTOR - BAJA P/EXPORT. DEFINITIVA: baja del automotor por exportación definitiva

-   **tramite_fecha (date):** fecha en la cual se perfecciona el trámite. Formato AAAA-MM-DD

-   **fecha_inscripcion_inicial (date):** fecha de inscripción inicial. Formato AAAA-MM-DD

-   **registro_seccional_codigo (int):** código del Registro Seccional en que se efectuó el trámite. Los códigos de Registros Seccionales están organizados por provincia y competencia

-   **registro_seccional_descripcion (string):** nombre del Registro Seccional en que se efectuó el trámite. Generalmente nombre refiere a la localización del Registro Seccional. No siempre coincide con la localidad del domicilio del titular del automotor

-   **registro_seccional_provincia (string):** provincia donde se localiza el Registro Seccional en que se inscribió el trámite. Corresponde asimismo a la provincia del domicilio del primer titular de la inscripción o de la guarda habitual del dominio

-   **automotor_origen (string):** corresponde al origen del vehículo. Puede tomar los valores I Importado, N Nacional o P Protocolo 21, que se rigen por los aranceles de los automotores nacionales pero se inscriben con el certificado de importación

-   **automotor_anio_modelo (int):** año en que se fabricó el modelo del automotor

-   **automotor_tipo_codigo (string):** código del tipo del automotor

-   **automotor_tipo_descripcion (string):** descripción del tipo del automotor. Puede tomar los valores sedán, pick-up, camión, semirremolque, todo terreno, minibús, etc.

-   **automotor_marca_codigo (string):** código de la marca del automotor

-   **automotor_marca_descripcion (string):** descripción de la marca del automotor

-   **automotor_modelo_codigo (string):** código del modelo del automotor

-   **automotor_modelo_descripcion (string):** descripción del modelo del automotor

-   **automotor_uso_codigo (string):** código de uso del automotor

-   **automotor_uso_descripcion (string):** descripción del uso declarado del automotor. Puede tomar los valores

    -   Privado

    -   Oficial

    -   No declarado

-   **titular_tipo_persona (string):** tipo de persona del primer titular declarado. Puede tomar los valores

    -   Física

    -   Jurídica

    -   No identificada

-   **titular_domicilio_localidad (string):** localidad del domicilio del primer titular declarado

-   **titular_domicilio_provincia (string):** provincia del domicilio del primer titular declarado

-   **titular_genero (string):** género del primer titular declarado. Puede tomar los valores

    -   Masculino (en caso de persona física)

    -   Femenino (en caso de persona física)

    -   No identificado (en caso de persona física)

    -   No aplica (en caso de persona jurídica)

-   **titular_anio_nacimiento (int):** año de nacimiento del primer titular declarado

-   **titular_pais_nacimiento (string):** país de nacimiento del primer titular declarado. En el caso de personas jurídicas toma el valor "No aplica"

-   **titular_porcentaje_titularidad (int):** porcentaje de titularidad

-   **titular_domicilio_provincia_id (string):** código de provincia del domicilio del primer titular declarado, según la codificación de provincia implementada por INDEC. (hasta 05/2019 nombre campo titular_domicilio_provincia_indec_id)

-   **titular_pais_nacimiento_id (string):** código de pais de nacimiento del primer titular declarado, según la codificación de pais implementada por INDEC. (hasta 05/2019 nombre campo titular_pais_nacimiento_indec_id)

### DNRPA. Bajas de autos - AAAA

-   **Nombre:** dnrpa-Bajas-autos-AAAA.zip

-   **Descripción del contenido:** archivo comprimido que contiene las bajas inscriptas en los Registros Seccionales de la Propiedad Automotor en el año AAAA

-   **Formato:** ZIP

### Notas

[Ley 27.275 - Derecho de Acceso a la Información Pública](http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

La actividad registral de los automotores está regulada por el Régimen Jurídico del Automotor, el Digesto de normas técnico-registrales y el Reglamento Interno de Normas Orgánico - Funcionales y Disposiciones Modificatorias. Esta documentación se encuentra disponible en la sección normativa de la [*Página oficial de la DNRPA*](http://www.dnrpa.gov.ar/portal_dnrpa/regimenj2.php) Para consultar más datos referidos a los Registros Seccionales, remitirse al [*Listado de Registros Seccionales de la DNRPA*](http://datos.jus.gob.ar/dataset/listado-de-registros-seccionales-de-la-dnrnpa).

[Ley 25.761 – Desarmado de automotores y venta de sus autopartes](http://servicios.infoleg.gob.ar/infolegInternet/anexos/85000-89999/87496/norma.htm)

[Decreto 744/2004 – Reglamentación Ley Nº 25.761 - Desarmado de automotores y venta de sus autopartes](http://servicios.infoleg.gob.ar/infolegInternet/anexos/95000-99999/95763/norma.htm)

Este Conjunto de datos es publicado en el Portal de Datos Abiertos de la Justicia Argentina mediante [Resolución Nº 881 del Ministerio de Justicia](http://datos.jus.gob.ar/resoluciones/RESOL-2017-881-APN-MJ.pdf), del 14 de Noviembre de 2017.
