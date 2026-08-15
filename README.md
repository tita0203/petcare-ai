# PetCare AI

> Conoce mejor la salud de tu mascota y mantén su historial siempre organizado.

PetCare AI es una aplicación para centralizar y organizar la información sanitaria de las mascotas. Permite gestionar vacunas, enfermedades, tratamientos, operaciones, recordatorios e historial reproductivo, además de compartir apartados específicos con profesionales veterinarios.

Incluye orientación personalizada mediante inteligencia artificial basada en los datos y antecedentes de la mascota, sin sustituir el diagnóstico ni la atención veterinaria.

## Problema que resuelve

La información sanitaria de una mascota suele estar repartida entre cartillas, informes, recetas, mensajes y distintas clínicas veterinarias.

Esto dificulta recordar próximas vacunas, consultar tratamientos anteriores o facilitar antecedentes completos a una nueva veterinaria.

PetCare AI busca reunir esa información en un único lugar para facilitar el seguimiento sanitario, conservar los antecedentes de la mascota y ofrecer recordatorios y orientación contextual basada en sus datos.

## Usuarios principales

- **Responsables de mascotas:** registran y gestionan las fichas y los historiales sanitarios.
- **Profesionales veterinarios:** consultan o actualizan exclusivamente los apartados autorizados por la persona responsable.
- **Administración:** gestiona los catálogos y las verificaciones necesarias.

## Funcionalidades del MVP

- Registro e inicio de sesión.
- Gestión de roles de responsable y profesional veterinario.
- Creación y edición de fichas de mascotas.
- Registro de una o varias razas para mascotas mestizas.
- Información sobre predisposiciones y cuidados según raza, tamaño y edad.
- Gestión de enfermedades, diagnósticos, alergias e intolerancias.
- Registro de tratamientos y medicación.
- Control de vacunas, desparasitaciones y próximas dosis.
- Registro de operaciones y esterilización.
- Historial reproductivo de embarazos y partos.
- Recordatorios sanitarios personalizables.
- Vinculación entre mascotas y profesionales veterinarios.
- Permisos específicos para cada apartado del historial.
- Registro básico de accesos y modificaciones.
- Orientación personalizada mediante inteligencia artificial.
- Recomendación de atención veterinaria cuando corresponda.

## Límites de la orientación mediante IA

PetCare AI ofrece información orientativa basada en los datos registrados de la mascota y en fuentes previamente seleccionadas.

La aplicación:

- No diagnostica enfermedades.
- No prescribe medicamentos.
- No indica ni modifica dosis.
- No sustituye la valoración de un profesional veterinario.
- No garantiza que un síntoma esté relacionado con un antecedente o una predisposición racial.
- Recomienda contactar con una clínica veterinaria ante señales de alarma o cuando no pueda ofrecer una orientación segura.

## Tecnologías

### En uso

- Java 21
- Spring Boot
- Spring Web
- Spring Data JPA
- MySQL
- Maven
- Git y GitHub

### Previstas

- Spring Security
- Bean Validation
- JUnit y Mockito
- Swagger / OpenAPI
- Docker
- Angular
- Integración con un servicio de inteligencia artificial

## Arquitectura

El backend se organizará mediante una arquitectura por capas:

- `controller`: entrada de peticiones HTTP.
- `service`: lógica y reglas de negocio.
- `repository`: acceso a la base de datos.
- `model`: entidades del dominio.
- `dto`: transferencia controlada de datos.
- `security`: autenticación y autorización.
- `exception`: gestión centralizada de errores.

## Estado del proyecto

🟡 En planificación y desarrollo inicial.

Actualmente se están definiendo el alcance del MVP, el modelo de datos, las reglas de negocio, las historias de usuario y la arquitectura inicial.

## Roadmap

- [x] Sprint 0 — Planificación y diseño del MVP
- [ ] Sprint 1 — Base del proyecto, usuarios y seguridad
- [ ] Sprint 2 — Mascotas y catálogo de razas
- [ ] Sprint 3 — Historial sanitario y reproductivo
- [ ] Sprint 4 — Vacunas, desparasitaciones y recordatorios
- [ ] Sprint 5 — Vinculación de profesionales veterinarios y permisos
- [ ] Sprint 6 — Orientación mediante inteligencia artificial
- [ ] Sprint 7 — Pruebas, documentación y preparación del MVP

## Funcionalidades futuras

- Verificación completa de profesionales y clínicas veterinarias.
- Gestión detallada de clínicas y horarios.
- Documentos e informes sanitarios adjuntos.
- Generación de informes sanitarios en PDF.
- Requisitos y listas de comprobación para viajar con mascotas.
- Inicio de sesión con Google y Apple.
- Aplicación móvil.
- Blog y foro por razas.
- Servicios de cuidadores.
- Adopciones.

## Autora

**Liliam Rocío Sánchez Martínez**

Desarrolladora web especializada en Java y en especialización en desarrollo backend con Spring Boot.

## Aviso

PetCare AI es un proyecto en desarrollo creado con fines educativos y de portfolio.

La información y la orientación proporcionadas por la aplicación no sustituyen el diagnóstico, el tratamiento ni la atención de un profesional veterinario.