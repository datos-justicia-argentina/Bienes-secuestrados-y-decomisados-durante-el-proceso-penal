Bienes Secuestrados y Decomisados durante el Proceso Penal
==========================================================

<span id="características" class="anchor"></span>En este conjunto de datos se detallan los bienes secuestrados, decomisados y/ o afectados a una medida cautelar, durante la sustanciación de un proceso penal, que fueran informados al Registro de Bienes Secuestrados y Decomisados durante el Proceso Penal (RNBSD) por la autoridad interviniente en dicho proceso, cuya competencia es de carácter Nacional y/ o Federal.

Dicho RNBSD ha sido se creado por [*Decreto Nº 826*](http://servicios.infoleg.gob.ar/infolegInternet/anexos/180000-184999/183500/norma.htm) del 17 de Junio de 2011, en el ámbito del Ministerio de Justicia y Derechos Humanos de la Nación, para identificar, registrar, valuar y localizar la totalidad de los bienes secuestrados, decomisados o afectados a una medida cautelar, en el marco de un proceso penal, con la finalidad de articular, coordinar e implementar políticas públicas activas para combatir el lavado de activos de origen ilícito en nuestro país y la región.

En este mismo orden de ideas, la Decisión Administrativa N° 483 ([**http://www.infoleg.gob.ar/infolegInternet/anexos/260000-264999/261473/norma.htm**](http://www.infoleg.gob.ar/infolegInternet/anexos/260000-264999/261473/norma.htm)) del 17 de mayo de 2016, que aprueba la Estructura Organizativa del Ministerio de Justicia y Derechos Humanos, y determina que el RNBSD depende de la Coordinación de Registro de Bienes y Derechos Reales, dependiente de la Subsecretaria de Asuntos Registrales y determina cuál será la responsabilidad primaria y las acciones de dicho organismo.

Características
---------------

-   **Fecha de Primera Publicación:**

-   **Tags o Etiquetas:** bienes, bienes secuestrados, bienes decomisados, medida cautelar, proceso penal, aeronave, armas, vehículos, buque, dinero, estupefacientes, inmuebles

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional del Registro Nacional de Bienes Secuestrados y Decomisados durante el Proceso Penal

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional del Registro Nacional de Bienes Secuestrados y Decomisados durante el Proceso Penal

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional del Registro Nacional de Bienes Secuestrados y Decomisados durante el Proceso Penal

-   **Grupo:** Sistema Registral

-   **Frecuencia de Actualización:** Mensualmente

Recursos disponibles
--------------------

### Bienes Secuestrados y Decomisados durante el Proceso Penal

-   **Nombre:** bienes-secuestrados-decomisados-proceso-penal.csv

-   **Descripción:** Contiene los datos de los bienes secuestrados, decomisados o afectados a una medida cautelar, en el marco de un proceso penal, datos del juzgado, delito y características de cada bien tales como marca, modelo, etc.

-   **Formato:** CSV delimitado por coma, codificado en UTF-8

-   **Rango temporal:** Listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **bien (string):** Tipo de bien. Son los activos de cualquier tipo, corporales o incorporales, muebles o inmuebles, tangibles o intangibles, y los documentos o instrumentos legales que acrediten la propiedad u otros derechos sobre dichos activos. Pueden ser aeronave, armas, automotores, buques, dinero, estupefacientes o inmuebles

-   **numero\_oficio (int):** Número correspondiente oficio mediante el cual la autoridad interviniente informa los bienes secuestrados y/ o decomisados en el marco de un proceso penal

-   **Juzgado/ Tribunal/ Fiscalía (string):** Nombre de la autoridad interviniente según corresponda

-   **tipo\_delito (string):** Describe el tipo de delito que se sustancia en el marco de un proceso penal

-   **medida (string):** Tipo de medida. Consiste en la medida adoptada por la autoridad interviniente en el marco del proceso penal. Pueden ser: afectado a medida cautelar – Embargo, afectado a otra medida, decomiso o secuestro

-   **fecha\_recepcion (date):** Fecha de recepción del oficio por el Registro Nacional de Bienes Secuestrados y Decomisados durante el Proceso Penal

<!-- -->

-   **fecha\_medida (string):** Fecha de la medida adoptada por la autoridad interviniente. No siempre es informada

-   **aeronave\_numero\_serie (string):** Número de serie de la aeronave. Sólo posee datos si el bien es aeronave

-   **aeronave\_matricula (string):** Número de matrícula de la aeronave. Sólo posee datos si el bien es aeronave

-   **aeronave\_marca (string):** Marca de la aeronave. Sólo posee datos si el bien es aeronave

<!-- -->

-   **aeronave\_modelo (string):** Modelo de la aeronave. Sólo posee datos si el bien es aeronave

-   **arma\_tipo (string):** Tipo de arma informada por la autoridad interviniente, la cual puede ser: Ametralladora, Carabina, Escopeta, Fusil, Pistola, Revolver, Subfusil, etc. Sólo posee datos si el bien es arma

-   **arma\_numero\_serie (string):** Número de serie del arma. Sólo posee datos si el bien es arma

-   **arma\_marca (string):** Marca del arma. Sólo posee datos si el bien es arma

-   **arma\_modelo (string):** Modelo del arma. Sólo posee datos si el bien es arma

-   **arma\_calibre (string):** Calibre del arma. Sólo posee datos si el bien es arma

<!-- -->

-   **automotor\_tipo (string):** Tipo de automotor informado por la autoridad interviniente, el cual puede ser: Automóvil, Camión, Camioneta, Casa Rodante, Colectivo, Jeep, Moto-vehículo, Trailer, etc. Sólo posee datos si el bien es automotor

-   **automotor\_dominio (string):** Número de dominio del automotor. Sólo posee datos si el bien es automotor

<!-- -->

-   **automotor\_marca (string):** Marca del automotor. Sólo posee datos si el bien es automotor

-   **automotor\_modelo (string):** Modelo del automotor. Sólo posee datos si el bien es automotor

-   **automotor\_color (string):** Color del automotor. Sólo posee datos si el bien es automotor

-   **automotor\_anio (string):** Año modelo del automotor. Sólo posee datos si el bien es automotor

-   **buque\_pais (string):** País al que pertenece el buque. Sólo posee datos si el bien es buque

-   **buque\_nombre (string):** Nombre del buque. Sólo posee datos si el bien es buque

-   **buque\_matricula (string):** Número de matrícula del buque. Sólo posee datos si el bien es buque

<!-- -->

-   **dinero\_moneda\_descripcion (string):** Tipo de moneda. Cualquier tipo de moneda informada por la autoridad interviniente, generalmente, dólares, pesos argentinos, reales, soles, etc. Sólo posee datos si el bien es dinero

<!-- -->

-   **dinero\_cantidad (string):** Monto en la moneda especificada. Sólo posee datos si el bien es dinero

<!-- -->

-   **estupefaciente\_sustancia (string):** Tipo de sustancia psicotrópica informada por la autoridad interviniente, la cual puede ser: Cocaína, Hojas de coca, Hongos, LSD, Marihuana, Éxtasis, de uso famacológico, etc. Sólo posee datos si el bien es estupefacientes

-   **estupefaciente\_cantidad (string):** Cantidad en gramos de la sustancia. Sólo posee datos si el bien es estupefacientes

<!-- -->

-   **localizacion (string):** **:** Lugar donde se encuentra el bien, ubicación física del bien

-   **provincia (string):** Nombre de provincial donde se encuentra localizado el bien

<span id="notas" class="anchor"></span>
