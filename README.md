# 🗂️ Sistema de Registro de Usuarios

## 📎 Descripción del Caso

El sistema de registro de usuarios es una herramienta diseñada para permitir la creación, administración y control de cuentas dentro de una plataforma digital. Su propósito es almacenar información personal de forma segura y brindar acceso a funcionalidades protegidas mediante autenticación.

Incluye procesos como creación de cuentas, inicio de sesión, edición de perfil, recuperación de contraseña y administración de usuarios.  
Este sistema es fundamental para la seguridad y personalización de la experiencia del usuario.

---

## 🎯 Objetivo

El objetivo del sistema es ofrecer una plataforma segura donde los usuarios puedan registrarse, iniciar sesión y gestionar su información personal de manera intuitiva.

También busca garantizar que cada usuario tenga acceso únicamente a los recursos que le corresponden mediante validaciones correctas.

La interfaz del sistema debe facilitar la modificación de datos, consulta de información y recuperación de credenciales sin complicaciones.

---

## 🧵 Tabla de Pruebas – Casos de Prueba Unitaria

| Requerimiento asociado | Datos de entrada | Resultado esperado | Resultado obtenido |
|------------------------|------------------|--------------------|--------------------|
| Registro de usuarios | **Nombre:** Luis <br> **Apellido:** Molina <br> **Correo:** lmolina@example.com <br> **Contraseña:** 44332211 | El usuario debe registrarse correctamente. | La cuenta se creó exitosamente. |
| Consulta del perfil | **Dirección:** San Joaquín <br> **Fecha de nacimiento:** 28/07/2002 | Mostrar los datos del usuario. | La información se mostró sin errores. |
| Inicio de sesión | **Correo:** lmolina@example.com <br> **Contraseña:** 44332211 | Validar credenciales e ingresar. | Acceso permitido. |

---

## 📑 Tabla de Casos de Validación

| Requerimiento asociado | Datos de entrada | Resultado esperado | Resultado obtenido |
|------------------------|------------------|--------------------|--------------------|
| Eficiencia del sistema | Datos del usuario guardados | Procesos rápidos y estables. | El sistema respondió de manera eficiente. |
| Recuperación ante errores | Solicitud de restablecimiento | Envío seguro de enlace o código. | La recuperación se realizó correctamente. |

---

## 🧩 Tipo de Mantenimiento Propuesto

### 🛠️ Mantenimiento Adaptativo

---

## 📘 Descripción del Caso

A medida que el entorno tecnológico evoluciona, el sistema debe adaptarse para mantenerse funcional y compatible con nuevas herramientas, normativas y requerimientos del entorno.

En este caso, se han detectado necesidades como:

- Actualización de la API usada para autenticación.
- Compatibilidad con navegadores modernos.
- Adecuación del sistema a nuevas políticas de seguridad.
- Adaptación del backend a versiones actualizadas del servidor o framework.
- Inclusión de nuevos formatos de datos requeridos por la plataforma.

Estos cambios no se deben a fallos del sistema, sino a la necesidad de que se adapte al entorno actual para seguir funcionando correctamente.

---

## 🎯 Objetivos del Mantenimiento Adaptativo

- Actualizar componentes que quedaron obsoletos.
- Asegurar compatibilidad con nuevas versiones de software y hardware.
- Fortalecer la seguridad conforme a normas recientes.
- Ajustar el sistema a cambios externos sin alterar su funcionalidad principal.
- Optimizar el rendimiento con tecnologías más recientes.

---

## 🧷 Requerimientos para el Mantenimiento

### 🔧 Requerimientos Técnicos

- Actualizar librerías y dependencias del backend y frontend.
- Ajustar el código para utilizar nuevas versiones de la API de autenticación.
- Implementar compatibilidad con nuevos navegadores y dispositivos.
- Revisar la estructura de la base de datos según los nuevos estándares.
- Aplicar mejoras de seguridad exigidas por la plataforma o el servidor.

### 🗃️ Requerimientos Operativos

- Realizar pruebas de compatibilidad tras cada actualización.
- Documentar los cambios y versiones aplicadas.
- Probar la integración completa antes de subirla a producción.
- Mantener comunicación con los administradores de infraestructura.
- Realizar respaldos para evitar pérdida de información durante el proceso.

---

## 🧪 Tabla de Pruebas Funcionales

| Caso de Prueba | Resultado Esperado | Validación |
|----------------|---------------------|-----------|
| Actualización de API | El sistema debe conectarse correctamente con la nueva API. | La conexión fue exitosa. |
| Compatibilidad con navegadores | Interfaz funcional en versiones modernas. | Se visualizó correctamente en todos los navegadores probados. |
| Seguridad reforzada | El sistema debe cumplir nuevas normas de seguridad. | Las validaciones se aplicaron correctamente. |

---

## 🔁 Reflexión sobre el Control de Versiones

El control de versiones es esencial cuando se realizan mejoras adaptativas.  
Permite gestionar cada actualización, revertir cambios si algo falla y trabajar ordenadamente en nuevas ramas sin alterar la versión estable.

Además, facilita la coordinación del equipo, el seguimiento de dependencias y la documentación de cada etapa del mantenimiento.

---

## 🏆 Conclusión

El mantenimiento adaptativo permitirá que el sistema continúe funcionando de forma óptima, segura y compatible con los avances tecnológicos del entorno.

Actualizar componentes, mejorar la seguridad y adaptar el sistema a nuevas APIs garantiza una mayor vida útil del software y una experiencia de usuario confiable.

El control de versiones complementa este proceso, haciendo las actualizaciones más seguras, ordenadas y rastreables.

