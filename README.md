

# **Extracción**

La extracción es una técnica para la remoción de uns soluto de una fase sólida o líquida por medio dele actuar de un solvente líquido. La extracción sólido-líquido es donde se remueve el soluto de un soluto insoluble; mientras que la extracción líquido-líquido es útil para recuperar el soluto de un sistema multicomponente por medio contacto con un líquido inmiscible por el que el soluto tiene afinidad. 

# **Extracción Sólido-Líquido**

El método más importante de extracción es el continuo a contracorriente por etapas. En este método, incluso si el sólido no se mueve, la concentración del líquido va aumentando de etapa a etapa.

En esto se asume que el sólido libre de soluto es completamente insoluble, donde: 
* *L* es el flujo de líquido retenido en la matriz del sólido.
* *V* es el sobreflujo.
* xa: Solución retenida en el sólido a la entrada.
* xb: Solución retenida en el sólido a la salida
* yb: Solvente fresco que entra al sistema.
* yb: Solución concentrada que sale del sistema.

La línea de operación es: 
## $y_{n+1}=(\frac{L_{n}}{V_{n+1}})x_{n}+\frac{V_{a}y_{a}}{V_{n+1}}$

Esta línea es preferible hacerla al ajustar una serie de puntos notables (el primero se calcula como *x1=ya*; el resto de los puntos notables deben quedar entre *x1* y *xb*), ya que *Vn+1* y Ln, varían considerablemente de punto a punto, esto de acuerdo a los datos experimentales de aceite en solución retenida por kg de sólido inerte. La relación de equilibrio es igual a *x=y*, ya que se supone que la cantidad de disolvente es suficiente para disolver el soluto y que el soluto no se adsorbe en el sólido inerte.

En el caso en el que la densidad y viscosidad de la solución no varía de punto a punto considerablmente, la línea de operación será recta, de lo contrario se curveará.

 ![](https://ars.els-cdn.com/content/image/3-s2.0-B9780123725066000046-f14-04-9780123725066.gif)

Source: [ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/B9780123725066000046)

# **Extracción Líquido-Líquido**
En la extracción líquido-líquido, como en otras operaciones de separación, 2 fases deben ponerse en contacto para permitir una transferencia de masa adecuada. El problema de transferencia de masa se vuelve particularmente más complejo en los sistemas líquido-líquido, esto debido a diferencias de densidad y viscosidad entre ambas fases dificultan un mezclado y separación sencillos; por lo que debe de añadírsele en algunos casos energía mecánica par promover la transferencia de masa rápida.

Aquí aparecen 2 conceptos: 
* *Extracto*: Es la fracción de solvente más soluto
* *Refinado*: Es la fracción de la que el soluto ha sido removido.

## *Extracción de solutos diluidos*
Dado que muchas operaciones se hacen en contracorriente, muchos principios usados en destilación y absorción aplican en extracción.

En este tipo de extracciones, los cambios entre los flujos pueden ser despreciados, y se usa un coeficiente de distribución $K_{D}$; los cuales ayudan a definir un factor de extracción E. 
## $E=\frac{K_{D}V}{L}$
siendo la fracción de soluto remanente es: 

## $\frac{1}{1+E}$
y la fracción de soluto recuperado es: 
## $\frac{E}{1+E}$
Dado que es una extracción de un soluto diluido, se puede hacer una simplificación y usar las ecuaciones de Kremser.

## $N=\frac{ln[(y_{b}-y_{b}^{\*})/(y_{a}-y_{a}^{\*})]}{ln[(y_{b}-y_{a})/(y_{b}^{\*}-y_{a}^{\*})]}$
Especies con (\*) representan las concentraciones al equilibrio.

Para soluciones más concentradas, es recomendable usar datos de equilibrio obtenidos a partir de diagramas ternarios.

Para este tipo de problemas, pueden trazarse las etapas de equilibrio en el diagrama ternario, sin embargo una simplificación a través de un digrama de McCabe-Thiele en de la concentración del soluto en la fase del extracto y el refinado (este diagrama no muestra la concentración del solvente en el refinado o de la solución original en el extracto) ayuda a resolver el problema con relativa exactitud. 

Para la construcción de la línea de operación deben de considerarse la composición de los componentes menores para determinar los flujos de extracto y refinado, los cuales son relevantes para la construcción de la línea de operación. 

El diagrama McCabe-Thiele se construye a través de colocar la fracción másica del soluto en el extracto (y) en la ordenada y la fracción masa del soluto en el refinado (x) en la abscisa. La línea de operación se construye de forma análoga a la fórmula presentada para la extracción sólido-líquido; a partir de ahí se construyen las etapas de la manera ya conocida.

**FUENTE**

[1] McCabe W. , Smith J. , Harriott P. (2022) *Unit Operations of Chemical Engineering* 7th edition, McGraw-Hill India

