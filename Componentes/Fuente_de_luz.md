# Fenomenología del haz incidente
 Debido a que el haz que interactúa con el telescopio no es un haz colimado simple, sino una superposición compleja de frentes de onda,
 es importante caracterizarlo en términos difractivos.

 ## Geometría de Emisión
 ### Morfología del Cono Cherenkov
Los pares resultantes ($e^\pm$) en la cascada, emiten en un cono de luz con ángulo de apertura $\theta_c$ respecto a su trayectoria.
El valor del ángulo está determinado por el índice de refracción del aire $n$, el cual depende a su vez de la altura $h$, es decir, de la densidad atmosférica; además, depende de la velocidad relativista normalizada de las partículas dentro de la cascada atmosférica ($e^\pm$).

$$\cos \theta_c(h) = \frac{1}{\beta n(h)}$$ donde $$\beta = \frac{v}{c}$$

La dependencia de $\theta_c$ con $h$ implica que el haz de luz no es un cono perfecto, sino una estructura cónica "anidada" donde la luz generada a mayor altura llega más enfocada cerca del eje de la cascada, mientras que la luz generada a menor altura sufre una mayor dispersión (A 10 km de altura, el aire es menos denso ($n \approx 1.0001$), resultando en un cono más cerrado ($\theta_c \approx 0.7^\circ$). Al nivel del mar ($n \approx 1.0003$), el cono se abre hasta $\theta_c \approx 1.3^\circ$) (Cherenkov light imaging in astroparticle physics (pdf 7650)).

En general, ambos grupos de fotones tienden a caer a la misma distancia radial respecto al núcleo de impacto ($\approx 120m$), formando un anillo de alta densidad en el borde y, en el interior, de una densidad de fotones relativamente uniforme. 

### "Light Pool" (La Huella en el Espejo)
- **Densidad de Fotones (Frank-Tamm):**

$$\frac{dN}{dx} \approx 2\pi\alpha \left(1 - \frac{1}{\beta^2 n^2}\right) \int_{\lambda_1}^{\lambda_2} \frac{1}{\lambda^2} d\lambda$$

- **Densidad Lateral (LDF):** La distribución lateral de luz puede graficarse en función de cuántos fotones caen por metro cuadrado en función de la distancia al centro del impacto ($r$). Esta estructura puede diferenciarse de acuerdo a tres regímenes, los cuales se describirán a partir del siguiente marco de referencia determinado por el sistema coordenado:
  - *Origen ($O$):* Centro del espejo del telescopio.
  - *Eje Óptico* ($\hat{z}$): Vector unitario apuntando al cenit (vertical local).
  - *Eje de la Cascada* ($\hat{u}$): Vector unitario de la trayectoria de la partícula primaria. Se asume incidencia vertical para simplificar la demostración matemática ($\hat{u} = -\hat{z}$).
  - *Parámetro de Impacto* ($R$): Distancia perpendicular desde el eje de la cascada hasta el telescopio.
  - *Punto de Emisión* ($P$): Un punto arbitrario en la cascada a una altura $H$ sobre el suelo.

1 *Régimen de Simetría Azimutal* ($R\approx 0$)
El eje óptico del telescopio ($\hat{z}$) está alineado exactamente con el eje de la cascada ($\hat{u}$). La partícula se propaga paralela al eje óptico a velocidad $v \approx c(-\hat{z})$. Además, el fotón emitido con un vector de onda $k$ tal que el ángulo entre la trayectoria de la partícula y el fotón coincide con el ángulo del cono Cherenkov:

$$\theta_{inc} = \text{ángulo}(\vec{k}, \hat{z}) = \theta_c$$




