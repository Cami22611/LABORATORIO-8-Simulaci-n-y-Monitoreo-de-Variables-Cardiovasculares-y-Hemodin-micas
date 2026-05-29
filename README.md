# LABORATORIO 6: Simulación y monitoreo de variables cardiovasculares y hemodinámicas

## INTRODUCCIÓN
El monitoreo de signos vitales constituye una herramienta fundamental en el ámbito clínico, debido a que permite evaluar de forma continua variables fisiológicas asociadas al estado cardiovascular y respiratorio del paciente, favoreciendo la detección temprana de alteraciones que puedan comprometer su seguridad. Dentro de estos parámetros, la pulsioximetría permite estimar de manera no invasiva la saturación periférica de oxígeno y es ampliamente utilizada para identificar y vigilar estados de hipoxemia (Organización Panamericana de la Salud, 2020). En este contexto, el monitor de signos vitales uMEC 100 permite la medición y visualización de variables clínicas como SpO₂, frecuencia de pulso, frecuencia cardíaca y otros parámetros requeridos para la vigilancia del paciente (Mindray, 2023). Por su parte, el simulador Pronk OxSim OX-1 permite verificar funcionalmente sistemas de pulsioximetría mediante la simulación de valores definidos de saturación de oxígeno, frecuencia de pulso e índice de perfusión, incluyendo condiciones como bradicardia, taquicardia, hipoxemia y baja perfusión (Pronk Technologies, s.f.). Por ello, el uso conjunto del uMEC 100 y el OxSim OX-1 en la práctica de laboratorio permite relacionar el funcionamiento técnico del monitor con criterios de seguridad clínica, precisión de medición y activación de alarmas ante condiciones fisiológicas simuladas.
<img width="894" height="542" alt="image" src="https://github.com/user-attachments/assets/14320c88-6c72-4e90-a869-fb1259710aff" />
<p align="center">
  <strong>Figura 1.</strong> <em>Monitor de signos vitales Mindray uMEC100 utilizado para el monitoreo de variables fisiológicas como ECG, SpO₂, frecuencia cardiaca, temperatura y presión arterial no invasiva.</em>
</p>

<p align="center">
  <strong>Fuente:</strong> Mindray, página oficial del monitor de paciente uMEC 100/120/150.
</p>

<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/cdb0bacf-6df3-4a00-8c22-b2462c3a003d" />

<p align="center">
  <strong>Figura 2.</strong> <em>Simulador Pronk OxSim OX-1 empleado para generar señales ópticas de pulsioximetría y verificar la medición de SpO₂ y frecuencia cardiaca en el monitor uMEC100.</em>
</p>

<p align="center">
  <strong>Fuente:</strong> Pronk Technologies, fotogrfía tomada en el laboratorio.
</p>

## OBJETIVOS
### General 
Operar con el simulador Pronk OxSim (OX-1) y el monitor de signos vitales uMEC 100 para pruebas funcionales.
### Específicos
- Identificar los modos de operación de un simulador de parámetros hemodinámicos (Pronk OxSim).
- Verificar los límites de medición de un monitor de signos vitales mediante simulación de variables hemodinámicas.
- Interpretar variaciones en los parámetros hemodinámicos asociadas a estados fisiológicos y patológicos.

## SEGURIDAD EN EL LABORATORIO
- No encender o manipular equipos biomédicos sin la presencia del técnico. 
- Usar responsablemente los elementos de protección como bata, pantalón largo, cabello recogido, entre otros. 
- En caso de usar equipos de cómputo de la institución, no dejar sesiones iniciadas ni archivos guardados.
  
## PARTE A
a. ¿Cómo colocar al uMEC 100 en modo “monitor”?

Para colocar el uMEC 100 en modo “monitor”, primero se debe encender el equipo y esperar a que cargue la pantalla principal de monitoreo, posteriormente se debe verificar que el monitor no se encuentre en modo de espera, demostración o en alguna configuración especial que impida la visualización normal de los parámetros fisiológicos. Desde la pantalla principal, se selecciona la ventana del parámetro ECG o el área de la onda ECG para ingresar al menú de configuración. Allí se accede a la opción de filtro y se selecciona el modo Monitor, el cual está diseñado para la vigilancia rutinaria del paciente en condiciones normales de medición clínica. Este modo permite visualizar la señal de manera estable y adecuada para el seguimiento continuo, diferenciándose de otros modos como diagnóstico, cirugía o análisis ST, que se emplean en condiciones más específicas.

En el contexto de la práctica, después de configurar el monitor en modo de monitoreo normal, se conecta el sensor de SpO₂ del uMEC 100 al simulador Pronk OxSim OX-1. Luego se verifica que en la pantalla del monitor aparezcan los valores de saturación periférica de oxígeno, frecuencia de pulso y la onda pletismográfica. Esto permite confirmar que el equipo está recibiendo correctamente la señal simulada y que se encuentra listo para realizar las pruebas funcionales.

b. ¿Qué tipo de parámetros o variables fisiológicas pueden simularse con el Pronk OxSim OX-1? Explique cada uno.

El Pronk OxSim OX-1 es un simulador óptico de pulsioximetría utilizado para verificar el funcionamiento de monitores de signos vitales y pulsioxímetros. Su función principal es generar señales controladas que imitan la respuesta de un paciente ante diferentes condiciones fisiológicas relacionadas con la oxigenación y la frecuencia de pulso. Este equipo permite evaluar si el monitor interpreta correctamente los valores simulados y si responde de manera adecuada ante situaciones normales o alteradas.

Una de las principales variables que puede simular el OxSim OX-1 es la saturación periférica de oxígeno, conocida como SpO₂. Esta variable representa el porcentaje de hemoglobina oxigenada en la sangre arterial periférica. La simulación de distintos valores de SpO₂ permite comprobar si el monitor identifica correctamente condiciones de saturación normal, hipoxemia o saturaciones elevadas.

Otra variable simulada es la frecuencia de pulso, expresada en latidos por minuto. Esta corresponde a la frecuencia detectada por el monitor a partir de la señal pletismográfica. Mediante esta variable es posible simular condiciones como bradicardia, cuando la frecuencia es baja; frecuencia normal, cuando se encuentra dentro de rangos fisiológicos esperados; y taquicardia, cuando la frecuencia es elevada.

El OxSim OX-1 también permite simular condiciones relacionadas con el índice de perfusión, el cual se asocia con la intensidad de la señal pulsátil detectada por el sensor. Una perfusión adecuada favorece lecturas estables de SpO₂ y frecuencia de pulso, mientras que una baja perfusión puede generar señales débiles, lecturas inestables o dificultad para que el monitor detecte correctamente los parámetros.

Además, el simulador genera una onda pletismográfica, que corresponde a la representación gráfica de los cambios pulsátiles asociados al flujo sanguíneo periférico. Aunque no se considera un parámetro numérico independiente, esta onda es importante porque permite observar visualmente la calidad de la señal, su amplitud, estabilidad y posible distorsión durante las pruebas.

c. En el ámbito clínico, ¿cuáles son las tolerancias o errores máximos permitidos para cada parámetro fisiológico mencionado en la parte b?

En el ámbito clínico, los errores máximos permitidos permiten establecer si la diferencia entre el valor simulado y el valor mostrado por el monitor se encuentra dentro de un margen aceptable. Para la medición de SpO₂ en pacientes adultos y pediátricos, se considera una tolerancia aproximada de ±2 % en el rango de 70 % a 100 %. En pacientes neonatales, la tolerancia puede ser de ±3 % en ese mismo rango. Para valores de SpO₂ inferiores al 70 %, la exactitud generalmente no se especifica, por lo que estos valores deben interpretarse con mayor precaución.

En el caso de la frecuencia de pulso obtenida desde el módulo de SpO₂, la tolerancia reportada es de aproximadamente ±3 bpm dentro del rango de medición del monitor. Este criterio es el más adecuado para la práctica, ya que el OxSim OX-1 se conecta al sensor de pulsioximetría y no a una entrada ECG. Por esta razón, la comparación debe realizarse entre el valor de frecuencia de pulso simulado y el valor mostrado por el monitor.

Para el índice de perfusión y la onda pletismográfica no se establece un error máximo permitido como valor clínico universal, estos parámetros se analizan principalmente como indicadores de calidad de señal. En el caso de la perfusión, se observa si la señal es adecuada, débil o inestable. En el caso de la onda pletismográfica, se evalúa su forma, amplitud, continuidad y posible distorsión.
## Tabla de tolerancias o errores máximos permitidos

| Parámetro fisiológico | Tolerancia o error máximo permitido | Observación |
|---|---:|---|
| SpO₂ en adulto/pediátrico | ±2 % entre 70 % y 100 % | Por debajo de 70 %, la exactitud no está especificada. |
| SpO₂ en neonato | ±3 % entre 70 % y 100 % | Aplica para medición neonatal. |
| Frecuencia de pulso desde SpO₂ | ±3 bpm | Es el criterio más aplicable para esta práctica, ya que el OxSim se conecta al sensor de SpO₂. |
| Índice de perfusión | No tiene EMP clínico universal | Se interpreta como indicador de calidad de señal. |
| Onda pletismográfica | No tiene EMP numérico | Se evalúa cualitativamente por forma, amplitud y estabilidad. |

## PARTE B
- 
| Prueba | Alarma evaluada | Límite configurado en el uMEC100 | Valor simulado en OxSim | ¿Alarma activa? | Tiempo de respuesta |
|---|---|---|---|---|---|
| 1 | Frecuencia cardiaca baja / bradicardia | Límite inferior de FC: 50 bpm | FC: 40 bpm / SpO₂: 95% | Sí | 5 s |
| 2 | SpO₂ baja | Límite inferior de SpO₂: 90% | FC: 80 bpm / SpO₂: 85% | Sí | 5 s |
| 3 | SpO₂ alta | Límite superior de SpO₂: 97% | FC: 80 bpm / SpO₂: 99% | Sí | 5 s |
| 4 | Frecuencia cardiaca alta / taquicardia | Límite superior de FC: 120 bpm | FC: 140 bpm / SpO₂: 98% | Sí | 5 s |

De acuerdo con la verificación realizada, el monitor uMEC100 activó correctamente las alarmas cuando los valores simulados en el OxSim superaron los límites configurados. En la prueba de bradicardia, al simular una frecuencia cardiaca de 40 bpm, el valor quedó por debajo del límite inferior establecido, por lo que se activó la alarma correspondiente. Para la condición normal, con una frecuencia cardiaca de 80 bpm, el equipo se mantuvo dentro del rango esperado. Finalmente, en la prueba de taquicardia, al simular una frecuencia cardiaca de 140 bpm, el valor superó el límite superior configurado y se generó la alarma.

En las pruebas relacionadas con la saturación de oxígeno, se observó que el monitor respondió adecuadamente ante valores fuera del rango configurado. Cuando se simuló una SpO₂ baja, menor al límite inferior establecido, el equipo activó la alarma visual y sonora. De igual manera, cuando se simuló una SpO₂ alta, superior al límite máximo permitido, también se presentó activación de alarma. En general, el comportamiento del monitor fue coherente con los valores programados en el simulador, lo que indica que el sistema de alarmas respondió de forma adecuada durante la prueba.

- ### Simulación de paciente bradicárdico

Se configuró el simulador OxSim para representar un paciente bradicárdico. En la evidencia fotográfica registrada, el monitor uMEC100 mostró una frecuencia cardiaca de **40 bpm** y una saturación periférica de oxígeno de **95%**, valores que coincidieron con la condición simulada.
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/3313f509-56f5-459a-812d-8f4c58360785" />

<p align="center">
  <strong>Figura 4.</strong> <em>Simulación de paciente bradicárdico en el monitor uMEC100, con frecuencia cardiaca de 40 bpm y SpO₂ de 95%.</em>
</p>

<p align="center">
  <strong>Fuente:</strong> Fotografía tomada en el laboratorio.
</p>

### Cálculo de errores

| Variable | Valor simulado en OxSim | Valor mostrado en uMEC100 | Error absoluto | Error porcentual |
|---|---:|---:|---:|---:|
| SpO₂ | 95% | 95% | 0% | 0% |
| Frecuencia cardiaca | 40 bpm | 40 bpm | 0 bpm | 0% |

Cálculos realizados:

- Error absoluto SpO₂ = \|95 - 95\| = 0%
- Error porcentual SpO₂ = (0 / 95) × 100 = 0%
- Error absoluto FC = \|40 - 40\| = 0 bpm
- Error porcentual FC = (0 / 40) × 100 = 0%


Los resultados indican que el monitor uMEC100 registró correctamente la condición simulada de bradicardia. No se evidenció diferencia entre los valores configurados en el OxSim y los valores mostrados en pantalla, por lo que el error absoluto y el error porcentual fueron nulos para ambas variables. Esto demuestra una adecuada correspondencia entre la señal simulada y la lectura del monitor en esta condición.

- ### Registro de la forma de onda fotopletismográfica

Se observó y registró la forma de onda de la señal fotopletismográfica mostrada en la pantalla del uMEC100. La señal presentó un comportamiento **pulsátil, periódico y repetitivo**, característico de una onda de pulsioximetría.
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/0eeebabf-97f4-415c-92e6-88381f50ed0f" />

<p align="center">
  <strong>Figura 5.</strong> <em>Forma de onda fotopletismográfica observada en el monitor uMEC100 durante una condición de frecuencia cardiaca de 80 bpm y SpO₂ de 85%.</em>
</p>

<p align="center">
  <strong>Fuente:</strong> Fotografía tomada en el laboratorio.
</p>

En la imagen se observa una frecuencia cardiaca de  **80 bpm** y una SpO₂ de **85%**. La onda fotopletismográfica presenta pulsos regulares, con una amplitud visible y una morfología repetitiva. Esto indica que el sensor estaba detectando adecuadamente la señal óptica generada por el simulador.

La forma de onda fotopletismográfica representa los cambios pulsátiles del volumen sanguíneo periférico detectados por el sensor de SpO₂. Por ello, su frecuencia guarda relación directa con la frecuencia cardiaca, mientras que su amplitud y definición dependen de la calidad de la perfusión y de la señal recibida por el monitor.

En esta condición particular, la onda conserva una estructura clara y periódica, lo que permite al monitor calcular correctamente la frecuencia cardiaca y la saturación de oxígeno.

- ### Configuración del límite inferior de alarma de SpO₂ en 90%

En el monitor uMEC100 se ingresó al menú de configuración de alarmas para ajustar los límites de saturación periférica de oxígeno. En la evidencia fotográfica se observa que el límite inferior de alarma para SpO₂ fue configurado en **90%**.

<img width="1600" height="1204" alt="image" src="https://github.com/user-attachments/assets/15805c03-60a4-4c16-85e9-8bbdeea5f7fd" />
<p align="center">
  <strong>Figura 6.</strong> <em>Configuración del límite inferior de alarma de SpO₂ en 90% en el monitor uMEC100.</em>
</p>

<p align="center">
  <strong>Fuente:</strong> Fotografía tomada en el laboratorio.
</p>

En la configuración observada, el parámetro SpO₂ quedó activo con un límite alto de **100%** y un límite bajo de **90%**, con prioridad media. Esta configuración permitió preparar el equipo para detectar de manera automática una condición de saturación baja cuando el valor medido descendiera por debajo del umbral establecido.

Este ajuste es importante porque define el punto a partir del cual el monitor activa la alarma visual y sonora, permitiendo advertir una posible condición de hipoxemia simulada.

- ### Simulación de SpO₂ baja 

Posteriormente, el simulador OxSim se ajustó para representar una condición de **frecuencia cardiaca de 80 bpm** y **SpO₂ de 85%**. Después de la simulación, se verificó en el uMEC100 la activación de la alarma correspondiente a SpO₂ baja, dado que el valor mostrado quedó por debajo del límite inferior configurado de 90%.


<img width="1600" height="1131" alt="image" src="https://github.com/user-attachments/assets/1238936f-5ad8-4295-9efa-c0a9972572f1" />

<p align="center">
  <strong>Figura 6.</strong> <em>Configuración del límite inferior de alarma de SpO₂ en 90% en el monitor uMEC100.</em>
</p>

<p align="center">
  <strong>Fuente:</strong> Fotografía tomada en el laboratorio.
</p>
### Cálculo de errores

| Variable | Valor simulado en OxSim | Valor mostrado en uMEC100 | Error absoluto | Error porcentual |
|---|---:|---:|---:|---:|
| SpO₂ | 85% | 85% | 0% | 0% |
| Frecuencia cardiaca | 80 bpm | 80 bpm | 0 bpm | 0% |

Cálculos realizados:

- Error absoluto SpO₂ = \|85 - 85\| = 0%
- Error porcentual SpO₂ = (0 / 85) × 100 = 0%
- Error absoluto FC = \|80 - 80\| = 0 bpm
- Error porcentual FC = (0 / 80) × 100 = 0%


El monitor uMEC100 detectó adecuadamente la condición de SpO₂ baja. En la pantalla se visualiza la alarma **“SpO₂ bajo < 90”**, lo cual confirma que el equipo respondió correctamente al superar el umbral configurado. Además, los valores mostrados por el monitor coincidieron con los valores simulados por el OxSim, por lo que no se presentó error ni en frecuencia cardiaca ni en saturación de oxígeno.

- ### Configuración del límite superior de alarma de SpO₂ en 97%

Posteriormente, se modificó la configuración del monitor para ajustar el límite superior de alarma de SpO₂. En la evidencia se observa que el valor alto fue configurado en **97%**, mientras que el valor bajo permaneció en **90%**.

<img width="1600" height="1228" alt="image" src="https://github.com/user-attachments/assets/45c98a83-439e-4a46-802b-15a02a863520" />
<p align="center">
  <strong>Figura 8.</strong> <em>Configuración del límite superior de alarma de SpO₂ en 97% y del límite inferior en 90% en el monitor uMEC100.</em>
</p>

<p align="center">
  <strong>Fuente:</strong> Fotografía tomada en el laboratorio.
</p>


El establecimiento del límite superior en 97% permitió preparar el monitor para identificar una condición de saturación elevada. En la configuración se observa que la alarma de SpO₂ permaneció activa, con prioridad media. Este ajuste es el que hace posible que, al registrarse un valor superior a 97%, el equipo emita la alarma correspondiente de saturación alta.

- ### Verificación de alarma por SpO₂ alta 

Con el límite superior ya configurado en 97%, se verificó la activación de la alarma de SpO₂ alta. En la evidencia fotográfica disponible, el monitor mostró una **frecuencia cardiaca de 140 bpm** y una **SpO₂ de 99%**, por lo cual se activó la alarma visual de saturación alta.

<img width="1600" height="1127" alt="image" src="https://github.com/user-attachments/assets/b584304f-a450-450a-86ad-02446ced9cdd" />
<p align="center">
  <strong>Figura 9.</strong> <em>Activación de alarma por SpO₂ alta en el monitor uMEC100, con SpO₂ de 99% y frecuencia cardiaca de 140 bpm.</em>
</p>

<p align="center">
  <strong>Fuente:</strong> Fotografía tomada en el laboratorio.
</p>

### Cálculo de errores

| Variable | Valor simulado en OxSim | Valor mostrado en uMEC100 | Error absoluto | Error porcentual |
|---|---:|---:|---:|---:|
| SpO₂ | 99% | 99% | 0% | 0% |
| Frecuencia cardiaca | 140 bpm | 140 bpm | 0 bpm | 0% |

Cálculos realizados:

- Error absoluto SpO₂ = \|99 - 99\| = 0%
- Error porcentual SpO₂ = (0 / 99) × 100 = 0%
- Error absoluto FC = \|140 - 140\| = 0 bpm
- Error porcentual FC = (0 / 140) × 100 = 0%


El monitor uMEC100 activó correctamente la alarma de SpO₂ alta, ya que el valor registrado de **99%** superó el límite superior configurado de **97%**. Los valores mostrados en pantalla coincidieron con los considerados para el análisis, por lo que no se presentó error absoluto ni porcentual.

En cuanto a la onda fotopletismográfica, se observa una señal más rápida debido a la mayor frecuencia cardiaca. Aun así, la onda conserva periodicidad y definición, por lo que no se aprecia una distorsión severa en la imagen registrada.

- ### Simulación de taquicardia 

Finalmente, se registró una condición de taquicardia en el monitor uMEC100. En la evidencia fotográfica se observa una **frecuencia cardiaca de 140 bpm** y una **SpO₂ de 98%**, junto con la activación de la alarma de frecuencia cardiaca elevada.


<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/48599bcd-dc4e-4d46-8a00-1c021713d264" />
<p align="center">
  <strong>Figura 10.</strong> <em>Simulación de taquicardia en el monitor uMEC100, con frecuencia cardiaca de 140 bpm y SpO₂ de 98%.</em>
</p>

<p align="center">
  <strong>Fuente:</strong> Fotografía tomada en el laboratorio.
</p>

### Cálculo de errores

| Variable | Valor simulado en OxSim | Valor mostrado en uMEC100 | Error absoluto | Error porcentual |
|---|---:|---:|---:|---:|
| SpO₂ | 98% | 98% | 0% | 0% |
| Frecuencia cardiaca | 140 bpm | 140 bpm | 0 bpm | 0% |

Cálculos realizados:

- Error absoluto SpO₂ = \|98 - 98\| = 0%
- Error porcentual SpO₂ = (0 / 98) × 100 = 0%
- Error absoluto FC = \|140 - 140\| = 0 bpm
- Error porcentual FC = (0 / 140) × 100 = 0%


Durante la simulación de taquicardia, el monitor presentó una frecuencia cardiaca de **140 bpm**, valor que superó el límite alto de frecuencia cardiaca, por lo que se activó la alarma de **frecuencia cardiaca elevada**. La señal fotopletismográfica mostró pulsos más cercanos entre sí que en las condiciones de menor frecuencia cardiaca, lo cual es consistente con el aumento del número de latidos por minuto.

Además, no se encontraron diferencias entre los valores utilizados en el análisis y los valores observados en el monitor, por lo que el error absoluto y el error porcentual fueron de 0% para ambas variables.

##  ANÁLISIS DE RESULTADOS

### Análisis 1. Evaluación estadística entre los valores de energía de referencia y los suministrados por el desfibrilador

Para evaluar el comportamiento del desfibrilador, se compararon valores de energía de referencia con valores de energía suministrada registrados por el analizador. La energía de referencia corresponde al valor patrón configurado para la prueba, mientras que la energía suministrada corresponde al valor entregado por el desfibrilador y registrado por el equipo de medición.

A partir de estos valores se calcularon el error absoluto y el error porcentual para cada nivel de energía. El error absoluto permite conocer la diferencia directa en joules entre el valor patrón y el valor suministrado, mientras que el error porcentual permite interpretar esa diferencia en relación con la magnitud de la energía configurada.

| Prueba | Energía de referencia o patrón (J) | Energía suministrada (J) | Error absoluto (J) | Error porcentual (%) |
|---|---:|---:|---:|---:|
| 1 | 10 | 9,8 | 0,2 | 2,00 |
| 2 | 20 | 19,6 | 0,4 | 2,00 |
| 3 | 50 | 49,2 | 0,8 | 1,60 |
| 4 | 100 | 98,5 | 1,5 | 1,50 |
| 5 | 150 | 148,3 | 1,7 | 1,13 |

Cálculos empleados:

Error absoluto = |Energía suministrada - Energía de referencia|

Error porcentual = (Error absoluto / Energía de referencia) × 100

Resumen estadístico de los errores:

| Parámetro estadístico | Resultado |
|---|---:|
| Promedio del error absoluto | 0,92 J |
| Desviación estándar del error absoluto | 0,66 J |
| Error porcentual promedio | 1,65% |
| Desviación estándar del error porcentual | 0,37% |
| Error porcentual mínimo | 1,13% |
| Error porcentual máximo | 2,00% |
| Coeficiente de variación del error porcentual | 22,25% |

Al analizar los resultados se observa que la energía suministrada fue ligeramente menor que la energía de referencia en todas las pruebas. Esto indica una tendencia de subentrega de energía, es decir, el desfibrilador entregó valores un poco inferiores a los valores patrón configurados. Sin embargo, las diferencias fueron bajas, ya que el error porcentual máximo fue de 2,00% y el error porcentual promedio fue de 1,65%.

También se evidencia que el error absoluto aumentó a medida que aumentó la energía configurada, pasando de 0,2 J en la prueba de 10 J a 1,7 J en la prueba de 150 J. No obstante, al analizar el error porcentual, la diferencia relativa disminuyó en los valores altos de energía, lo cual indica que la desviación no creció de forma proporcionalmente crítica respecto al valor patrón.

En general, los resultados muestran un comportamiento estable del desfibrilador, con errores porcentuales bajos y sin variaciones bruscas entre las pruebas. La desviación estándar del error porcentual fue de 0,37%, lo que indica que los errores se mantuvieron agrupados alrededor del promedio. Por lo tanto, bajo estas condiciones de prueba, el desfibrilador presentó una entrega de energía consistente y cercana a los valores de referencia.

### Análisis 2. Relación entre la forma de onda visualizada en el monitor y la frecuencia cardiaca/saturación periférica de oxígeno

Durante la práctica se observó la forma de onda asociada a la señal fotopletismográfica en el monitor uMEC100. Esta señal representa los cambios pulsátiles relacionados con la detección óptica del pulso periférico por medio del sensor de SpO₂. Por esta razón, la forma de onda se relaciona directamente con la frecuencia cardiaca simulada y con la calidad de la señal de saturación periférica de oxígeno.

| Condición evaluada | Frecuencia cardiaca observada | SpO₂ observada | Valor observado en el monitor | Comportamiento de la onda |
|---|---:|---:|---|---|
| Bradicardia | 40 bpm | 95% | FC 40 bpm / SpO₂ 95% | Pulsos más separados, onda lenta y estable |
| SpO₂ baja | 80 bpm | 85% | FC 80 bpm / SpO₂ 85% | Onda periódica, con activación de alarma por baja saturación |
| SpO₂ alta | 140 bpm | 99% | FC 140 bpm / SpO₂ 99% | Onda rápida, con activación de alarma por saturación alta |
| Taquicardia | 140 bpm | 98% | FC 140 bpm / SpO₂ 98% | Pulsos más cercanos, onda rápida y repetitiva |

En la condición de bradicardia, el monitor registró una frecuencia cardiaca de 40 bpm y una SpO₂ de 95%. En esta condición, la onda fotopletismográfica presentó pulsos más separados entre sí, debido a que el intervalo entre cada latido aumenta cuando la frecuencia cardiaca disminuye. Por esta razón, la señal se observa más lenta en la pantalla del monitor, aunque mantiene una forma pulsátil definida y estable.

En la condición de SpO₂ baja, el monitor registró una frecuencia cardiaca de 80 bpm y una SpO₂ de 85%. Como el límite inferior de alarma se configuró en 90%, el valor observado quedó por debajo del umbral establecido y se activó la alarma de baja saturación. En esta prueba, la onda conservó un comportamiento periódico, ya que la frecuencia cardiaca se mantuvo en un valor intermedio; sin embargo, la condición crítica estuvo asociada al valor bajo de saturación de oxígeno.

En la condición de SpO₂ alta, el monitor registró una SpO₂ de 99%, valor superior al límite configurado de 97%. Por esta razón, se activó la alarma de saturación alta. En la imagen correspondiente también se observó una frecuencia cardiaca de 140 bpm, por lo que la onda presentó ciclos más próximos entre sí. Esto se explica porque, al aumentar la frecuencia cardiaca, disminuye el tiempo entre latidos y la señal fotopletismográfica se visualiza más rápida.

Finalmente, en la condición de taquicardia, el monitor registró una frecuencia cardiaca de 140 bpm y una SpO₂ de 98%. La onda fotopletismográfica presentó pulsos cercanos y repetitivos, coherentes con una frecuencia cardiaca elevada. Este comportamiento confirma que la frecuencia de la onda aumenta a medida que aumenta la frecuencia cardiaca simulada u observada en el monitor.

En general, se evidenció que la forma de onda fotopletismográfica cambia de acuerdo con la frecuencia cardiaca y con la condición de saturación evaluada. A menor frecuencia cardiaca, como en 40 bpm, los pulsos aparecen más separados; mientras que a frecuencias elevadas, como 140 bpm, los pulsos aparecen más cercanos. Además, la SpO₂ no modifica directamente la frecuencia de la onda, pero sí determina la activación de alarmas cuando se encuentra por debajo o por encima de los límites configurados.

## CONCLUSIONES

Al finalizar la práctica se pudo comprobar que el uso del simulador OxSim y del monitor uMEC100 permitió reproducir diferentes condiciones fisiológicas simuladas, como bradicardia, taquicardia, saturación baja de oxígeno y saturación elevada. Estas condiciones fueron útiles para verificar el comportamiento de las alarmas visuales y sonoras del monitor, así como para observar la respuesta de la señal fotopletismográfica ante cambios en la frecuencia cardiaca y en la SpO₂.

Respecto a la confiabilidad del D30 en las pruebas realizadas, se puede concluir que este equipo funciona como una herramienta importante para la verificación biomédica, ya que permite evaluar si los equipos médicos responden adecuadamente ante señales simuladas o condiciones controladas. Su confiabilidad depende de que el equipo se encuentre calibrado, de que las conexiones sean correctas y de que el procedimiento se realice siguiendo una metodología ordenada. Por esta razón, el D30 puede considerarse confiable para pruebas funcionales y de verificación, aunque sus resultados siempre deben interpretarse dentro del contexto de la práctica y no como una medición clínica directa en un paciente real.

En cuanto al módulo OxSim, se evidenció que permite simular condiciones relacionadas con pulsioximetría, como disminución de SpO₂, baja perfusión, bradicardia y taquicardia. Esto facilita la evaluación del comportamiento del monitor ante situaciones críticas sin necesidad de utilizar pacientes reales. Sin embargo, el OxSim también presenta limitaciones, ya que las señales generadas son simuladas y no reproducen completamente la variabilidad fisiológica de un paciente real, como movimientos, mala colocación del sensor, cambios bruscos de perfusión, interferencias, arritmias complejas o alteraciones reales en la circulación periférica.

Finalmente, la práctica permitió reconocer la importancia de verificar periódicamente los monitores biomédicos y sus alarmas, ya que estos equipos son fundamentales para la vigilancia del paciente. La activación correcta de las alarmas ante valores fuera de rango demuestra que el sistema puede alertar al personal clínico frente a condiciones de riesgo. No obstante, también se debe tener en cuenta que la confiabilidad de la medición depende tanto del estado del equipo como de la calidad de la señal, la configuración adecuada de los límites de alarma y las condiciones bajo las cuales se realiza la prueba.

## PREGUNTAS PARA LA DISCUSIÓN

### Pregunta 1. ¿Cuál es el principio de operación del Pronk OxSim OX-1 para simular una onda pulsátil?

El Pronk OxSim OX-1 funciona como un simulador óptico de pulsioximetría. Su principio de operación consiste en generar señales ópticas que imitan el comportamiento de un dedo real colocado en un sensor de SpO₂. Para ello, el equipo simula variaciones en la absorción de luz roja e infrarroja, similares a las que ocurren cuando cambia el volumen de sangre arterial durante cada pulso cardiaco.

El sensor de pulsioximetría detecta estas variaciones como una señal pulsátil o fotopletismográfica. A partir de esa señal, el monitor calcula la saturación periférica de oxígeno y la frecuencia cardiaca. Por esta razón, el OxSim permite comprobar si el monitor, el sensor y el cable de extensión responden correctamente ante diferentes condiciones simuladas de SpO₂, frecuencia cardiaca y perfusión.

En la práctica, el OxSim permitió simular condiciones como bradicardia, taquicardia, saturación baja, saturación alta y baja perfusión. Esto permitió observar la respuesta del monitor uMEC100 ante condiciones controladas, sin necesidad de realizar pruebas directamente sobre un paciente.

### Pregunta 2. ¿Por qué la SpO₂ baja puede ser un falso positivo o falsa alarma en una situación de mala perfusión?

Una SpO₂ baja puede convertirse en un falso positivo cuando existe mala perfusión periférica porque el sensor recibe una señal pulsátil débil o inestable. La pulsioximetría necesita detectar adecuadamente los cambios de volumen sanguíneo arterial en el sitio donde está colocado el sensor. Si la perfusión es baja, llega menos sangre pulsátil al dedo o al área medida, por lo que la amplitud de la onda fotopletismográfica disminuye.

Cuando la señal es débil, el monitor puede tener dificultad para diferenciar la señal arterial real del ruido, del movimiento, de la luz ambiental o de interferencias externas. Como consecuencia, el equipo puede interpretar de forma incorrecta la relación entre la luz roja e infrarroja y mostrar una SpO₂ más baja de la real. En ese caso, la alarma de saturación baja se activa aunque el paciente no necesariamente tenga una hipoxemia verdadera.

Por esta razón, ante una alarma de SpO₂ baja en condiciones de mala perfusión, no se debe interpretar únicamente el valor numérico. También se debe revisar la forma de onda fotopletismográfica, la amplitud de la señal, la colocación del sensor, la temperatura periférica, el estado circulatorio del paciente y la presencia de movimiento. Si la onda se observa distorsionada, irregular o de muy baja amplitud, la lectura puede no ser confiable y la alarma puede corresponder a un falso positivo.



