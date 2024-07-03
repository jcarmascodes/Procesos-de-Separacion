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







El equipo típico de destilación en columna consiste en: 
* *Plato de Alimentación*: El plato en el que se suministra la mezcla a destilar. 
* *Rehervidor*: El cual vaporiza parcialmente la mezcla que a este llega. Se encuentra en el fondo de la columna.
* *Reflujo*: Es una fracción del líquido destilado que es retornado a la columna, esto se logra a través de un condensador. Incrementa la pureza del producto final.
* *Zona de rectificación*: Zona por encima del plato de alimentación, ahí es donde se enriquece de el vapor de los componentes más volátiles.
* *Zona de agotamiento*: Zona por debajo del plato de alimentación, ahí es donde la corriente de líquido está compuesta en su mayor parte por los componentes menos volátiles. 

![](https://www.aiche.org/sites/default/files/images/cep/inline/2018-07-01-Feature/2018-07-01-Predict-Distillation-Tray-Efficiency/images/fig_01.png)

Source: [ChemicalEngineering World](https://chemicalengineeringworld.com/packed-column-versus-tray-column/#google_vignette)

