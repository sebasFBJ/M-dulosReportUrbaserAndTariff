## 📌 Requisitos Funcionales – Módulo de Recolección

| ID | Requisito Funcional | Descripción |
|----|---------------------|-------------|
| RF-R01 | Registro de incidencias del servicio de recolección | El sistema debe permitir a los ciudadanos registrar reportes relacionados con incidencias en la recolección de residuos. |
| RF-R02 | Validación de reportes ciudadanos | El sistema debe validar los campos obligatorios y formatos de datos antes de permitir el envío del reporte. |
| RF-R03 | Visualización básica de reportes | El sistema debe permitir consultar los reportes almacenados en la base de datos, en modo desarrollo. |
| RF-R04 | Registro de incidencias del servicio de barrido | El sistema debe permitir registrar incidencias asociadas al servicio de barrido. *(Fuera del alcance por cambio de tecnología)* |
| RF-R05 | Migración de funcionalidad | Se debe migrar el módulo de recolección existente hacia la nueva tecnología seleccionada, conservando sus funcionalidades. |
| RF-R06 | Mensajería de retroalimentación | El sistema debe mostrar mensajes de éxito o error al usuario al registrar un reporte. |
| RF-R07 | Formulario dinámico según servicio | El formulario debe adaptarse automáticamente según el servicio seleccionado (recolección, barrido, otros). |
| RF-R08 | Responsividad | La interfaz debe adaptarse correctamente a dispositivos móviles y computadores. |


## 📌 Requisitos Funcionales – Módulo de Tarifas

| ID | Requisito Funcional | Descripción |
|----|---------------------|-------------|
| RF-T01 | Registro de datos tarifarios | El sistema debe permitir ingresar los datos técnicos y económicos para el cálculo CBL y CRT según resolución CRA 720/2015. |
| RF-T02 | Cálculo automatizado de tarifas | El sistema debe aplicar las fórmulas establecidas por la CRA para calcular CBL y CRT automáticamente. |
| RF-T03 | Almacenamiento de resultados | El sistema debe guardar en base de datos los resultados generados, asociados al municipio, prestador y periodo. |
| RF-T04 | Visualización de tarifas en dashboard | El sistema debe permitir visualizar los resultados de los cálculos en el dashboard. |
| RF-T05 | Edición de registros | El administrador debe poder modificar los datos ingresados antes de recalcular las tarifas. |
| RF-T06 | Validación con datos simulados | El sistema debe aceptar datos simulados para validar la precisión de las fórmulas implementadas. |
| RF-T07 | Mensajes de retroalimentación | El sistema debe mostrar mensajes de éxito o error sobre los cálculos realizados. |


## 📌 Historias de Usuario – Módulo de Recolección

| ID | Historia de Usuario | Criterios de Aceptación |
|----|---------------------|--------------------------|
| US-R01 | Como ciudadano, quiero registrar un reporte de recolección para informar incidencias del servicio. | - Permite ingresar comuna, barrio, descripción, fecha, evidencia.<br>- Guarda la información correctamente. |
| US-R02 | Como ciudadano, quiero que los campos del formulario sean validados para evitar enviar datos incorrectos. | - Campos obligatorios validados.<br>- Datos en formato correcto.<br>- No envía si falta información. |
| US-R03 | Como funcionario, quiero visualizar los reportes registrados para analizarlos y hacer seguimiento. | - Lista visible de reportes.<br>- Consulta básica por fecha, comuna. |
| US-R04 | Como ciudadano, quiero recibir mensajes de éxito o error para saber si mi reporte se registró adecuadamente. | - Mensaje verde para éxito.<br>- Mensaje rojo para error. |
| US-R05 | Como usuario, quiero que el formulario cambie según el servicio seleccionado para registrar la información correcta. | - Campos cambian según “Recolección”, “Barrido” u otro servicio. |
| US-R06 | Como usuario, quiero que la aplicación funcione bien en mi celular o computador. | - Diseño responsivo.<br>- No se desconfigura. |
| US-R07 | Como administrador, quiero que la funcionalidad existente del módulo se conserve al migrarlo a una nueva tecnología. | - Funciones previas replicadas.<br>- No se pierde información. |


## 📌 Historias de Usuario – Módulo de Tarifas

| ID | Historia de Usuario | Criterios de Aceptación |
|----|---------------------|--------------------------|
| US-T01 | Como administrador, quiero registrar los datos tarifarios para ejecutar los cálculos CBL y CRT. | - Formulario completo.<br>- Validación de campos numéricos. |
| US-T02 | Como administrador, quiero que el sistema calcule automáticamente las tarifas según CRA 720/2015. | - Aplicación correcta de fórmulas.<br>- Resultados exactos. |
| US-T03 | Como administrador, quiero guardar los resultados de los cálculos para consultarlos cuando los necesite. | - Registro almacenado en BD.<br>- Datos asociados al periodo. |
| US-T04 | Como administrador, quiero visualizar los resultados calculados en el dashboard para analizarlos. | - Gráficas o tablas visibles.<br>- Datos actualizados. |
| US-T05 | Como administrador, quiero editar los datos tarifarios antes de recalcular valores. | - Campos modificables.<br>- Recalcula después de guardar. |
| US-T06 | Como técnico, quiero probar las fórmulas con datos simulados para validar el funcionamiento del módulo. | - Permite datos de prueba.<br>- Identifica errores numéricos. |
| US-T07 | Como administrador, quiero ver mensajes de éxito o error para saber si el cálculo fue realizado correctamente. | - Mensajes claros.<br>- Notificación visible. |
