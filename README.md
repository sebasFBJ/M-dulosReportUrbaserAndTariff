## 📌 Product Backlog

| ID | User Story | Prioridad | Responsable | Estado |
|----|------------|-----------|-------------|--------|
| US01 | Como usuario quiero iniciar sesión para acceder al sistema | Alta | Sofía | En progreso |
| US02 | Como admin quiero crear roles para asignar permisos | Alta | Sebastián | Pendiente |
| US03 | Como usuario quiero ver mi perfil para actualizar datos | Media | Carlos | Finalizado |

# 📌 Product Backlog – Módulo de Reportes

| ID | Nombre del Requisito | Descripción | Prioridad | Estimación (SP) | Estado |
|----|----------------------|-------------|-----------|------------------|--------|
| RF01 | Inicio de sesión controlado | El usuario inicia sesión con credenciales asignadas sin posibilidad de crear cuenta. | Alta | 5 | Pendiente |
| RF02 | Visualización de servicios | El usuario visualiza la lista de servicios disponibles para reporte. | Alta | 3 | Pendiente |
| RF03 | Selección de servicio | El usuario selecciona el servicio para acceder al formulario correspondiente. | Alta | 3 | Pendiente |
| RF04 | Formulario dinámico | El formulario se adapta según el servicio seleccionado mostrando campos específicos. | Alta | 8 | Pendiente |
| RF05 | Validación de campos | Todos los campos del formulario deben ser validados antes del envío. | Alta | 5 | Pendiente |
| RF06 | Mensaje de éxito | Al enviar un reporte válido, se muestra un mensaje de confirmación. | Media | 2 | Pendiente |
| RF07 | Mensaje de error o alerta | Si la validación falla se muestra un mensaje indicando los errores. | Alta | 3 | Pendiente |
| RF08 | Responsividad | La aplicación debe funcionar correctamente en móvil y escritorio. | Media | 8 | Pendiente |
| RF09 | Modo administrador | Los administradores gestionan los reportes desde un panel dedicado. | Alta | 13 | Pendiente |
| RF10 | Control de acceso | Se delimitan permisos entre usuarios y administradores para garantizar seguridad. | Alta | 5 | Pendiente |




# 📌 Historias de Usuario – Módulo de Reportes

| ID | Historia de Usuario | Descripción / Objetivo | Criterios de Aceptación |
|----|----------------------|------------------------|--------------------------|
| US01 | Como **usuario**, quiero **iniciar sesión**, para **acceder a la plataforma y realizar reportes**. | Basado en RF01 | - Debe ingresar usuario/contraseña válidos<br>- Si es correcto, entra al sistema<br>- Si no, muestra error |
| US02 | Como **usuario**, quiero **visualizar los servicios disponibles**, para **seleccionar el tipo de reporte que necesito**. | Basado en RF02 | - Mostrar lista de servicios<br>- Debe cargarse rápido<br>- Cada servicio debe ser seleccionable |
| US03 | Como **usuario**, quiero **seleccionar un servicio**, para **acceder al formulario específico del reporte**. | Basado en RF03 | - Al hacer clic, abre el formulario<br>- Mantiene el nombre del servicio seleccionado |
| US04 | Como **usuario**, quiero **que el formulario sea dinámico**, para **llenar solo los campos necesarios según el tipo de servicio**. | Basado en RF04 | - Cambia campos según servicio<br>- Debe validar tipos de campos |
| US05 | Como **usuario**, quiero **que el sistema valide el formulario**, para **evitar enviar información incompleta o incorrecta**. | Basado en RF05 | - Validar campos requeridos<br>- Validar formato de datos |
| US06 | Como **usuario**, quiero **ver un mensaje de éxito**, para **saber que mi reporte fue enviado correctamente**. | Basado en RF06 | - Mensaje visible<br>- Opcional: redirigir o limpiar formulario |
| US07 | Como **usuario**, quiero **ver mensajes de error**, para **corregir los datos ingresados**. | Basado en RF07 | - Alertas claras<br>- Indicar qué campo falló |
| US08 | Como **usuario**, quiero **que la aplicación sea responsiva**, para **usarla desde mi celular o PC**. | Basado en RF08 | - Todo el diseño debe adaptarse<br>- No debe romperse en pantallas pequeñas |
| US09 | Como **administrador**, quiero **visualizar y gestionar los reportes**, para **tomar acciones correspondientes**. | Basado en RF09 | - Vista de lista completa<br>- Ver detalles de reportes<br>- Filtrar y ordenar |
| US10 | Como **administrador**, quiero **control de acceso**, para **mantener seguridad entre perfiles**. | Basado en RF10 | - Usuarios normales no acceden a vista admin<br>- Roles separados<br>- Acceso restringido correctamente |
