# LABORATORIO 6: Simulación y monitoreo de variables cardiovasculares y hemodinámicas

## INTRODUCCIÓN
El monitoreo de signos vitales constituye una herramienta fundamental en el ámbito clínico, debido a que permite evaluar de forma continua variables fisiológicas asociadas al estado cardiovascular y respiratorio del paciente, favoreciendo la detección temprana de alteraciones que puedan comprometer su seguridad. Dentro de estos parámetros, la pulsioximetría permite estimar de manera no invasiva la saturación periférica de oxígeno y es ampliamente utilizada para identificar y vigilar estados de hipoxemia (Organización Panamericana de la Salud, 2020). En este contexto, el monitor de signos vitales uMEC 100 permite la medición y visualización de variables clínicas como SpO₂, frecuencia de pulso, frecuencia cardíaca y otros parámetros requeridos para la vigilancia del paciente (Mindray, 2023). Por su parte, el simulador Pronk OxSim OX-1 permite verificar funcionalmente sistemas de pulsioximetría mediante la simulación de valores definidos de saturación de oxígeno, frecuencia de pulso e índice de perfusión, incluyendo condiciones como bradicardia, taquicardia, hipoxemia y baja perfusión (Pronk Technologies, s.f.). Por ello, el uso conjunto del uMEC 100 y el OxSim OX-1 en la práctica de laboratorio permite relacionar el funcionamiento técnico del monitor con criterios de seguridad clínica, precisión de medición y activación de alarmas ante condiciones fisiológicas simuladas.

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

- ### Paciente bradicárdico

Se configuró el simulador OxSim para representar un paciente bradicárdico con una frecuencia cardiaca de 40 bpm y una saturación de oxígeno de 95%. Luego, se compararon los valores simulados con los valores mostrados en el monitor uMEC100, tomando el OxSim como valor de referencia.

| Variable            | Valor simulado en OxSim | Valor mostrado en uMEC100 | Error absoluto | Error porcentual |
| ------------------- | ----------------------: | ------------------------: | -------------: | ---------------: |
| SpO₂                |                     95% |                       96% |             1% |            1,05% |
| Frecuencia cardiaca |                  40 bpm |                    40 bpm |          0 bpm |               0% |

Cálculos realizados:

Error absoluto SpO₂ = |96 - 95| = 1%

Error porcentual SpO₂ = (1 / 95) × 100 = 1,05%

Error absoluto FC = |40 - 40| = 0 bpm

Error porcentual FC = (0 / 40) × 100 = 0%

De acuerdo con los resultados, el monitor uMEC100 registró correctamente la frecuencia cardiaca simulada, ya que no presentó diferencia respecto al valor configurado en el OxSim. En la saturación de oxígeno se presentó una diferencia de 1%, equivalente a un error porcentual de 1,05%, lo cual indica una variación baja entre el valor simulado y el valor mostrado por el monitor.

- ### Registro de la forma de onda fotopletismográfica

Al observar la pantalla del monitor uMEC100, se identificó la forma de onda fotopletismográfica correspondiente a la señal del pulsioxímetro. La señal presentó un comportamiento pulsátil y periódico, relacionado con la detección del pulso periférico. Esto permitió verificar que el sensor de SpO₂ estaba captando correctamente la señal generada por el simulador OxSim y que el monitor representaba visualmente los cambios asociados a la frecuencia cardiaca y a la saturación de oxígeno.

- ### Verificación de alarma por SpO₂ baja

En el monitor uMEC100 se configuró el límite inferior de alarma de SpO₂ en 90%. Posteriormente, el simulador OxSim se ajustó para simular una frecuencia cardiaca de 80 bpm y una SpO₂ de 85%. Como el valor de SpO₂ simulado se encontraba por debajo del límite configurado, se esperó un tiempo de 5 segundos y se verificó la activación de la alarma sonora y visual en el uMEC100.

| Variable | Valor simulado en OxSim | Valor mostrado en uMEC100 | Error absoluto | Error porcentual |
|---|---:|---:|---:|---:|
| SpO₂ | 85% | 83% | 2% | 2,35% |
| Frecuencia cardiaca | 80 bpm | 80 bpm | 0 bpm | 0% |

Cálculos realizados:

Error absoluto SpO₂ = |83 - 85| = 2%

Error porcentual SpO₂ = (2 / 85) × 100 = 2,35%

Error absoluto FC = |80 - 80| = 0 bpm

Error porcentual FC = (0 / 80) × 100 = 0%

De acuerdo con los resultados obtenidos, el monitor uMEC100 detectó correctamente la condición de baja saturación de oxígeno, ya que el valor mostrado de SpO₂ fue inferior al límite configurado de 90%. La alarma sonora y visual se activó después de 5 segundos, cumpliendo con lo solicitado en la práctica. En cuanto a los errores, la SpO₂ presentó un error absoluto de 2% y un error porcentual de 2,35%, mientras que la frecuencia cardiaca no presentó diferencia entre el valor simulado y el valor mostrado por el monitor.
- ### Configuración de alarma de límite superior de SpO₂

En el monitor uMEC100 se configuró la alarma de límite superior de SpO₂ en 97%. Esta configuración permitió evaluar si el equipo activaba la alarma cuando el valor de saturación de oxígeno superaba el límite establecido.

- ### Verificación de alarma por SpO₂ alta en modo Low Perfusion

Posteriormente, el simulador OxSim se ajustó para simular una SpO₂ de 99% en modo “Low Perfusion”, manteniendo una frecuencia cardiaca de 80 bpm. A partir de ese momento, se esperaron 5 segundos y se verificó la activación de la alarma sonora y visual en el monitor uMEC100.

| Variable | Valor simulado en OxSim | Valor mostrado en uMEC100 | Error absoluto | Error porcentual |
|---|---:|---:|---:|---:|
| SpO₂ | 99% | 99% | 0% | 0% |
| Frecuencia cardiaca | 80 bpm | 80 bpm | 0 bpm | 0% |

Cálculos realizados:

Error absoluto SpO₂ = |99 - 99| = 0%

Error porcentual SpO₂ = (0 / 99) × 100 = 0%

Error absoluto FC = |80 - 80| = 0 bpm

Error porcentual FC = (0 / 80) × 100 = 0%

De acuerdo con los resultados obtenidos, el monitor uMEC100 activó correctamente la alarma sonora y visual, ya que la SpO₂ simulada fue de 99% y superó el límite superior configurado de 97%. No se presentó error entre los valores simulados en el OxSim y los valores mostrados en el uMEC100. En cuanto a la onda fotopletismográfica, sí se observó una posible distorsión o disminución en la amplitud de la señal, debido a que el modo “Low Perfusion” simula una condición de baja perfusión periférica, en la cual la señal pulsátil puede verse más débil o menos definida.

- ### Verificación de alarma por frecuencia cardiaca elevada

Con un valor de SpO₂ de 95%, se generó una taquicardia en el simulador OxSim configurando una frecuencia cardiaca de 140 bpm. Luego, se observó la onda en el monitor uMEC100 y se verificó si se activaba la alarma correspondiente a frecuencia cardiaca elevada.

| Variable | Valor simulado en OxSim | Valor mostrado en uMEC100 | Error absoluto | Error porcentual |
|---|---:|---:|---:|---:|
| SpO₂ | 95% | 94% | 1% | 1,05% |
| Frecuencia cardiaca | 140 bpm | 141 bpm | 1 bpm | 0,71% |

Cálculos realizados:

Error absoluto SpO₂ = |94 - 95| = 1%

Error porcentual SpO₂ = (1 / 95) × 100 = 1,05%

Error absoluto FC = |141 - 140| = 1 bpm

Error porcentual FC = (1 / 140) × 100 = 0,71%

De acuerdo con los resultados obtenidos, el monitor uMEC100 registró una frecuencia cardiaca de 141 bpm frente a los 140 bpm configurados en el OxSim, presentando un error absoluto de 1 bpm y un error porcentual de 0,71%. Para la SpO₂, el monitor mostró 94% frente al valor patrón de 95%, con un error absoluto de 1% y un error porcentual de 1,05%. La alarma de frecuencia cardiaca elevada sí se activó, ya que el valor de frecuencia cardiaca se encontraba por encima del límite superior configurado para el paciente.

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

### Análisis 2. Relación entre la forma de onda visualizada en el D30 y la frecuencia cardiaca/saturación periférica de oxígeno

Durante la práctica se observó la forma de onda asociada a la señal fotopletismográfica. Esta señal representa los cambios pulsátiles del volumen sanguíneo periférico detectados por el sensor de pulsioximetría. Por esta razón, la forma de onda se relaciona directamente con la frecuencia cardiaca simulada y con la calidad de la señal de saturación periférica de oxígeno.

| Condición evaluada | Frecuencia cardiaca simulada | SpO₂ simulada | Valor observado en el monitor | Comportamiento de la onda |
|---|---:|---:|---|---|
| Bradicardia | 40 bpm | 95% | FC 40 bpm / SpO₂ 96% | Pulsos más separados, onda lenta y estable |
| SpO₂ baja | 80 bpm | 85% | FC 80 bpm / SpO₂ 83% | Onda periódica, con activación de alarma por baja saturación |
| SpO₂ alta en modo Low Perfusion | 80 bpm | 99% | FC 80 bpm / SpO₂ 99% | Onda de menor amplitud y posible distorsión |
| Taquicardia | 140 bpm | 95% | FC 141 bpm / SpO₂ 94% | Pulsos más cercanos, onda rápida y repetitiva |

En la condición de bradicardia, con una frecuencia cardiaca simulada de 40 bpm, la onda presentó pulsos más separados entre sí. Esto ocurre porque el intervalo entre cada latido es mayor cuando la frecuencia cardiaca disminuye. Por esta razón, la señal se observa más lenta en la pantalla del monitor, aunque mantiene una forma pulsátil definida.

Cuando se simuló una frecuencia cardiaca de 80 bpm, la onda se observó más regular, con pulsos distribuidos de manera uniforme. En la prueba de SpO₂ baja, con un valor simulado de 85%, el monitor registró una saturación de 83% y activó la alarma correspondiente, debido a que el valor se encontraba por debajo del límite inferior configurado en 90%. En esta condición, la frecuencia de la onda se mantuvo estable porque la frecuencia cardiaca no cambió, pero la alarma se relacionó directamente con el valor de saturación.

En la prueba de SpO₂ alta en modo “Low Perfusion”, el simulador se configuró con una saturación de 99% y una frecuencia cardiaca de 80 bpm. En esta condición, la onda fotopletismográfica pudo observarse con menor amplitud o con distorsión. Esto se debe a que el modo de baja perfusión simula una señal periférica débil, lo que disminuye la intensidad de la señal pulsátil detectada por el sensor. Aunque el valor numérico de SpO₂ fue registrado correctamente, la calidad visual de la onda puede verse afectada.

Finalmente, en la condición de taquicardia, con una frecuencia cardiaca simulada de 140 bpm, la onda presentó pulsos más cercanos entre sí. Esto se debe a que el tiempo entre latidos disminuye cuando aumenta la frecuencia cardiaca. El monitor registró una frecuencia de 141 bpm y una SpO₂ de 94% frente al valor patrón de 95%, mostrando diferencias bajas respecto a los valores simulados. Además, se activó la alarma de frecuencia cardiaca elevada, ya que el valor superó el límite superior configurado.

En general, se evidenció que la forma de onda cambia de acuerdo con la frecuencia cardiaca y con la calidad de la señal de SpO₂. A menor frecuencia cardiaca, los pulsos aparecen más separados; a mayor frecuencia cardiaca, los pulsos aparecen más cercanos. Además, en condiciones de baja perfusión, la onda puede disminuir su amplitud o presentar distorsión, debido a que la señal pulsátil captada por el sensor es más débil.
  



