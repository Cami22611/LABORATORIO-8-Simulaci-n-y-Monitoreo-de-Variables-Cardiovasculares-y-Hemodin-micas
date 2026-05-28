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
1.  | Prueba | Alarma evaluada | Límite configurado en el uMEC100 | Valor simulado en OxSim | ¿Alarma activa? | Tiempo de respuesta |
|---|---|---|---|---|---|
| 1 | Frecuencia cardiaca baja / bradicardia | Límite inferior de FC: 50 bpm | FC: 40 bpm / SpO₂: 95% | Sí | 5 s |
| 2 | SpO₂ baja | Límite inferior de SpO₂: 90% | FC: 80 bpm / SpO₂: 85% | Sí | 5 s |
| 3 | SpO₂ alta | Límite superior de SpO₂: 97% | FC: 80 bpm / SpO₂: 99% | Sí | 5 s |
| 4 | Frecuencia cardiaca alta / taquicardia | Límite superior de FC: 120 bpm | FC: 140 bpm / SpO₂: 98% | Sí | 5 s |

De acuerdo con la verificación realizada, el monitor uMEC100 activó correctamente las alarmas cuando los valores simulados en el OxSim superaron los límites configurados. En la prueba de bradicardia, al simular una frecuencia cardiaca de 40 bpm, el valor quedó por debajo del límite inferior establecido, por lo que se activó la alarma correspondiente. Para la condición normal, con una frecuencia cardiaca de 80 bpm, el equipo se mantuvo dentro del rango esperado. Finalmente, en la prueba de taquicardia, al simular una frecuencia cardiaca de 140 bpm, el valor superó el límite superior configurado y se generó la alarma.

En las pruebas relacionadas con la saturación de oxígeno, se observó que el monitor respondió adecuadamente ante valores fuera del rango configurado. Cuando se simuló una SpO₂ baja, menor al límite inferior establecido, el equipo activó la alarma visual y sonora. De igual manera, cuando se simuló una SpO₂ alta, superior al límite máximo permitido, también se presentó activación de alarma. En general, el comportamiento del monitor fue coherente con los valores programados en el simulador, lo que indica que el sistema de alarmas respondió de forma adecuada durante la prueba.

  



