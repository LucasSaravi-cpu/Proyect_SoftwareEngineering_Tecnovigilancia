**Descripcion del sistema**

**Sistema de Gestión de Equipamiento Médico para Tecnovigilancia**
Este sistema está diseñado para abordar las necesidades de gestión del equipamiento médico de una institución de salud, especialmente en áreas de alta tecnología como Tecnovigilancia. El sistema permite el inventario y mantenimiento de equipos esenciales en la atención de los pacientes, permitiendo a la institución registrar, controlar y seguir el estado y uso de estos equipos.

**Objetivos del Sistema**
- Inventario Completo del Equipamiento Médico: Registro detallado de todos los equipos clasificados por tipo (p. ej., respiradores, monitores, camas, etc.), ubicación, estado y proveedor.
-Gestión de Mantenimiento: Control de mantenimientos preventivos y correctivos, realizados por proveedores externos. Para el caso de los respiradores, se incluye un seguimiento específico basado en horas de uso con alertas y notificaciones según el estado del equipo.
-Seguimiento del Estado del Equipo: Visualización y actualización del estado de los equipos en tiempo real, manteniendo registro de los estados básicos (En uso, En espera de servicio, Disponibles, En mantenimiento, etc.).
**Funcionalidades Clave**
Generación y Uso de Códigos QR: Cada equipo cuenta con un número de serie y un código QR impreso, generado por el sistema, que permite acceder a su información desde dispositivos móviles según el perfil de usuario.
**Perfiles de Usuario:**
-Administrador: Acceso completo al sistema y a la información detallada de los equipos.
-Tecnovigilancia: Gestión y seguimiento de equipos y sus mantenimientos.
-Director: Acceso a la información completa de los equipos.
-Visitante: Acceso limitado al nombre y tipo de equipo.
-Enfermero: Acceso a la identificación del equipo, horas de uso y la posibilidad de reportar mal funcionamiento, modificar el sector y el estado asociado a los reportes.
-Mantenimiento: Acceso a los datos de identificación y observaciones de los equipos en relación a reportes de mal funcionamiento.
Integración con el HIS (Sistema de Información Hospitalaria): Los equipos se pueden asignar a pacientes en cada sector, permitiendo a Enfermería identificar y seleccionar equipos por número de serie (incluso sin lectores QR) directamente desde el HIS.
Clasificación de Equipos y Rango de Horas para Respiradores
Los equipos están clasificados en varios tipos (Transceptores, Monitores Multimétricos, Respiradores, etc.), y los respiradores, en particular, llevan un seguimiento exhaustivo de sus horas de uso. Su vida útil es de 30,000 horas, con los siguientes rangos de uso:

-Menos de 15,000 horas: Uso normal.
-Entre 15,000 y 25,000 horas: Requiere atención en su uso.
-Más de 25,000 horas: Alerta de mantenimiento.
**Configuración de Sectores**
Los equipos están distribuidos en sectores configurables (UTI, UCO, Quirófanos, Neonatología, etc.). Cada equipo puede ser movido o reasignado a otro sector según el tipo de usuario y la condición del equipo.

Esta documentación inicial puede evolucionar para incluir cualquier cambio necesario conforme el sistema se implemente y se adapte a los requerimientos específicos de la institución.
