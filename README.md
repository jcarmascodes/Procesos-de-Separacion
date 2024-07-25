# **Fundamento Teórico**
La absorción es usada para separar mezclas de gases; remover impurezas, contaminantes o veneno de catalizadores, o la recuperación de sustancias valiosas.

Esto se logra por medio de transferencia de masa desde la fase gas a la líquida, cuando el proceso es inverso se le llamada desorción o agotamiento.

Esta operación unitaria es llevada a cabo en columna verticales de platos, las cuales permiten el contacto de fases en múltiples etapas a contracorriente.

![](https://www.filsonfilters.com/wp-content/uploads/2020/11/Figure-2-Absorption-tower.jpg)

Source: [Filson Filter](https://www.filsonfilters.com/absorption-tower)
## **Columna de Platos**
Uno de los métodos por el que se analizan este tipo de equipos es a través de un Método Gráfico, el cual consiste en dibujar 2 líneas:

* *Línea de Equilibrio*: Ajusta datos y-x de equilibrio de fases entre el soluto y el absorbente. Para mezclas muy diluidas, la Ley de Henry puede describir correctamente este equilibrio.
* *Línea de Operación*: Representa las condiciones de absorción y-x deseadas durante el funcionamiento del equipo. Donde sus puntos terminales representan las condiciones en el fondo (extremo superior de la línea de operación) y el domo de la torre (extremo inferior de la línea de operación). Para torres de absorción, esta línea debe estar por encima de la línea de equilibrio; en el caso de desorción es contrario.

Para el cálculo del número de platos, deben de dibujarse escalones ente las líneas de operación y equilibrio. Esto se logra comenzando el dibujo desde la cima de la torre y terminando en el fondo de esta [1].

![](https://www.cheresources.com/invision/uploads/images/articles/packcol6.gif)

Source: [Cheresources](http://www.cheresources.com/content/articles/separation-technology/packed-column-design#google_vignette)

# **VIDEO DEMOSTRATIVO DEL FUNCIONAMIENTO DE UNA COLUMNA DE ABSORCIÓN DE PLATOS**
Ejemplo del uso de aminas para la remoción de ácidos: https://youtu.be/qybIVRG20OA?si=mzSCQqdF9-0UrJrK
 
[![Alt text](https://img.youtube.com/vi/qybIVRG20OA/0.jpg)](https://www.youtube.com/watch?v=qybIVRG20OA)


**Ecuaciones de balance** El balance se hace sobre la especie de interés
*   *y*: Vapor
*   *x*: Líquido
*   *E*: Corrientes de Entrada
*   *S*: Corrientes de Salida
*   *Inertey*: Flujo gaseoso inerte que transporte el soluto
*   *Inertex*: Flujo líquido inerte que transporta el soluto recuperado
*   *H*: Constante de Henry


## $V_{E}\times y_{E}=N_{Ey}$


## $V_{E}\times (1-y_{E})=N_{InerteyE}$

## $N_{Ey}\times (Porcentaje_{Abs})=N_{xS}$

## $N_{Ey}\times (Porcentaje_{NoAbs})=N_{yS}$

## $N_{InerteyE}+N_{yS}=V_{S}$

## $N_{InertexE}+N_{xS}=L_{S}$

## $\frac {N_{yS}}{V_{S}}=y_{S}$

## $\frac {N_{xS}}{L_{S}}=x_{S}$

**Línea de Operación**
## $y=\frac{L_{S}}{V_{E}}x+y_{S}+\frac{L_{S}}{V_{E}}x_{E}$

**Línea de Equilibrio**
##  $P_{T}y=Hx$

## **Columnas Empacadas**
Otro modelo que es común encontrar es el de las columnas empacadas. Las columnas empacadas están rellenas de un material barato e inerte como puede ser la porcelana, arcilla, metal o plásticos, los cuales suelen acomodarse de manera aleatoria; a cada empaque se le asocia un determinado factor de empaquetamiento.

![](https://media.cheggcdn.com/media/064/064e565c-0e30-4c92-b257-45ac94346579/phpeCfbon)

Source: [Chegg](https://www.chegg.com/homework-help/questions-and-answers/1-lecture-23-40-points-ammonia-absorbed-air-countercurrent-contact-water-tower-packed-2-in-q81315974)

Durante el dimensionamiento de esta clase de equipos debe tomarse en cuenta: 
* *La caída de presión*: La caída de presión de la columna no debe ser superior a 2 in H2O/ft para factores de empaquetamiento (Fp) superiores a 60, por otro lado para Fp inferiores debe usarse la siguiente ecuación:
 ## $\Delta P_{flood}=0.115F_{p}^{0.7}$
 Para determinar la caída de presión debe de leerse un diagrama que se ilustra en el ejemplo de Torre de Absorción empacada, el cual se lee con ayuda del factor de capacidad para obtener la velocidad superficial:
 ## $C_{s}=u_{0} \sqrt{\rho_{y}/(\rho_{x}-\rho_{y})}$ 

 En base a ello puede calcularse el diámetro de la torre.

 Para el cálculo de la altura de la torre se usa la ecuación: 
 ## $Z_{T}=H_{y}N_{y}$
 Donde:
 * *H*: Altura de la unidad de transferencia: Se calcula a través de coeficientes de transferencia de masa, donde K es la constante de la Ley de Henry, V y L los flujos de vapor y líquido.
 ## $H_{OG}=H_{G}+(KV/L)H_{L}$
 * *N*: Número de unidades de transferencia: Estas representan el número de etapas teóricas para lograr la separación.
   * *yb*: Concentración de soluto en la corriente de vapor de entrada
   * *yT*: Concentración de soluto en la corriente de vapor de salida
   * *ybeq*: Concentración de soluto al equilibrio en la corriente de vapor de entrada
   * *yTeq*: Concentración de soluto al equilibrio en la corriente de vapor de salida

# $\frac{y_{b}-y_{T}}{\frac{(y_{b}-y_{beq})-(y_{T}-y_{Teq})}{\ln((y_{b}-y_{beq})-(y_{T}-y_{Teq}))}}$

Para los coeficientes de transferencia de masa se requieren algunos conceptos y fórmulas: 
* *Retención de líquido*: Es una medida de cuánto líquido queda retenido en una columna:
## $h_{L}=(12\frac{N_{FrL}}{N_{ReL}})^{1/3}(\frac{a_{h}}{a})^{2/3}$ 
Esta expresión requiere del número de Reynolds y el número de Froude del líquido. Además, requiere de la siguiente correlación empírica propuesta por Billet y Schultes.
## $a_{h}/a=C_{h}N_{ReL}^{0.15}N_{FrL}^{0.1}$ para $N_{ReL} < 5$
## $a_{h}/a=0.85C_{h}N_{ReL}^{0.25}N_{FrL}^{0.1}$ para $N_{ReL} >= 5$
* *Altura de la unidad de transferencia de líquido*: La fórmula es una correlación empírica propuesta por Billet y Schultes.
## $H_{L}=\frac{1}{C_{L}}(\frac{1}{12})^{1/6}(\frac{4h_{L}\epsilon}{D_{L}au_{L}})^{1/2}\frac{u_{L}}{a}(\frac{a}{a_{Ph}})$

* *Altura de la unidad de transferencia de vapor*: La fórmula es una correlación empírica propuesta por Billet y Schultes, la cual requiere del número de Reynolds del vapor y el número de Schmidt del vapor; así como el número de Reynolds, el número de Weber y el número de Froude del líquido y el diámetro hidráulico. 
## $H_{G}=\frac{1}{C_{V}}(\epsilon-h_{L})^{1/2}(\frac{4\epsilon}{a^{4}})^{1/2}(N_{ReV})^{-3/4}(N_{ScV})^{-1/3}(\frac{u_{V}a}{D_{G}a_{Ph}})$
Adicionalmente, se requiere de una correlación empírica: 
## $\frac{a_{Ph}}{a}=1.5(aD_{H})^{-1/2}(N_{ReLh})^{-0.2}(N_{WeLh})^{0.75}(N_{FrLh})^{-0.45}$

![](https://epcmholdings.com/wp-content/uploads/2022/08/Packed-column-schematic-e1659925358307-1024x643.png)

Source: [EPCM Holdings](https://epcmholdings.com/absorption-column-types-and-designing-considerations/)



**FUENTE**

[1] Seader S.D. , Henley E. , Roper K. (2011) *Separation Process Principles: Chemical and Biochemical Operations* 3erd edition,  John & Wiley Sons USA
