Bienes secuestrados y decomisados durante el proceso penal
==========================================================

En este conjunto de datos se detallan los bienes secuestrados, decomisados y/ o afectados a una medida cautelar, durante la sustanciación de un proceso penal, que fueran informados al Registro de Bienes Secuestrados y Decomisados durante el Proceso Penal (RNBSD) por la autoridad interviniente en dicho proceso, cuya competencia es de carácter Nacional y/ o Federal.

Dicho RNBSD ha sido se creado por [Decreto Nº 826](http://servicios.infoleg.gob.ar/infolegInternet/anexos/180000-184999/183500/norma.htm) del 17 de Junio de 2011, en el ámbito del Ministerio de Justicia y Derechos Humanos de la Nación, para identificar, registrar, valuar y localizar la totalidad de los bienes secuestrados, decomisados o afectados a una medida cautelar, en el marco de un proceso penal, con la finalidad de articular, coordinar e implementar políticas públicas activas para combatir el lavado de activos de origen ilícito en nuestro país y la región.

En este mismo orden de ideas, la [Decisión Administrativa N° 483](http://www.infoleg.gob.ar/infolegInternet/anexos/260000-264999/261473/norma.htm) del 17 de mayo de 2016, que aprueba la Estructura Organizativa del Ministerio de Justicia y Derechos Humanos, y determina que el RNBSD depende de la Coordinación de Registro de Bienes y Derechos Reales, dependiente de la Subsecretaria de Asuntos Registrales y determina cuál será la responsabilidad primaria y las acciones de dicho organismo.

En la sección notas se detallará la normativa Nacional e Internacional vinculada con la actividad del registro.

http://datos.jus.gob.ar/dataset/bienes-secuestrados-y-decomisados-durante-el-proceso-penal

Encuesta de satisfacción del usuario:
-------------------------------------
http://relevamientos.jus.gob.ar/index.php/286368

Características
---------------

-   **Fecha de Primera Publicación:** 28/06/2017

-   **Tags o Etiquetas:** bienes, bienes secuestrados, bienes decomisados, medida cautelar, proceso penal, aeronave, armas, vehículos, buque, dinero, estupefacientes, inmuebles

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional del Registro Nacional de Bienes Secuestrados y Decomisados durante el Proceso Penal

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional del Registro Nacional de Bienes Secuestrados y Decomisados durante el Proceso Penal

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional del Registro Nacional de Bienes Secuestrados y Decomisados durante el Proceso Penal

-   **Grupo:** Sistema Registral

-   **Frecuencia de Actualización:** Mensualmente

Recursos disponibles
--------------------

### Bienes secuestrados y decomisados durante el proceso penal - AAAAMMDD

-   **Nombre:** bienes-secuestrados-decomisados-proceso-penal-AAAAMMDD.csv

-   **Descripción del contenido:** se detallan los bienes secuestrados, decomisados o afectados a una medida cautelar, en el marco de un proceso penal, datos del juzgado, delito y características de cada bien tales como marca, modelo, etc.

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** listado de bienes secuestrados y decomisados desde marzo de 2012 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **tipo_bien (string):** tipo de bien. Son los activos de cualquier tipo, corporales o incorporales, muebles o inmuebles, tangibles o intangibles, y los documentos o instrumentos legales que acrediten la propiedad u otros derechos sobre dichos activos. Pueden ser aeronave, armas, automotores, buques, dinero, estupefacientes o inmuebles

-   **numero_oficio (int):** número correspondiente oficio mediante el cual la autoridad interviniente informa los bienes secuestrados y/ o decomisados en el marco de un proceso penal

-   **juzgado (string):** nombre de la autoridad interviniente según corresponda: Juzgado, Tribunal, Fiscalía

-   **expediente (string):** es el número con el que se registra la causa o causas porque a veces son varias

-   **causa (string):** se describe el delito y los participantes del mismo

-   **tipo_delito (string):** describe el tipo de delito que se sustancia en el marco de un proceso penal

-   **medida (string):** tipo de medida. Consiste en la medida adoptada por la autoridad interviniente en el marco del proceso penal. Pueden ser: afectado a medida cautelar – Embargo, afectado a otra medida, decomiso o secuestro

-   **fecha_recepcion (date):** fecha de recepción del oficio por el Registro Nacional de Bienes Secuestrados y Decomisados durante el Proceso Penal

-   **fecha_oficio (date):** es la fecha en la que se libra el oficio, muchas veces es la sentencia final así que va a ser la misma fecha de la medida

-   **fecha_medida (date):** fecha de la medida adoptada por la autoridad interviniente. No siempre es informada

-   **fecha_desicion_judicial (date):** es la fecha en la que se resuelve la situación jurídica del bien

-   **situacion_juridica (string):** es la situación en la que se encuentra el bien luego de su secuestro o decomiso

-   **localizacion (string):** **:** lugar donde se encuentra el bien, ubicación física del bien

-   **provincia (string):** nombre de provincial donde se encuentra localizado el bien

-   **estupefaciente_sustancia (string):** tipo de sustancia psicotrópica informada por la autoridad interviniente, la cual puede ser: Cocaína, Hojas de coca, Hongos, LSD, Marihuana, Éxtasis, de uso famacológico, etc. Sólo posee datos si el bien es estupefacientes

-   **estupefaciente_cantidad (string):** cantidad en gramos de la sustancia. Sólo posee datos si el bien es estupefacientes

-   **arma_tipo (string):** tipo de arma informada por la autoridad interviniente, la cual puede ser: Ametralladora, Carabina, Escopeta, Fusil, Pistola, Revolver, Subfusil, etc. Sólo posee datos si el bien es arma

-   **arma_numero_serie (string):** número de serie del arma. Sólo posee datos si el bien es arma

-   **arma_marca (string):** marca del arma. Sólo posee datos si el bien es arma

-   **arma_modelo (string):** modelo del arma. Sólo posee datos si el bien es arma

-   **arma_calibre (string):** calibre del arma. Sólo posee datos si el bien es arma

-   **automotor_tipo (string):** tipo de automotor informado por la autoridad interviniente, el cual puede ser: Automóvil, Camión, Camioneta, Casa Rodante, Colectivo, Jeep, Moto-vehículo, Trailer, etc. Sólo posee datos si el bien es automotor

-   **automotor_dominio (string):** número de dominio del automotor. Sólo posee datos si el bien es automotor

-   **automotor_marca (string):** marca del automotor. Sólo posee datos si el bien es automotor

-   **automotor_modelo (string):** modelo del automotor. Sólo posee datos si el bien es automotor

-   **automotor_color (string):** color del automotor. Sólo posee datos si el bien es automotor

-   **automotor_anio (string):** año modelo del automotor. Sólo posee datos si el bien es automotor

-   **aeronave_numero_serie (string):** número de serie de la aeronave. Sólo posee datos si el bien es aeronave

-   **aeronave_matricula (string):** número de matrícula de la aeronave. Sólo posee datos si el bien es aeronave

-   **aeronave_marca (string):** marca de la aeronave. Sólo posee datos si el bien es aeronave

-   **aeronave_modelo (string):** modelo de la aeronave. Sólo posee datos si el bien es aeronave

-   **buque_pais (string):** país al que pertenece el buque. Sólo posee datos si el bien es buque

-   **buque_nombre (string):** nombre del buque. Sólo posee datos si el bien es buque

-   **buque_matricula (string):** número de matrícula del buque. Sólo posee datos si el bien es buque

-   **dinero_moneda_descripcion (string):** tipo de moneda. Cualquier tipo de moneda informada por la autoridad interviniente, generalmente, dólares, pesos argentinos, reales, soles, etc. Sólo posee datos si el bien es dinero

-   **dinero_cantidad (string):** monto en la moneda especificada. Sólo posee datos si el bien es dinero

-   **titulo_tipo (string):** tipo de título. Sólo posee datos si el bien es título

-   **titulo_nombre_emisor (string):** nombre del emisor del título. Sólo posee datos si el bien es título

-   **titulo_cantidad (string):** cantidad de títulos. Sólo posee datos si el bien es título  

-   **titulo_fecha_vencimiento (string):** fecha de vencimiento del título. Sólo posee datos si el bien es título

-   **titulo_categoria (string):** categoría del título. Sólo posee datos si el bien es título  

-   **titulo_bolsa_cotiza (string):** Bolsa en que cotiza . Sólo posee datos si el bien es título

-   **titulo_moneda (string):** tipo de moneda. Sólo posee datos si el bien es título             

-   **otro_clasificacion (string):** otro tipo de bienes. Sólo posee datos si el bien es otro     

-   **otro_detalle (string):** detalle de los bienes encuadrados en la categoría otros. Sólo posee datos si el bien es otro

-   **provincia_id (string):** código de la provincia donde se encuentra localizado el bien según la codificación INDEC (hasta 05/2019 nombre campo provincia_indec_id)

### Bienes secuestrados y decomisados durante el proceso penal - AAAA

-   **Nombre:** bienes-secuestrados-decomisados-durante-proceso-penal-AAAA.zip

-   **Descripción del contenido:** archivo comprimido correspondiente al año AAAA con los archivos publicados en el portal datos.jus.gob.ar durante dicho año

-   **Formato:** ZIP

### Notas

[Ley 27.275 - Derecho de Acceso a la Información Pública]( http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

Convenciones internacionales vinculadas con el RNBSD y las leyes nacionales que aprueban dichas convenciones.

• Convención de las Naciones Unidas contra el Tráfico Ilícito de Estupefacientes y Sustancias Psicotrópicas. Ley N° 24.072.

http://www.infoleg.gob.ar/infolegInternet/anexos/0-4999/471/norma.htm

• Convención Interamericana contra la corrupción. Ley N° 24.759.

http://www.infoleg.gob.ar/infolegInternet/anexos/40000-44999/41466/norma.htm

• Convención Internacional Contra la Delincuencia Organizada Transnacional y protocolos complementarios. Ley N° 25.632.

http://servicios.infoleg.gob.ar/infolegInternet/anexos/75000-79999/77329/norma.htm

• Convención Interamericana Contra el Terrorismo. Ley N°26.023.

http://www.infoleg.gob.ar/infolegInternet/anexos/105000-109999/105500/norma.htm

• Convención de las Naciones Unidas Contra la Corrupción. Ley N° 26.097.

http://www.infoleg.gob.ar/infolegInternet/anexos/115000-119999/116954/norma.htm

• Protocolo contra la Fabricación y el Tráfico Ilícitos de Armas de Fuego, sus Piezas y Componentes y Municiones, que complementa la Convención de las Naciones Unidas contra la Delincuencia Organizada Transnacional, adoptado por la Asamblea General de la Organización de las Naciones Unidas el 31 de mayo de 2001. Ley N° 26.138

http://www.infoleg.gob.ar/infolegInternet/anexos/115000-119999/119448/norma.htm

Código Penal de la Nación.

• Artículo 23: “En todos los casos en que recayese condena por delitos previstos en este Código o en leyes penales especiales, la misma decidirá el decomiso de las cosas que han servido para cometer el hecho y de las cosas o ganancias que son el producto o el provecho del delito, en favor del Estado nacional, de las provincias o de los municipios, salvo los derechos de restitución o indemnización del damnificado y de terceros.

Si las cosas son peligrosas para la seguridad común, el comiso puede ordenarse aunque afecte a terceros, salvo el derecho de éstos, si fueren de buena fe, a ser indemnizados.

Cuando el autor o los partícipes han actuado como mandatarios de alguien o como órganos, miembros o administradores de una persona de existencia ideal, y el producto o el provecho del delito ha beneficiado al mandante o a la persona de existencia ideal, el comiso se pronunciará contra éstos.

Cuando con el producto o el provecho del delito se hubiese beneficiado un tercero a título gratuito, el comiso se pronunciará contra éste.

Si el bien decomisado tuviere valor de uso o cultural para algún establecimiento oficial o de bien público, la autoridad nacional, provincial o municipal respectiva podrá disponer su entrega a esas entidades. Si así no fuere y tuviera valor comercial, aquélla dispondrá su enajenación. Si no tuviera valor lícito alguno, se lo destruirá.

En el caso de condena impuesta por alguno de los delitos previstos por los artículos 125, 125 bis, 127, 140, 142 bis, 145 bis, 145 ter y 170 de este Código, queda comprendido entre los bienes a decomisar la cosa mueble o inmueble donde se mantuviera a la víctima privada de su libelad u objeto de explotación. Los bienes decomisados con motivo de tales delitos, según los términos del presente artículo, y el producido de las multas que se impongan, serán afectados a programas de asistencia a la víctima. (Párrafo sustituido por art. 20 de la Ley N° 26.842 B.O. 27/12/2012)

En caso de los delitos previstos en el artículo 213 ter y quáter y en el Título XIII del libro Segundo de éste Código, serán decomisados de modo definitivo, sin necesidad de condena penal, cuando se hubiere podido comprobar la ilicitud de su origen, o del hecho material al que estuvieren vinculados, y el imputado no pudiere ser enjuiciado por motivo de fallecimiento, fuga, prescripción o cualquier otro motivo de suspensión o extinción de la acción penal, o cuando el imputado hubiere reconocido la procedencia o uso ilícito de los bienes. (Párrafo incorporado por art. 6º de la Ley Nº 26.683 B.O. 21/06/2011)

Todo reclamo o litigio sobre el origen, naturaleza o propiedad de los bienes se realizará a través de una acción administrativa o civil de restitución. Cuando el bien hubiere sido subastado sólo se podrá reclamar su valor monetario. (Párrafo incorporado por art. 6º de la Ley Nº 26.683 B.O. 21/06/2011)

El juez podrá adoptar desde el inicio de las actuaciones judiciales las medidas cautelares suficientes para asegurar el decomiso del o de los inmuebles, fondos de comercio, depósitos, transportes, elementos informáticos, técnicos y de comunicación, y todo otro bien o derecho patrimonial sobre los que, por tratarse de instrumentos o efectos relacionados con el o los delitos que se investigan, el decomiso presumiblemente pueda recaer.

El mismo alcance podrán tener las medidas cautelares destinadas a hacer cesar la comisión del delito o sus efectos, o a evitar que se consolide su provecho o a obstaculizar la impunidad de sus partícipes. En todos los casos se deberá dejar a salvo los derechos de restitución o indemnización del damnificado y de terceros.

• ARTICULO 305. - El juez podrá adoptar desde el inicio de las actuaciones judiciales las medidas cautelares suficientes para asegurar la custodia, administración, conservación, ejecución y disposición del o de los bienes que sean instrumentos, producto, provecho o efectos relacionados con los delitos previstos en los artículos precedentes.

En operaciones de lavado de activos, serán decomisados de modo definitivo, sin necesidad de condena penal, cuando se hubiere podido comprobar la ilicitud de su origen, o del hecho material al que estuvieren vinculados, y el imputado no pudiere ser enjuiciado por motivo de fallecimiento, fuga, prescripción o cualquier otro motivo de suspensión o extinción de la acción penal, o cuando el imputado hubiere reconocido la procedencia o uso ilícito de los bienes.

Los activos que fueren decomisados serán destinados a reparar el daño causado a la sociedad, a las víctimas en particular o al Estado. Sólo para cumplir con esas finalidades podrá darse a los bienes un destino específico.

Todo reclamo o litigio sobre el origen, naturaleza o propiedad de los bienes se realizará a través de una acción administrativa o civil de restitución. Cuando el bien hubiere sido subastado sólo se podrá reclamar su valor monetario.

(Artículo incorporado por art. 5º de la Ley Nº 26.683 B.O. 21/06/2011)

Leyes Nacionales vinculadas con el RNBSD.

• Ley Nº 20.785 - Bienes objeto de secuestro en causas penales. Custodia y disposición.

http://www.infoleg.gob.ar/infolegInternet/anexos/135000-139999/136925/norma.htm

• Decreto 1148/1991. Aprueba la reglamentación del artículo 39 de la Ley 23.737, que determina en su artículo 1° que los beneficios económico a que se refieren los artículos 25° y 30° de la mencionada Ley, los decomisados, o el producido de su venta, y las multas que se recauden por la aplicación de dicha ley, serán entregados a la SECRETARIA DE PROGRAMACION PARA LA PREVENCION DE LA DROGADICCION Y LA LUCHA CONTRA EL NARCOTRAFICO de la PRESIDENCIA DE LA NACION a los efectos de que la misma los destine a la lucha contra el tráfico ilegal de estupefacientes, su prevención y la rehabilitación de los afectados por el consumo de estupefacientes, con las salvedades previstas en los artículos 25º —último párrafo— y 30º —último párrafo— de la ley Nº 23.737.

http://www.infoleg.gob.ar/infolegInternet/anexos/5000-9999/6448/norma.htm

• Ley 23.737 – Legislación complementaria del CODIGO PENAL DE LA NACIÓN. Su modificación. Incorpórase el artículo 18 bis a la Ley N° 10.903. Reemplázanse los artículos 25 y 26 de la Ley N° 20.655 e incorpórase a la misma el artículo 26 bis. Deróganse los artículos 1° al 11 de la Ley N° 20.771 y sus modificatorias.

http://www.infoleg.gob.ar/infolegInternet/anexos/0-4999/138/norma.htm

• Ley 25.938 – REGISTRO NACIONAL DE ARMAS DE FUEGO Y MATERIALES CONTROLADOS, SECUESTRADOS O INCAUTADOS.

ARTICULO 2º.- MATERIALES: En el Registro que se establece por el artículo anterior se asentarán los datos correspondientes a las armas de fuego, sus partes y repuestos, municiones y demás materiales controlados incluidos en la Ley Nacional de Armas y Explosivos y sus reglamentaciones, que hayan sido secuestrados o incautados por las autoridades que se indican en el artículo siguiente. A dicha información tendrán acceso pleno el Registro Nacional de Armas y la Secretaría de Seguridad Interior, a los fines del adecuado ejercicio de sus respectivas competencias.

ARTICULO 7º.- DECOMISO. DESTRUCCION: Cuando en virtud de sentencia judicial o resolución administrativa firme se hubiere dispuesto el decomiso de los materiales comprendidos en el artículo 2º, se deberá proceder a su destrucción, la que se llevará a cabo en el lugar y por los métodos que el Registro Nacional de Armas establezca, con conocimiento de la Secretaría de Seguridad Interior.

La resolución que hubiere dispuesto el decomiso deberá comunicarse al Registro establecido en el artículo 1º, dentro de las cuarenta y ocho (48) horas de haber quedado firme.

• Ley 26.045 - LEY DEL REGISTRO NACIONAL DE PRECURSORES QUIMICOS.

ARTICULO 1º.- Créase en el ámbito de la Secretaría de Programación para la Prevención de la Drogadicción y la Lucha contra el Narcotráfico el Registro Nacional de Precursores Químicos previsto en el artículo 44 de la Ley Nº 23.737.

ARTICULO 12.- La autoridad de aplicación tendrá las siguientes atribuciones:

(…)

1.  Proponer al juez interviniente el destino de los productos o sustancias que se hubiesen decomisado.

• Ley 26.247 - IMPLEMENTACION DE LA CONVENCION SOBRE LA PROHIBICION DEL DESARROLLO, LA PRODUCCION, EL ALMACENAMIENTO Y EL EMPLEO DE ARMAS QUIMICAS Y SOBRE SU DESTRUCCION.\*\*

ARTICULO 25.- Todas las sustancias químicas tóxicas y sus precursores así como las instalaciones destinadas a fines prohibidos por la Convención y la presente ley serán decomisadas y/o destruidas de acuerdo con las disposiciones establecidas en la Convención.

• Ley 26.348 - NORMAS SOBRE AUTOMOTORES ABANDONADOS, PERDIDOS, DECOMISADOS O SECUESTRADOS.

ARTICULO 1º.- Los automotores abandonados, perdidos, decomisados o secuestrados, cuyo dominio corresponda al Estado nacional o a los Estados particulares en virtud de lo establecido en el artículo 2.342 del Código Civil, deberán ser descontaminados y compactados en forma previa a su disposición en calidad de chatarra.

ARTICULO 2º.- Sustitúyese el artículo 10 del Decreto Ley 6582/58 ratificado por la Ley 14.467 (t.o. 1997), con las modificaciones introducidas por las Leyes 25.232, 25.345 y 25.677 por el siguiente:

'Artículo 10: En las inscripciones del dominio de automotores nuevos, de fabricación nacional o importados, el Registro deberá protocolizar con la solicitud respectiva, el certificado de origen del vehículo que a esos fines expedirá el organismo de aplicación, a petición de los respectivos fabricantes e importadores.

En el caso de automotores armados fuera de fábrica, o de sus plantas de montaje, deberá justificarse fehacientemente el origen de los elementos utilizados, los que podrán ser de fabricación artesanal, en la forma en que lo determine el organismo de aplicación, quien resolverá en definitiva acerca de la procedencia o no de las inscripciones de estos tipos de automotores.

En todos los casos deberá acreditarse asimismo el cumplimiento de las condiciones de seguridad activa y pasiva para circular en la forma que determine la normativa específica en la materia. El incumplimiento de este recaudo no impedirá la adquisición del dominio, sin perjuicio de lo cual el Registro no emitirá la correspondiente cédula de identificación a la que se refiere el artículo 22 del presente.'

ARTICULO 3º.- Sustitúyese el artículo 10 bis de la Ley 20.785, modificada por la Ley 22.129, por el siguiente:

Artículo 10 bis: En los supuestos de aeronaves y en tanto no corresponda su entrega a quien tenga derechos sobre ellas, el mismo no sea habido o, citado legalmente, no compareciere a recibirlo, regirán las siguientes disposiciones:

1.  Los organismos oficiales encargados de su depósito, transcurridos SEIS (6) meses desde el día del secuestro solicitarán al juez que haga saber si existe algún impedimento para su remate.

Si dentro de los DIEZ (10) días de recibido el pedido el juez no hiciere saber su oposición por resolución fundada, el organismo oficial encargado del depósito dispondrá la venta en pública subasta a través de las instituciones bancarias mencionadas en el artículo 2°, en las que se depositará el importe obtenido de la venta.

Si el juez se opusiere al remate, el bien permanecerá en depósito.

Cada TRES (3) meses, contados a partir de la negativa que hubiere formulado el juez, se podrá librar un nuevo pedido a los mismos fines y con iguales alcances.

1.  El importe obtenido de la venta devengará el interés al tipo bancario correspondiente.

2.  Si con posterioridad a la subasta, correspondiere la devolución del bien a quien acreditare derecho sobre el mismo, deberá abonársele el producido de la venta con más los intereses al tipo bancario.

ARTICULO 4º.- Incorpórase como artículo 10 ter., a la Ley 20.785, modificada por la Ley 22.129, el siguiente:

Artículo 10 ter: En los supuestos de automotores, y en tanto no corresponda su entrega a quien tenga derechos sobre ellos, el mismo no sea habido o, citado legalmente, no compareciere a recibirlo, transcurridos SEIS (6) meses desde el día del secuestro, o bien en un plazo menor y la autoridad judicial así lo dispusiera, la autoridad encargada de su depósito y custodia procederá a gestionar su descontaminación, compactación y disposición como chatarra. El referido plazo de SEIS (6) meses podrá ser ampliado por el magistrado interviniente por resolución fundada, en la que deberá indicar las razones por las cuales no resulta aplicable el procedimiento de reducción.

Si con posterioridad a la descontaminación, compactación y disposición en calidad de chatarra, correspondiere la devolución del bien a quien acreditare derecho sobre el mismo, deberá abonársele el valor de la chatarra resultante, previa deducción de los importes originados por la descontaminación y compactación.

ARTICULO 7º.- Sustitúyese el artículo 238 del Código Procesal Penal de la Nación por el siguiente:

Artículo 238: Los objetos secuestrados que no estén sometidos a la confiscación, restitución, o embargo, serán devueltos tan pronto como no sean necesarios, a la persona de cuyo poder se sacaron. Esta devolución podrá ordenarse provisionalmente en calidad de depósito, e imponerse al poseedor la obligación de exhibirlos cada vez que le sea requerido.

Los efectos sustraídos serán devueltos, en las mismas condiciones, al damnificado, salvo que se oponga a ello el poseedor de buena fe de cuyo poder hubieran sido secuestrados.

Cuando se trate de automotores, se aplicará lo dispuesto por el artículo 10 ter de la Ley 20.785.

• Ley 26.361 - DEFENSA DEL CONSUMIDOR. Ley 24.240. Modificación.

ARTICULO 21.- Sustitúyese el texto del artículo 47 de la Ley Nº 24.240 de Defensa del Consumidor, por el siguiente: Artículo 47: Sanciones. Verificada la existencia de la infracción, quienes la hayan cometido serán pasibles de las siguientes sanciones, las que se podrán aplicar independiente o conjuntamente, según resulte de las circunstancias del caso:

1.  Apercibimiento.

2.  Multa de PESOS CIEN ($ 100) a PESOS CINCO MILLONES ($ 5.000.000).

3.  Decomiso de las mercaderías y productos objeto de la infracción.

4.  Clausura del establecimiento o suspensión del servicio afectado por un plazo de hasta TREINTA (30) días.

5.  Suspensión de hasta CINCO (5) años en los registros de proveedores que posibilitan contratar con el Estado.

6.  La pérdida de concesiones, privilegios, regímenes impositivos o crediticios especiales de que gozare.

En todos los casos, el infractor publicará o la autoridad de aplicación podrá publicar a costa del infractor, conforme el criterio por ésta indicado, la resolución condenatoria o una síntesis de los hechos que la originaron, el tipo de infracción cometida y la sanción aplicada, en un diario de gran circulación en el lugar donde aquélla se cometió y que la autoridad de aplicación indique. En caso que el infractor desarrolle la actividad por la que fue sancionado en más de una jurisdicción, la autoridad de aplicación podrá ordenar que la publicación se realice en un diario de gran circulación en el país y en uno de cada jurisdicción donde aquél actuare.

Cuando la pena aplicada fuere de apercibimiento, la autoridad de aplicación podrá dispensar su publicación.

El CINCUENTA POR CIENTO (50%) del monto percibido en concepto de multas y otras penalidades impuestas por la autoridad de aplicación conforme el presente artículo será asignado a un fondo especial destinado a cumplir con los fines del Capítulo XVI -EDUCACION AL CONSUMIDOR- de la presente ley y demás actividades que se realicen para la ejecución de políticas de consumo, conforme lo previsto en el artículo 43, inciso a) de la misma. El fondo será administrado por la autoridad nacional de aplicación.

• Ley 26.991 – NUEVA REGULACIÓN DE LAS RELACIONES DE PRODUCCIÓN Y CONSUMO. Ley 20.680. Modificación.

ARTÍCULO 15.- Sustitúyese el artículo 21 de la ley 20.680 y sus modificatorias, por el siguiente:

Artículo 21: Los bienes decomisados serán vendidos o locados por la autoridad de aplicación en un plazo máximo de treinta (30) días corridos desde su decomiso, atendiendo a la naturaleza y características de aquellos. En el caso de que los bienes decomisados sean perecederos, el plazo se reducirá a cinco (5) días corridos; el producto de la venta o locación ingresará a rentas generales de la Nación.

Este Conjunto de datos es publicado en el Portal de Datos Abiertos de la Justicia Argentina mediante [Resolución Nº 482 del Ministerio de Justicia y Derechos Humanos](http://datos.jus.gob.ar/resoluciones/RESOL-2017-482-APN-MJ.pdf), del 26 de Junio de 2017.
