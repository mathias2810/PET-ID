
# PET-ID 🐾
## La identidad digital de tu mascota

PET-ID es un proyecto de emprendimiento tecnológico que busca desarrollar un sistema de identificación física y digital para perros y gatos, facilitando su identificación, la comunicación con sus propietarios y su recuperación en caso de pérdida.

El proyecto combina una placa física con código QR, un perfil digital, un sistema de reportes y herramientas de gestión para propietarios de mascotas.

---

## 📑 Índice

1. [Problema](#1-problema)
2. [Solución](#2-solución)
3. [Funcionamiento](#3-funcionamiento)
4. [Características principales](#4-características-principales)
5. [Perfil digital](#5-perfil-digital)
6. [Modo perdido](#6-modo-perdido)
7. [Tecnologías propuestas](#7-tecnologías-propuestas)
8. [Público objetivo](#8-público-objetivo)
9. [Modelo de negocio](#9-modelo-de-negocio)
10. [Desarrollo del prototipo](#10-desarrollo-del-prototipo)
11. [Pruebas y validación](#11-pruebas-y-validación)
12. [Cronograma](#12-cronograma)
13. [Plan de crecimiento](#13-plan-de-crecimiento)
14. [Visión del proyecto](#14-visión-del-proyecto)

---

## 1. Problema

Cuando un perro o gato se pierde, la persona que lo encuentra puede no saber quién es su propietario ni cómo contactarlo.

Los principales problemas son:

- La mascota puede encontrarse lejos de su hogar.
- La persona que la encuentra puede no utilizar redes sociales.
- Las publicaciones pueden tardar en llegar al propietario.
- El animal puede no llevar información de identificación.
- Los datos personales publicados pueden quedar expuestos.
- El propietario puede enterarse demasiado tarde.

PET-ID busca reducir estas dificultades mediante un sistema de identificación física conectado a una plataforma digital.

## 2. Solución

PET-ID no pretende ser únicamente una placa con un código QR. Su objetivo es crear un sistema integrado de identificación y recuperación de mascotas.

El producto estará compuesto por:

- Una placa física personalizada.
- Un código QR único para cada mascota.
- Un perfil digital accesible desde un navegador.
- Un sistema de contacto protegido.
- Un formulario para reportar mascotas encontradas.
- Un modo especial para mascotas perdidas.
- Un registro de reportes y escaneos.
- Funciones futuras para veterinarias y refugios.

La propuesta de valor es facilitar que una mascota identificada pueda regresar a casa mediante una interacción rápida, sencilla y segura.

## 3. Funcionamiento

El proceso básico de PET-ID será el siguiente:

1. El propietario registra a su mascota en la plataforma.
2. El sistema crea un perfil digital único.
3. Se genera un código QR vinculado al perfil.
4. El QR se coloca en una placa física.
5. Si la mascota se pierde, el propietario activa el modo perdido.
6. Una persona encuentra al animal y escanea el código.
7. Se abre el perfil digital de la mascota.
8. La persona puede enviar un reporte con un mensaje y una ubicación opcional.
9. El propietario recibe una notificación.
10. Cuando recupera a su mascota, puede desactivar el modo perdido.

El sistema funcionará desde el navegador, por lo que la persona que encuentre a la mascota no necesitará instalar una aplicación.

## 4. Características principales

### 4.1. Identificación mediante QR

Cada mascota tendrá un código QR único que abrirá su perfil digital.

Ejemplo de enlace:

`https://pet-id.ec/p/MX1842`

El enlace es ilustrativo. El dominio deberá registrarse y configurarse antes de utilizarlo.

### 4.2. Tecnología NFC

Como función opcional, la placa podrá incorporar tecnología NFC.

Esto permitirá que una persona acerque un teléfono compatible a la placa para abrir el perfil digital sin escanear el QR con la cámara.

El QR y el NFC dirigirán al mismo perfil.

### 4.3. Contacto protegido

PET-ID buscará facilitar la comunicación entre la persona que encuentra a la mascota y su propietario sin publicar directamente su número telefónico, correo electrónico o dirección particular.

### 4.4. Reportes de mascotas encontradas

La persona que encuentre una mascota podrá enviar:

- Ubicación aproximada o compartida voluntariamente.
- Fotografía opcional.
- Mensaje.
- Fecha y hora del reporte.
- Información adicional.

### 4.5. Historial de escaneos

El propietario podrá consultar los eventos registrados por el sistema, como la fecha y hora de un escaneo o de un reporte.

La ubicación solo estará disponible cuando se proporcione o se autorice su uso.

**Importante:** el QR y el NFC no incorporan GPS ni permiten rastrear continuamente a la mascota.

## 5. Perfil digital

Cada mascota tendrá una página individual con información autorizada por su propietario.

Ejemplo:

### 🐕 MAX

- **Especie:** Perro
- **Raza:** Golden Retriever
- **Edad:** 3 años
- **Sexo:** Macho
- **Ubicación general:** Quito
- **Características:** collar azul, mancha blanca en el pecho y temperamento amigable.

### Información adicional

- Fotografía de la mascota.
- Características físicas.
- Información veterinaria básica.
- Alergias o medicamentos relevantes, si el propietario decide incluirlos.
- Contacto protegido.
- Estado actual de la mascota.

Los datos sensibles no estarán disponibles públicamente por defecto.

## 6. Modo perdido

El propietario podrá activar el modo perdido desde su cuenta.

Cuando se active:

- El perfil mostrará un aviso de mascota perdida.
- Se destacarán las instrucciones para ayudar a encontrarla.
- Se habilitará el formulario de reporte.
- Se registrarán los eventos que el sistema pueda recopilar legítimamente.
- Se enviarán notificaciones al propietario cuando corresponda.

Ejemplo:

> 🚨 MAX ESTÁ PERDIDO
>
> Si lo encontraste, por favor ayúdalo a regresar a casa.
>
> Puedes enviar un reporte para que su propietario reciba la información.

Cuando la mascota sea recuperada, el propietario podrá marcar el incidente como resuelto.

## 7. Tecnologías propuestas

Las siguientes herramientas son opciones para desarrollar el prototipo:

| Componente | Tecnología propuesta | Función |
|---|---|---|
| Diseño visual | Figma | Diseñar las pantallas |
| Interfaz web | HTML, CSS y JavaScript | Crear el sitio web |
| Interfaz avanzada | React | Organizar componentes de la aplicación |
| Base de datos | Supabase | Almacenar información |
| Autenticación | Supabase Auth | Gestionar las cuentas |
| Código QR | Biblioteca de generación QR | Crear códigos únicos |
| Hosting | Vercel | Publicar el sitio |
| Notificaciones | Servicio de correo electrónico | Avisar de nuevos reportes |
| Control de versiones | Git y GitHub | Gestionar el código |

Estas tecnologías son propuestas de implementación. La selección definitiva dependerá de los conocimientos del equipo, los costos y los requisitos del proyecto.

## 8. Público objetivo

### Público inicial

Propietarios de perros y gatos de zonas urbanas de Quito que buscan una forma práctica de identificar a sus mascotas y facilitar su recuperación si se pierden.

### Clientes potenciales

1. Dueños de perros.
2. Dueños de gatos.
3. Refugios de animales.
4. Clínicas veterinarias.
5. Tiendas de mascotas.
6. Organizaciones de rescate animal.
7. Entrenadores y cuidadores de mascotas.

La primera etapa se enfocará en propietarios individuales para validar el producto antes de ampliar el servicio a organizaciones.

## 9. Modelo de negocio

PET-ID podría utilizar tres líneas comerciales.

### 🟢 PET-ID BASIC

- Placa con QR.
- Perfil digital.
- Contacto protegido.
- Modo perdido.
- Formulario de reportes.

### 🔵 PET-ID PLUS

- Placa premium.
- Opción NFC.
- Múltiples contactos.
- Personalización.
- Funciones digitales adicionales.

### 🟣 PET-ID PRO

Dirigido a veterinarias y refugios.

- Administración de múltiples mascotas.
- Registro de animales.
- Gestión de perfiles.
- Herramientas para organizaciones.
- Funciones administrativas adicionales.

Los precios definitivos deberán establecerse mediante cotizaciones y validación de la disposición de compra de los clientes.

### Fuentes de ingresos

1. Venta de placas físicas.
2. Placas personalizadas.
3. Funciones premium opcionales.
4. Planes para veterinarias y refugios.
5. Alianzas comerciales con negocios relacionados con mascotas.

## 10. Desarrollo del prototipo

El objetivo del prototipo será demostrar que el sistema puede funcionar de principio a fin.

### 10.1. Parte física

Fabricar entre 5 y 10 placas de prueba.

Materiales posibles:

- Acrílico.
- Aluminio.
- Acero inoxidable.

Cada placa deberá contar con un QR diferente y un enlace que abra el perfil correcto.

### 10.2. Parte digital

Desarrollar un sitio web con las siguientes páginas:

1. Página de inicio.
2. Registro e inicio de sesión.
3. Registro de mascotas.
4. Perfil público.
5. Panel del propietario.
6. Modo perdido.
7. Formulario para reportar una mascota encontrada.

### 10.3. Demostración

Durante la presentación del proyecto:

1. Se muestra una placa física.
2. Se escanea el QR con un teléfono.
3. Se abre el perfil de una mascota de prueba.
4. Se activa el modo perdido.
5. Se envía un reporte desde otro dispositivo.
6. Se muestra el reporte recibido por el propietario.

Esta demostración permitirá comprobar el funcionamiento real del producto.

## 11. Pruebas y validación

Antes de presentar el prototipo, se realizarán pruebas para comprobar que las funciones principales trabajan correctamente.

| Prueba | Resultado esperado |
|---|---|
| Escanear el QR | Abre el perfil correcto |
| Registrar una mascota | Guarda sus datos |
| Activar modo perdido | Muestra el aviso |
| Enviar un reporte | Registra la información |
| Enviar una notificación | El propietario recibe el aviso |
| Denegar ubicación | Permite enviar un reporte sin ubicación |
| Consultar datos privados | Bloquea accesos no autorizados |
| Marcar como recuperada | Desactiva el aviso de pérdida |

También se realizarán pruebas piloto con propietarios de mascotas para conocer la facilidad de uso, la confianza en el sistema y la intención de compra.

Los resultados deberán documentarse con evidencias reales.

## 12. Cronograma

Se propone un cronograma inicial de ocho semanas.

| Semana | Actividad |
|---|---|
| 1 | Investigación y encuestas |
| 2 | Diseño del producto y requisitos |
| 3 | Desarrollo inicial del sitio web |
| 4 | Perfiles, QR y modo perdido |
| 5 | Fabricación de placas |
| 6 | Integración y pruebas técnicas |
| 7 | Prueba piloto y correcciones |
| 8 | Documentación y exposición final |

El cronograma podrá ajustarse según la complejidad técnica y el tiempo disponible.

## 13. Plan de crecimiento

### Fase 1: Validación local

- Fabricar las primeras placas.
- Probar el sistema con 20 a 50 mascotas.
- Recoger comentarios de los propietarios.
- Corregir errores del prototipo.

### Fase 2: Expansión en Quito

- Establecer alianzas con veterinarias.
- Contactar tiendas de mascotas.
- Colaborar con refugios.
- Ampliar la base de usuarios.

### Fase 3: Expansión provincial

Extender el servicio a otros sectores de Pichincha según la demanda y los resultados del piloto.

### Fase 4: Expansión nacional

Evaluar la distribución de PET-ID en otras ciudades de Ecuador.

### Fase 5: Expansión internacional

Considerar otros mercados latinoamericanos una vez que el sistema sea sostenible y escalable.

La expansión dependerá de la demanda real, los costos, la calidad del servicio y la capacidad operativa.

## 14. Visión del proyecto

PET-ID busca crear una identidad digital única para cada mascota, conectando al animal con su propietario, información importante y una red de recuperación en caso de pérdida.

A largo plazo, la plataforma podría conectar:

- Mascotas.
- Propietarios.
- Veterinarias.
- Refugios.
- Tiendas de mascotas.
- Organizaciones de rescate.
- Comunidad.

La visión es construir una plataforma que facilite la identificación y el cuidado responsable de perros y gatos, utilizando tecnología accesible y priorizando la privacidad de los usuarios.

---

## 📌 Entregables finales

Al terminar el proyecto se espera contar con:

- Investigación y validación del problema.
- Definición del público objetivo.
- Propuesta de valor.
- Diseño de marca y placas.
- Sitio web funcional.
- Perfiles digitales de mascotas.
- Códigos QR únicos.
- Sistema de modo perdido y reportes.
- Placas físicas de prueba.
- Informe de pruebas y validación.
- Presupuesto y modelo de negocio.
- Demostración funcional del prototipo.

## Estado del proyecto

**Etapa actual:** planificación y diseño del proyecto.

**Próximo objetivo:** validar la necesidad del producto y construir un MVP funcional.

> PET-ID: una identidad digital para ayudar a que cada mascota pueda regresar a casa.

# PET-ID 🐾
## La identidad digital de tu mascota

PET-ID es un proyecto de emprendimiento tecnológico que busca desarrollar un sistema de identificación física y digital para perros y gatos, facilitando su identificación, la comunicación con sus propietarios y su recuperación en caso de pérdida.

El proyecto combina una placa física con código QR, un perfil digital, un sistema de reportes y herramientas de gestión para propietarios de mascotas.

---

## 📑 Índice

1. [Problema](#1-problema)
2. [Solución](#2-solución)
3. [Funcionamiento](#3-funcionamiento)
4. [Características principales](#4-características-principales)
5. [Perfil digital](#5-perfil-digital)
6. [Modo perdido](#6-modo-perdido)
7. [Tecnologías propuestas](#7-tecnologías-propuestas)
8. [Público objetivo](#8-público-objetivo)
9. [Modelo de negocio](#9-modelo-de-negocio)
10. [Desarrollo del prototipo](#10-desarrollo-del-prototipo)
11. [Pruebas y validación](#11-pruebas-y-validación)
12. [Cronograma](#12-cronograma)
13. [Plan de crecimiento](#13-plan-de-crecimiento)
14. [Visión del proyecto](#14-visión-del-proyecto)

---

## 1. Problema

Cuando un perro o gato se pierde, la persona que lo encuentra puede no saber quién es su propietario ni cómo contactarlo.

Los principales problemas son:

- La mascota puede encontrarse lejos de su hogar.
- La persona que la encuentra puede no utilizar redes sociales.
- Las publicaciones pueden tardar en llegar al propietario.
- El animal puede no llevar información de identificación.
- Los datos personales publicados pueden quedar expuestos.
- El propietario puede enterarse demasiado tarde.

PET-ID busca reducir estas dificultades mediante un sistema de identificación física conectado a una plataforma digital.

## 2. Solución

PET-ID no pretende ser únicamente una placa con un código QR. Su objetivo es crear un sistema integrado de identificación y recuperación de mascotas.

El producto estará compuesto por:

- Una placa física personalizada.
- Un código QR único para cada mascota.
- Un perfil digital accesible desde un navegador.
- Un sistema de contacto protegido.
- Un formulario para reportar mascotas encontradas.
- Un modo especial para mascotas perdidas.
- Un registro de reportes y escaneos.
- Funciones futuras para veterinarias y refugios.

La propuesta de valor es facilitar que una mascota identificada pueda regresar a casa mediante una interacción rápida, sencilla y segura.

## 3. Funcionamiento

El proceso básico de PET-ID será el siguiente:

1. El propietario registra a su mascota en la plataforma.
2. El sistema crea un perfil digital único.
3. Se genera un código QR vinculado al perfil.
4. El QR se coloca en una placa física.
5. Si la mascota se pierde, el propietario activa el modo perdido.
6. Una persona encuentra al animal y escanea el código.
7. Se abre el perfil digital de la mascota.
8. La persona puede enviar un reporte con un mensaje y una ubicación opcional.
9. El propietario recibe una notificación.
10. Cuando recupera a su mascota, puede desactivar el modo perdido.

El sistema funcionará desde el navegador, por lo que la persona que encuentre a la mascota no necesitará instalar una aplicación.

## 4. Características principales

### 4.1. Identificación mediante QR

Cada mascota tendrá un código QR único que abrirá su perfil digital.

Ejemplo de enlace:

`https://pet-id.ec/p/MX1842`

El enlace es ilustrativo. El dominio deberá registrarse y configurarse antes de utilizarlo.

### 4.2. Tecnología NFC

Como función opcional, la placa podrá incorporar tecnología NFC.

Esto permitirá que una persona acerque un teléfono compatible a la placa para abrir el perfil digital sin escanear el QR con la cámara.

El QR y el NFC dirigirán al mismo perfil.

### 4.3. Contacto protegido

PET-ID buscará facilitar la comunicación entre la persona que encuentra a la mascota y su propietario sin publicar directamente su número telefónico, correo electrónico o dirección particular.

### 4.4. Reportes de mascotas encontradas

La persona que encuentre una mascota podrá enviar:

- Ubicación aproximada o compartida voluntariamente.
- Fotografía opcional.
- Mensaje.
- Fecha y hora del reporte.
- Información adicional.

### 4.5. Historial de escaneos

El propietario podrá consultar los eventos registrados por el sistema, como la fecha y hora de un escaneo o de un reporte.

La ubicación solo estará disponible cuando se proporcione o se autorice su uso.

**Importante:** el QR y el NFC no incorporan GPS ni permiten rastrear continuamente a la mascota.

## 5. Perfil digital

Cada mascota tendrá una página individual con información autorizada por su propietario.

Ejemplo:

### 🐕 MAX

- **Especie:** Perro
- **Raza:** Golden Retriever
- **Edad:** 3 años
- **Sexo:** Macho
- **Ubicación general:** Quito
- **Características:** collar azul, mancha blanca en el pecho y temperamento amigable.

### Información adicional

- Fotografía de la mascota.
- Características físicas.
- Información veterinaria básica.
- Alergias o medicamentos relevantes, si el propietario decide incluirlos.
- Contacto protegido.
- Estado actual de la mascota.

Los datos sensibles no estarán disponibles públicamente por defecto.

## 6. Modo perdido

El propietario podrá activar el modo perdido desde su cuenta.

Cuando se active:

- El perfil mostrará un aviso de mascota perdida.
- Se destacarán las instrucciones para ayudar a encontrarla.
- Se habilitará el formulario de reporte.
- Se registrarán los eventos que el sistema pueda recopilar legítimamente.
- Se enviarán notificaciones al propietario cuando corresponda.

Ejemplo:

> 🚨 MAX ESTÁ PERDIDO
>
> Si lo encontraste, por favor ayúdalo a regresar a casa.
>
> Puedes enviar un reporte para que su propietario reciba la información.

Cuando la mascota sea recuperada, el propietario podrá marcar el incidente como resuelto.

## 7. Tecnologías propuestas

Las siguientes herramientas son opciones para desarrollar el prototipo:

| Componente | Tecnología propuesta | Función |
|---|---|---|
| Diseño visual | Figma | Diseñar las pantallas |
| Interfaz web | HTML, CSS y JavaScript | Crear el sitio web |
| Interfaz avanzada | React | Organizar componentes de la aplicación |
| Base de datos | Supabase | Almacenar información |
| Autenticación | Supabase Auth | Gestionar las cuentas |
| Código QR | Biblioteca de generación QR | Crear códigos únicos |
| Hosting | Vercel | Publicar el sitio |
| Notificaciones | Servicio de correo electrónico | Avisar de nuevos reportes |
| Control de versiones | Git y GitHub | Gestionar el código |

Estas tecnologías son propuestas de implementación. La selección definitiva dependerá de los conocimientos del equipo, los costos y los requisitos del proyecto.

## 8. Público objetivo

### Público inicial

Propietarios de perros y gatos de zonas urbanas de Quito que buscan una forma práctica de identificar a sus mascotas y facilitar su recuperación si se pierden.

### Clientes potenciales

1. Dueños de perros.
2. Dueños de gatos.
3. Refugios de animales.
4. Clínicas veterinarias.
5. Tiendas de mascotas.
6. Organizaciones de rescate animal.
7. Entrenadores y cuidadores de mascotas.

La primera etapa se enfocará en propietarios individuales para validar el producto antes de ampliar el servicio a organizaciones.

## 9. Modelo de negocio

PET-ID podría utilizar tres líneas comerciales.

### 🟢 PET-ID BASIC

- Placa con QR.
- Perfil digital.
- Contacto protegido.
- Modo perdido.
- Formulario de reportes.

### 🔵 PET-ID PLUS

- Placa premium.
- Opción NFC.
- Múltiples contactos.
- Personalización.
- Funciones digitales adicionales.

### 🟣 PET-ID PRO

Dirigido a veterinarias y refugios.

- Administración de múltiples mascotas.
- Registro de animales.
- Gestión de perfiles.
- Herramientas para organizaciones.
- Funciones administrativas adicionales.

Los precios definitivos deberán establecerse mediante cotizaciones y validación de la disposición de compra de los clientes.

### Fuentes de ingresos

1. Venta de placas físicas.
2. Placas personalizadas.
3. Funciones premium opcionales.
4. Planes para veterinarias y refugios.
5. Alianzas comerciales con negocios relacionados con mascotas.

## 10. Desarrollo del prototipo

El objetivo del prototipo será demostrar que el sistema puede funcionar de principio a fin.

### 10.1. Parte física

Fabricar entre 5 y 10 placas de prueba.

Materiales posibles:

- Acrílico.
- Aluminio.
- Acero inoxidable.

Cada placa deberá contar con un QR diferente y un enlace que abra el perfil correcto.

### 10.2. Parte digital

Desarrollar un sitio web con las siguientes páginas:

1. Página de inicio.
2. Registro e inicio de sesión.
3. Registro de mascotas.
4. Perfil público.
5. Panel del propietario.
6. Modo perdido.
7. Formulario para reportar una mascota encontrada.

### 10.3. Demostración

Durante la presentación del proyecto:

1. Se muestra una placa física.
2. Se escanea el QR con un teléfono.
3. Se abre el perfil de una mascota de prueba.
4. Se activa el modo perdido.
5. Se envía un reporte desde otro dispositivo.
6. Se muestra el reporte recibido por el propietario.

Esta demostración permitirá comprobar el funcionamiento real del producto.

## 11. Pruebas y validación

Antes de presentar el prototipo, se realizarán pruebas para comprobar que las funciones principales trabajan correctamente.

| Prueba | Resultado esperado |
|---|---|
| Escanear el QR | Abre el perfil correcto |
| Registrar una mascota | Guarda sus datos |
| Activar modo perdido | Muestra el aviso |
| Enviar un reporte | Registra la información |
| Enviar una notificación | El propietario recibe el aviso |
| Denegar ubicación | Permite enviar un reporte sin ubicación |
| Consultar datos privados | Bloquea accesos no autorizados |
| Marcar como recuperada | Desactiva el aviso de pérdida |

También se realizarán pruebas piloto con propietarios de mascotas para conocer la facilidad de uso, la confianza en el sistema y la intención de compra.

Los resultados deberán documentarse con evidencias reales.

## 12. Cronograma

Se propone un cronograma inicial de ocho semanas.

| Semana | Actividad |
|---|---|
| 1 | Investigación y encuestas |
| 2 | Diseño del producto y requisitos |
| 3 | Desarrollo inicial del sitio web |
| 4 | Perfiles, QR y modo perdido |
| 5 | Fabricación de placas |
| 6 | Integración y pruebas técnicas |
| 7 | Prueba piloto y correcciones |
| 8 | Documentación y exposición final |

El cronograma podrá ajustarse según la complejidad técnica y el tiempo disponible.

## 13. Plan de crecimiento

### Fase 1: Validación local

- Fabricar las primeras placas.
- Probar el sistema con 20 a 50 mascotas.
- Recoger comentarios de los propietarios.
- Corregir errores del prototipo.

### Fase 2: Expansión en Quito

- Establecer alianzas con veterinarias.
- Contactar tiendas de mascotas.
- Colaborar con refugios.
- Ampliar la base de usuarios.

### Fase 3: Expansión provincial

Extender el servicio a otros sectores de Pichincha según la demanda y los resultados del piloto.

### Fase 4: Expansión nacional

Evaluar la distribución de PET-ID en otras ciudades de Ecuador.

### Fase 5: Expansión internacional

Considerar otros mercados latinoamericanos una vez que el sistema sea sostenible y escalable.

La expansión dependerá de la demanda real, los costos, la calidad del servicio y la capacidad operativa.

## 14. Visión del proyecto

PET-ID busca crear una identidad digital única para cada mascota, conectando al animal con su propietario, información importante y una red de recuperación en caso de pérdida.

A largo plazo, la plataforma podría conectar:

- Mascotas.
- Propietarios.
- Veterinarias.
- Refugios.
- Tiendas de mascotas.
- Organizaciones de rescate.
- Comunidad.

La visión es construir una plataforma que facilite la identificación y el cuidado responsable de perros y gatos, utilizando tecnología accesible y priorizando la privacidad de los usuarios.

---

## 📌 Entregables finales

Al terminar el proyecto se espera contar con:

- Investigación y validación del problema.
- Definición del público objetivo.
- Propuesta de valor.
- Diseño de marca y placas.
- Sitio web funcional.
- Perfiles digitales de mascotas.
- Códigos QR únicos.
- Sistema de modo perdido y reportes.
- Placas físicas de prueba.
- Informe de pruebas y validación.
- Presupuesto y modelo de negocio.
- Demostración funcional del prototipo.

## Estado del proyecto

**Etapa actual:** planificación y diseño del proyecto.

**Próximo objetivo:** validar la necesidad del producto y construir un MVP funcional.

> PET-ID: una identidad digital para ayudar a que cada mascota pueda regresar a casa.
