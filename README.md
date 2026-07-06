# UNIDAD 1: Discovery Agent

En la unidad 1 se implementa un **Discovery Agent** utilizando modelos de lenguaje avanzado de Claude para dar solución al diseño y construcción de un **Sistema de Gestión Vehicular para la Policía Nacional**. Este sistema abarca:
- La gestión de mantenimientos
- Solicitudes de repuestos
- Autorizaciones de traslados
- Reasignaciones de vehículos
- Registro de novedades o accidentes
- Reserva de turnos para mantenimientos de vehículos

Después de la implementación y el descubrimiento realizado por la IA, podemos responder las siguientes preguntas:

## ¿Qué supuesto tuyo sobre el problema cambió al revisar la evidencia real?
Al analizar la evidencia de las entrevistas, el supuesto inicial que cambia drásticamente es atribuir los cuellos de botella operativos a una supuesta "resistencia al cambio" tecnológico por parte de los usuarios del sistema. Las entrevistas evidencian que el mecánico no se opone a la utilización de un sistema, sino a la pérdida de tiempo cuadrando hojas de cálculo de Excel a fin de mes, y que el incumplimiento con mantenimientos programados del policía responde al simple olvido de un papel, no al deseo de no querer asistir.

## ¿Qué fue lo más difícil de cumplir la regla de "cero invención"?
Como modelo de IA procesando este contexto, lo más difícil de mantener la regla de "cero invención" es contener la tendencia de implementar soluciones innovadoras con temas no mencionados en las entrevistas o cosas fuera de contexto (por ejemplo, un rastreo GPS o el mantenimiento predictivo mediante sensores, etc.), forzando la delimitación del alcance estrictamente a los dolores explícitos de los actores, como la necesidad de usar un sistema para las aprobaciones (actualmente por correos electrónicos) o el agendamiento vía web (realizado por WhatsApp con los celulares personales).

## ¿Para qué te serviría la idea de "gobernanza ejecutable" en tu trabajo?
Aplicar el concepto de "gobernanza ejecutable" permite que la trazabilidad no muera en un repositorio estático como documentos generados para cumplir la fase de diseño, sino que defina de forma activa las siguientes fases del proceso de desarrollo llegando hasta la implementación (por ejemplo con el desarrollo guiado por especificaciones *Spec-Driven Development*). Los criterios de aceptación de las historias de usuario y la superación de las hipótesis de riesgo se transforman en pruebas y reglas automatizadas.

---