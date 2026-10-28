# Sistema de Gestión Clínica Integral (prototipo)

Prototipo web del Proyecto Emprendedor "Diseño e Implementación de un Sistema de Gestión Clínica Integral para la Optimización de Procesos Administrativos y Atención al Paciente" (Universidad César Vallejo, Ingeniería de Sistemas).

## Qué hace

- Registro, búsqueda, edición y eliminación de **personas**, **pacientes** y **médicos**.
- Alta de una persona con su rol (paciente o médico) en una sola operación.
- **Citas** con control de choques de horario por médico y por paciente.
- Panel de inicio con totales, próximas citas y gráficos.
- Validaciones: DNI de 8 dígitos, CMP de 4 a 6 dígitos, sin duplicados de DNI, código de historia ni CMP.
- Control de acceso por rol: administrador (todo) y consulta (solo lectura).
- **Copia de seguridad:** el administrador puede descargar todos los datos en un archivo `.json` ("Descargar copia") y cargarlo en otro equipo o navegador ("Cargar copia"), lo que permite llevar los registros de una PC a otra.

## Cuentas de prueba

| Usuario  | Contraseña    | Rol           |
|----------|---------------|---------------|
| admin    | admin123      | Administrador |
| consulta | consulta123   | Consulta      |

## Uso

Abrir `index.html` en cualquier navegador, o entrar a la página publicada con GitHub Pages.

## Importante

- Los datos se guardan **solo en el navegador** de quien usa la página (no hay servidor).
- Los datos iniciales son **ficticios**. No ingresar datos reales de pacientes.
- Es un prototipo académico: las contraseñas están en el código y no deben usarse en un sistema real.
- Una implementación real requeriría revisar las normas de privacidad y protección de datos de salud.

