**Introducción:**

El proyecto consiste en el desarrollo de una aplicación web con enfoque móvil. Se trata de una plataforma de gestión de alquiler de habitaciones de una vivienda, con dos roles principales: el propietario de las habitaciones y los inquilinos.

**Razón para desarrollar el software:**

La iniciativa de crear este software surge de la necesidad de proporcionar a los inquilinos una plataforma centralizada donde puedan acceder a su historial, generar comprobantes y realizar pagos de manera automatizada. De manera simultánea, los propietarios de las habitaciones podrán gestionar la disponibilidad de sus cuartos, realizar un seguimiento de ocupación, y llevar a cabo otras funciones administrativas esenciales.

**Objetivos del Proyecto:**

El conjunto de objetivos establecidos para el proyecto se enfoca en lograr una implementación exitosa de la aplicación de gestión de alquiler de habitaciones. Cada objetivo se ha delineado cuidadosamente para asegurar un desarrollo eficiente y satisfacer las necesidades tanto de los inquilinos como de los propietarios. Estos objetivos específicos son los siguientes:

1. **Implementar un sistema de historial de alquiler:**

   - Establecer una funcionalidad que permita a los inquilinos revisar su historial de alquiler de manera detallada, incluyendo fechas, pagos realizados y cuartos ocupados, contribuyendo así a una gestión más efectiva.

1. **Automatizar el proceso de generación de comprobantes:**

   - Facilitar a los inquilinos la generación automática de comprobantes de pago, proporcionando a su vez a los propietarios un registro detallado de transacciones para una administración financiera eficiente.

1. **Establecer un Sistema de Pago Inicial a través de Códigos QR:)**

Implementar la opción de pago mediante códigos QR (Yape o Plin), permitiendo a los inquilinos realizar transacciones de alquiler de manera eficiente y segura. Los usuarios deberán proporcionar una imagen del comprobante de pago, el cual será validado por el propietario a través de la plataforma.

- Desarrollo Futuro:
  Explorar la integración de pasarelas de pago automatizado para ofrecer una solución más conveniente y ágil en fases posteriores del proyecto.

1. **Proporcionar un Detalle Transparente del Cálculo de la Renta Final:**

   - Permitir a los inquilinos acceder a un desglose claro y detallado del cálculo de su renta final, incluyendo costos fijos acordados (agua y cuarto) y especificaciones detalladas del consumo eléctrico individualizado basado en medidores, asegurando transparencia y comprensión total del costo asociado al alquiler.

1. **Gestionar la disponibilidad de habitaciones:**
   - Posibilitar a los propietarios la actualización sencilla de la disponibilidad de sus habitaciones, ofreciendo notificaciones oportunas sobre solicitudes de alquiler y optimizando la gestión de ocupación.

Cada uno de estos objetivos contribuirá de manera significativa al éxito y funcionalidad integral de la aplicación de gestión de alquiler de habitaciones.

**Requisitos del sistema**

Basándome en los objetivos proporcionados, puedo ayudarte a derivar algunos requisitos para cada uno:

1. **Implementar un sistema de historial de alquiler:**

   - **Requisitos Funcionales:**

     - El sistema debe permitir a los inquilinos ver un historial detallado de sus alquileres.
     - Debe mostrar información como fechas de alquiler, pagos realizados y cuartos ocupados.
     - Los inquilinos deben poder acceder a esta información de manera clara y fácil.

   - **Requisitos No Funcionales:**
     - La interfaz de usuario debe ser intuitiva para facilitar la navegación del historial.
     - La información debe estar actualizada en tiempo real para una gestión efectiva.

2. **Automatizar el proceso de generación de comprobantes:**

   - **Requisitos Funcionales:**

     - Los inquilinos deben poder generar comprobantes de pago de manera automática desde la plataforma.
     - El sistema debe registrar de manera detallada cada transacción financiera realizada.
     - Los propietarios deben tener acceso a un registro centralizado de transacciones para administrar eficientemente las finanzas.

   - **Requisitos No Funcionales:**
     - El proceso de generación de comprobantes debe ser rápido y eficiente.
     - La plataforma debe garantizar la seguridad y confidencialidad de los datos financieros.

3. **Establecer un Sistema de Pago Inicial a través de Códigos QR:**

   - **Requisitos Funcionales:**

     - El sistema debe proporcionar códigos QR (Yape o Plin) para realizar transacciones de alquiler.
     - Los inquilinos deben poder adjuntar imágenes de comprobantes de pago para validación.
     - Los propietarios deben poder validar los pagos utilizando la imagen proporcionada por los inquilinos.

   - **Requisitos No Funcionales:**
     - La plataforma debe garantizar la integridad y seguridad del proceso de pago.
     - La validación de pagos debe realizarse de manera oportuna.

4. **Proporcionar un Detalle Transparente del Cálculo de la Renta Final:**

   - **Requisitos Funcionales:**

     - La plataforma debe mostrar un desglose claro del cálculo de la renta final para cada inquilino.
     - Debe incluir costos fijos (agua y cuarto) y detalles del consumo eléctrico individualizado.
     - Los inquilinos deben tener fácil acceso a esta información.

   - **Requisitos No Funcionales:**
     - La presentación del desglose debe ser comprensible y fácil de interpretar.
     - Los datos de consumo eléctrico deben actualizarse de manera regular para reflejar la situación actual.

5. **Gestionar la disponibilidad de habitaciones:**

   - **Requisitos Funcionales:**
     - Los propietarios deben poder actualizar la disponibilidad de sus habitaciones fácilmente.
     - La plataforma debe enviar notificaciones oportunas a los propietarios sobre solicitudes de alquiler y cambios en la disponibilidad.
   - **Requisitos No Funcionales:**
     - Las notificaciones deben ser entregadas de manera rápida y confiable.
     - La interfaz de gestión de disponibilidad debe ser intuitiva para una fácil administración.

### Desarrollo:

**Tecnologías Utilizadas:**

- **Frontend:**

  - React con Next.js para una experiencia web eficiente y reactiva.
  - Chakra UI como biblioteca UI centrada en la visualización de información de manera responsiva.

- **Backend:**
  - Nest.js para una arquitectura de servidor escalable y modular.
  - Prisma como ORM para simplificar las operaciones de la base de datos.
  - PostgreSQL como base de datos para asegurar robustez y rendimiento.

**Arquitectura de Desarrollo:**

- Utilización de la arquitectura modular proporcionada por Nest.js.
- Estructuración del código fuente para facilitar la mantenibilidad y escalabilidad.

**Módulos y Funcionalidades Clave:**

1. **Historial de Alquiler:**

   - Implementación de un módulo para que los inquilinos revisen su historial detallado de alquiler.

2. **Generación Automática de Comprobantes:**

   - Desarrollo de un módulo que permita a los inquilinos generar comprobantes de pago de manera automática.

3. **Sistema de Pago a través de Códigos QR:**

   - Integración de códigos QR (Yape o Plin) para transacciones de alquiler.
   - Validación de pagos mediante imágenes de comprobantes.

4. **Detalle Transparente del Cálculo de Renta:**

   - Desarrollo de un módulo que muestre un desglose claro del cálculo de la renta final para cada inquilino.

5. **Gestión de Disponibilidad de Habitaciones:**
   - Implementación de un módulo que permita a los propietarios actualizar fácilmente la disponibilidad de sus habitaciones.

**Colaboración y Control de Versiones:**

- Colaboración mediante plataformas como GitHub.
- Utilización de Git como herramienta de control de versiones para rastrear y gestionar cambios en el código.

**Cronograma de Desarrollo:**

- División del desarrollo en hitos para facilitar el seguimiento del progreso.
- Establecimiento de un cronograma básico para las diferentes fases del desarrollo.

**Pruebas Unitarias:**

- Implementación de pruebas unitarias para asegurar el correcto funcionamiento de cada componente de manera individual.

**Integración Continua:**

- Consideración de prácticas de integración continua para detectar problemas tempranamente durante el desarrollo.
