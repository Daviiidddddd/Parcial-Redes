# Parcial Redes De Computación

## David Castellanos, Jeancarlo Rodriguez y Andrés Torres
En este repositorio, se encuentran respondidas las preguntas correspondientes al parcial del primer corte de la materia, dividido por puntos para mayor comprensión

## Preguntas y Respuestas

## Punto 1

### 1. ¿Cómo contribuye la Transformada de Fourier al análisis de señales en la capa física?
La **Transformada de Fourier (TF)** es una herramienta matemática fundamental en el análisis de señales en la capa física del modelo OSI, ya que permite convertir una señal en el **dominio del tiempo** a su representación en el **dominio de la frecuencia**. Esto es esencial para entender la composición espectral de una señal, identificar componentes de ruido y evaluar el desempeño del canal de comunicación.

#### Aplicaciones en el análisis de señales:
1. **Análisis del espectro de la señal y ancho de banda**  
   La TF permite descomponer cualquier señal en una combinación de senoidales con diferentes frecuencias, lo que facilita la identificación del **ancho de banda necesario** para la transmisión y el diseño de filtros para mejorar la calidad de la señal.

2. **Detección y mitigación de ruido e interferencias**  
   En el dominio de la frecuencia, el ruido y las interferencias se manifiestan como componentes espectrales adicionales. La TF permite identificarlos y diseñar **filtros pasa-banda** o **pasa-bajo** para minimizar estos efectos y mejorar la calidad de la transmisión.

---

### 2. Señales compuestas y espectro de frecuencias
Si la señal transmitida es la suma de tres sinusoides con frecuencias \( f_1 \), \( f_2 \) y \( f_3 \), su expresión matemática en el dominio del tiempo sería:

\[
s(t) = A_1 \cos(2\pi f_1 t) + A_2 \cos(2\pi f_2 t) + A_3 \cos(2\pi f_3 t)
\]

Al aplicar la **Transformada de Fourier**, se obtiene su representación en el dominio de la frecuencia, que se vería como **tres picos** ubicados en \( f_1 \), \( f_2 \) y \( f_3 \), cada uno con su respectiva amplitud \( A_1 \), \( A_2 \) y \( A_3 \).

#### Interpretación:
- En el **dominio del tiempo**, la señal es una combinación de oscilaciones, lo que puede hacer que parezca compleja.
- En el **dominio de la frecuencia**, la señal se representa de manera más simple, con tres picos en las frecuencias \( f_1 \), \( f_2 \) y \( f_3 \), lo que facilita su análisis y procesamiento.

#### Representación gráfica:
- **Eje X:** frecuencia \( f \)
- **Eje Y:** amplitud de cada componente
- **Tres picos** en \( f_1 \), \( f_2 \) y \( f_3 \), reflejando que la señal está compuesta por estas frecuencias fundamentales.

Esta representación es clave para el diseño de filtros y la optimización del ancho de banda en redes de comunicación.

Conclusión

La Transformada de Fourier es una herramienta esencial en el análisis de señales en la capa física de las redes de comunicación. Permite entender cómo se comportan las señales en el dominio de la frecuencia, identificar interferencias y diseñar estrategias para mejorar la transmisión de datos. Su uso es fundamental en tecnologías como modulación de señales, codificación digital, procesamiento de audio y video, y diseño de circuitos de telecomunicaciones.

Además, la Transformada de Fourier es la base de muchas otras técnicas avanzadas, como la Transformada Rápida de Fourier (FFT), que optimiza los cálculos y permite su implementación eficiente en hardware y software. En un entorno de redes de datos, comprender y aplicar esta herramienta puede marcar la diferencia en la calidad y eficiencia de la comunicación digital.

