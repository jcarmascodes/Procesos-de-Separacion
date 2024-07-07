# **Fundamento Teórico**

En la destilación, se alimenta una mezcla de 2 o más componentes que se separan en 2 o más productos, donde comúnmente se habla de un destilado que sale por el domo de una columna y por los productos pesados que salen por el fondo de esta. 

Esta separación requiere: 
* Formar una segunda fase, de forma que el líquido y el vapor entren en contacto mientras fluyen a contracorriente en una columna empacada o de platos.
* Que los componentes de la mezcla tengan volatilidades diferentes.

La destilación es diferente a la absorción o desorción, ya que en esta operación unitaria, la fase vapor se crea por medios térmicos. 
La destilación es un proceso muy relevante y está presente desde la elaboración de bebidas alcohólicas hasta la separación del petróleo en diferentes fracciones. 

## **Destilación Flash**
La destilación flash consiste en vaporizar una determinada fracción de líquido, de manera que el vapor que salga del separador flash esté en equilibrio con el líquido que sale. En este equipo la presión es reducida a través de una válvula.

![](https://upload.wikimedia.org/wikipedia/commons/c/c4/Vap-Liq_Separator.png)

Source: [Wikipedia](https://en.wikipedia.org/wiki/Vapor%E2%80%93liquid_separator)

En la destilación flash se aprovecha el concepto de volatilidad relativa, que es una relación entre el líquido y el vapor.

## $K_{i}=\frac{y_{i}}{x_{i}}$
## $\alpha=\frac{K_{1}}{K_{2}}$
Donde las fracciones de líquido y vapor pueden relacionarse a través de las ecuaciones: 

## $y=\frac{\alpha x}{1+(\alpha-1)x}$

Las ecuaciones usadas en el cálculo de las composiciones del separador flash, son: 

* *A, B, C*: Son las constantes de Antoine
* *P**: Presión de vapor de un componente puro
* *PT*: Presión del separador flash
* *F*: Corriente de alimentación
* *V*: Corriente de vapor que sale del separador Flash
* *L*: Corriente de líquido que sale del separador Flash
* *y*: Fracción de vapor que sale del separador flash
* *x*: Fracción de líquido que sale del separador flash
* *Z*: Fracción de un componente que entra al separador flash

**Ley de Antoine**

  ## $\log_{10}(P*_{i})=A-\frac{B}{T+C}$
Para la Ley de Raoult
## $K_{i}=\frac{P*}{P_{T}}$

## $S_{0}=[\sum{Z_{i}K_{i}}]-1$

## $S_{1}=1-[\sum{\frac{Z_{i}}{K_{i}}}]$

**Condiciones de separación**
## $S_{1} < 0$ $S_{0} < 0$
Sólo se obtiene líquido
## $S_{1} > 0$ $S_{0} > 0$
Sólo se obtiene vapor
## $S_{1} < 0$ $S_{0} > 0$ 
Hay coexistencia líquido-vapor


**Cálculo de las composiciones**

## $S_{x}=\sum\frac{Z_{i}}{1+(V/F)(K_{i}-1)}$

## $S_{y}=\sum\frac{Z_{i}K_{i}}{1+(V/F)(K_{i}-1)}$
**Criterio de Convergencia**
## $S_{y}-S_{x} < S$
Siendo S la tolerancia del sistema

**Método Numérico: Newton-Raphson para estimar la relación V/F**


## $S^{'}=-\sum\frac{Z_{i}(K_{i}-1)^{2}}{[1+(V/F)(K_{i}-1)]^{2}}$


## $(V/F)_{nueva}=(V/F)-\frac{S}{S^{'}}$

**Ecuaciones de Balance**
 ## $V=(V/F)\times F$
## $L=F-V$

# **Método de McCabe-Thiele**
La destilación flash es usada como único método de separación si la volatilidad entre las especies de la mezcla es muy diferente; aunque en la mayoría de los casos es más común encontrar columnas de platos, los cuales funcionan como múltiples etapas de equilibrio para lograr una pureza determinada.
**Balances de Materia**
$\frac{Fz-Fx_{D}}{x_{B}-x_{D}}=B$
$D=F-B$

El método de McCabe-Thiele funciona en los siguientes casos si: 
* Los componentes tienen entalpías de vaporización similares y constantes.
* La energía liberada durante el mezclado es despreciable.
* La columna está aislada, de forma que la pérdida de energía es despreciable.
* La presión en la columna es uniforme.

  Estas suposiciones llevan a considerar un derrame molar constante en el vapor y líquido.
  
El equipo típico de destilación en columna consiste en: 
* *Plato de Alimentación*: El plato en el que se suministra la mezcla a destilar. 
* *Rehervidor*: El cual vaporiza parcialmente la mezcla que a este llega. Se encuentra en el fondo de la columna.
* *Reflujo*: Es una fracción del líquido destilado que es retornado a la columna, esto se logra a través de un condensador. Incrementa la pureza del producto final.
* *Zona de rectificación*: Zona por encima del plato de alimentación, ahí es donde se enriquece de el vapor de los componentes más volátiles.
* *Zona de agotamiento*: Zona por debajo del plato de alimentación, ahí es donde la corriente de líquido está compuesta en su mayor parte por los componentes menos volátiles. 

![](https://www.aiche.org/sites/default/files/images/cep/inline/2018-07-01-Feature/2018-07-01-Predict-Distillation-Tray-Efficiency/images/fig_01.png)

Source: [ChemicalEngineering World](https://chemicalengineeringworld.com/packed-column-versus-tray-column/#google_vignette)


En base a estas suposiciones se dibujan las líneas de operación de rectificación y agotamiento cuyas ecuaciones son: 

**Línea de Operación Zona Rectificación**
## $y_{N+1}=\frac{R_{D}}{R_{D}+1}x_{n}+\frac{x_{D}}{R_{D}+1}$


**Línea de Operación Zona de Agotamiento**
## $y=(\frac{V_{B}+1}{V_{B}})x-(\frac{1}{V_{B}})x_{B}$

**Condiciones de alimentación**
Las condiciones del flujo de alimentación influyen notoriamente en el plato por el que entrará la mezcla a separar. 
Todos los tipos de alimentación pueden ser caracterizados por medio del parámetro q, que se define como los moles del flujo líquido en la zona de agotamiento que son resultado de la corriente de alimentación [2].

**Cálculo de la condición de alimentación q**
* *q>1* Líquido frío
## $q=1+\frac{Cp_{L}(T_{b}-T_{F})}{\lambda}$
* *q=1* Líquido Saturado
* *0<q<1* Mezcla Líquido-Vapor (q es la fracción es líquida)
* *q=0* Vapor Saturado
* *q<0* Vapor Sobrecalentado
## $q=-\frac{Cp_{V}(T_{F}-T_{d})}{\lambda}$


**Línea de Alimentación**
## $y=-\frac{q}{1-q}x+\frac{x_{F}}{1-q}$


**Cálculo del Punto de Intersección entre Líneas de Operación**
## $x_{int}=\frac{Z(R+1)+x_{D}(q-1)}{q(R+1)-R(q-1)}$

**Cálculo de los flujos**
## $V_{B}=S\times B$

## $L_{D}=R\times D$

![](https://en.citizendium.org/wiki/images/thumb/8/84/McCabe-Thiele.png/325px-McCabe-Thiele.png)

Source: [Citizendium](https://en.citizendium.org/wiki/McCabe-Thiele_method)

# **VIDEO DEMOSTRATIVO DEL FUNCIONAMIENTO DE UNA COLUMNA DE DESTILACIÓN DE PLATOS**
Ejemplo del funcionamiento del equipo: https://www.youtube.com/watch?v=07MBppchxow
 
[![Alt text](https://img.youtube.com/vi/07MBppchxow/0.jpg)](https://www.youtube.com/watch?v=07MBppchxow)

# **VIDEO DEMOSTRATIVO DEL FUNCIONAMIENTO DE UN SEPARADOR FLASH**
Ejemplo del funcionamiento del equipo: https://www.youtube.com/watch?v=N3F41ndBfwY
[![Alt text](https://img.youtube.com/vi/N3F41ndBfwY/0.jpg)](https://www.youtube.com/watch?v=N3F41ndBfwY)

## **Destilación multicomponente Método Fenske-Underwood-Gilliland**

En la destilación multicomponente hay 3 o más componentes en la alimentación, y especificar la composición de uno de los componentes no define al resto; sin embargo si se intentan fijar *n-1* componentes para el destilado y los fondos es casi imposible satisfacer estas especificaciones con exactitud. Un incremento en el reflujo o en la cantidad de etapas podrían hacer una separación más fina y por coincidencia podría lograr la separación deseada. Por ello el diseñador generalmente selecciona 2 componentes cuya concentración en el destilado y en los fondos sea representativa de la separación lograda, a estos se les llama componentes clave. Al más volátil se le llama "Clave ligero" y se caracteriza por la letra L, mientras que el menos volátil se le llama "Clave pesado" y se caracteriza por la letra H. 

Una vez seleccionadas los componentes claves, el diseñador elige las fracciones de xL y xH bajo los siguientes criterios:
* El destilado debe de estar casi completamente comouesto por el Clave ligero si los 2 componentes seleccionados son los más volátiles; esto debido a que los componentes más pesados que el componente H no irán más allá del plato de alimentación.
* Si existen componentes más ligeros que el componente L, donde estos se recuperen íntegramente en el destilado.
* Si existen componentes más pesados que el componente H, estos recuperan íntegramente en los fondos.

La ecuación de Fenske aplica para la determinación del número mínimo de platos a una razón de reflujo infinita. Don de D, F, B hacen referencia a las composiciones del destilado del destilado, del plato de alimentación y en los fondos 
## $N_{min}=\frac{\ln[(x_{Di}/x_{Bi})/(x_{Dj}/x_{Bj})]}{\ln{\alpha_{ij}}}$
## $\alpha_{ij}=\sqrt[3]{\alpha_{Dij}\alpha_{Fij}\alpha_{Bij}}=\frac{\alpha_{LK}}{\alpha_{HK}}$

**FUENTE**

[1] McCabe W. , Smith J. , Harriott P. (2022) *Unit Operations of Chemical Engineering* 7th edition, McGraw-Hill India

[2] Seader S.D. , Henley E. , Roper K. (2011) *Separation Process Principles: Chemical and Biochemical Operations* 3erd edition,  John & Wiley Sons USA


