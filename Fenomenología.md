# IACTs (Imaging Atmospheric Cherenkov Telescopes) 
## Aceleradores Cósmicos No Térmicos
La radiación proveniente de fenómenos causados por aceleradores no térmicos, como remanentes de supernova, púlsares,
agujeros negros, no es térmica, sino que proviene de partículas cargadas aceleradas a velocidades relativistas. A diferencia de otros objetos,
cuya emisión sigue la curva de campana descrita por el modelo de cuerpo negro, estos objetos emiten un espectro de Ley de Potencias $(dN/dE \propto E^\Gamma)$.
Esta característica indica que no hay equilibrio térmico en el haz; en contraste, hay un mecanismo inyectando energía continuamente a las partículas.
 ## Aceleración de Fermi de Primer Orden
  Las partículas adquieren altas energías a través de la aceleración de Fermi de primer orden.
  - Choque: la explosión cósmica envía una onda de choque supersónica al medio interestelar.
  - Reborte Magnético: 
 
(Continuar con esto después)

## Direccionalidad del haz

### Rigidez magnética
La rigidez magnética es una cantidad física que cuantifica la resistencia de una partícula cargada a ser desviada por un campo magnético $B$, y se deduce a partir de la fuerza de Lorentz.

$$\vec{F} = q(\vec{v} \times \vec{B})$$

Donde: 
- $q$ es la carga eléctrica de la partícula.
- $\vec{v}$ es el vector velocidad.
- $\vec{B}$ es el vector campo magnético.

  Al considerar una partícula incidente en un campo magnético uniforme, cuya velocidad descrita por $\vec{v}$ es perpendicular a las líneas de campo ($\vec{v} \perp \vec{B}$), se tiene que:

  $$F = qvB\sin(90^\circ) = qvB$$

  ### Equilibrio con Fuerza Centrípeta
  Como la fuerza magnética es siempre perpendicular a la velocidad, no realiza trabajo (no cambia la energía cinética ni la rapidez $|\vec{v}|$), solo cambia la dirección. Esto genera un Movimiento Circular Uniforme.

  Por la Segunda Ley de Newton, esta fuerza actúa como fuerza centrípeta:

  $$F_{Lorentz} = F_{centripeta}$$

  $$qvB = \dfrac{mv^2}{\rho}$$

Donde:
- $m$ es la masa de la partícula (masa relativista $\gamma m_0$ si la velocidad es alta).
- $\rho$ (rho) es el radio de curvatura de la trayectoria.

  Ahora, agrupando las propiedades intrínsecas del campo a un lado de la ecuación, y las propiedades de la partícula al otro lado.
  
$$qB = \frac{mv}{\rho}$$

$$B\rho = \frac{mv}{q}$$

Donde $mv=p$.

$$B\rho = \frac{p}{q}$$

Siendo $B\rho$ la rigidez magnética $R$. 

$$R \equiv B\rho = \frac{p}{q}$$

De esta manera, la ecuación indica que el producto entre el campo magnético y el radio de giro es equivalente al momento de la partícula dividido por su carga. La carga $q$ se sustituye en términos del número $Z$ y la carga elemental $e$, tal que $q=Ze$:

$$R = \frac{p}{Ze}$$

La forma matemática de partículas relativistas se logra al multiplicar por $\frac{c}{c}$ (un "uno" conveniente):

$$R = \frac{pc}{Zec}$$

Para obtener unidades de energía, con base en que el interés es calcular el potencial equivalente que guía a la partícula:

$$R [Voltios] = \frac{pc [eV]}{Ze [e]}$$

### Fotones Gamma

Los rayos cósmicos, conformados por partículas cargadas, se caracterizan por un valor $Z \ge 1$, lo cual implica que la rigidez magnética de estas partículas es finita. Al interactuar con los campos magnéticos galácticos ($B$), su trayectoria se curva y se pierde información de su origen.

Por su parte, los rayos gamma no son desviados por campos magnéticos en el espacio, debido a que su carga eléctrica neta es nula $q=0$. Matemáticamente:

$$R = \frac{pc}{Ze}$$

Si $e=0$, la rigidez del fotón es infinita ($R \to \infty$). Una partícula cuya rigidez es infinita no puede curvarse bajo la acción de ningún campo magnético finito.

(Se puede explicar en términos de:

$$\frac{d\vec{p}_{\gamma}}{dt} = 0 \cdot (\vec{c} \times \vec{B}) = 0$$

Este resultado se puede escribir en términos de una geodésica nula en el espacio de Minkowski.)

## Interacción Colisional Atmosférica

- **Calorímetro Atmosférico:** la atmósfera se comporta como un medio denso para partícula de alta energía. Está caracterizada por su longitud de radiación ($X_0 \approx 37g\cm^2$), la cual es una medida de "cuánta materia" (en este caso, aire) debe atravesar una partícula de alta energía antes de interactuar. Para un fotón, es $7/9$ de la distancia media recorrida antes de convertirse en un par electrón-positrón ($e^+ e^-$).
La longitud de radiación $X_0$ está dada en unidades de $g\cm^2$, debido a la dependencia del aire con la altura; esta convención facilita ignorar la expansión del gas y considerar únicamente la cantidad de átomos golpeados por la partícula de alta energía.

- **Cascada Atmosférica Extensa** (EAS)
Cuando un fotón gamma de muy alta energía (VHE, E > 30 GeV) penetra la atmósfera, interactúa con el campo eléctrico de un núcleo atómico (N). Este proceso transforma la energía del fotón en materia, a la luz
del fenómeno de producción de pares. 

$$\gamma + N \rightarrow e^+ + e^- + N$$

(Hacer un refinamiento téorico de todo esto.)
