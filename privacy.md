# Política de Privacidad — Viktot Bot

**Fecha de Vigencia:** 17 de Agosto de 2026

Esta Política de Privacidad explica cómo **Viktot Bot** ("el Bot") recopila, utiliza y almacena información cuando interactúas con él en Discord.

## 1) Qué Hace Viktot Bot
Viktot Bot es un bot complementario a Pokétwo que proporciona nombres de apariciones de Pokémon y características opcionales que ayudan a los usuarios a gestionar **Collections** y **Shiny Hunts**, incluido el comportamiento de notificación configurable por servidor.

## 2) Información que Recopilamos y Procesamos

### A) Identificadores de Discord (almacenados)
Viktot Bot almacena identificadores de Discord para asociar configuraciones con el usuario/servidor correcto y operar características del servidor:
- IDs de Usuario
- IDs de Servidor (Guild)
- IDs de Canal (para ciertas configuraciones de servidor)
- IDs de Mensaje (para ciertas características operativas, como correlacionar eventos de aparición y respuestas del bot)

### B) Contenido de mensajes (procesado; almacenamiento limitado)
Viktot Bot procesa contenido de mensajes **en servidores donde está instalado**:
- **Mensajes de Pokétwo** (p. ej., mensajes de aparición/captura) para identificar apariciones y proporcionar nombres/notificaciones.
- **Mensajes de comando del usuario** dirigidos a Viktot Bot (p. ej., `!bot …`) para establecer o modificar preferencias del usuario y configuración del servidor.

**Sin Mensajes Directos:** Viktot Bot **no** proporciona características basadas en DM y **no** procesa intencionalmente mensajes directos.

### C) Imágenes (procesadas transitoriamente)
Viktot Bot descarga temporalmente imágenes asociadas a apariciones de Pokétwo para clasificación/nombres. Estas imágenes se usan para procesamiento inmediato y **no se guardan en disco** para retención a largo plazo en producción.

### D) Datos de preferencia de usuario y configuración de servidor (almacenados en SQLite)
Viktot Bot almacena datos operacionales del bot como:
- Selecciones de Shiny Hunt
- Entradas de Collection
- Alternancias de preferencia AFK (si recibes notificaciones de Shiny Hunt / Colección)
- Alternancias de preferencia de Región/tipo (si está habilitado)
- Configuración de notificaciones de captura (si está habilitado)
- Configuración del servidor (p. ej., configuración de notificaciones de rol, categorías, opciones/indicadores de características, canales excluidos)

### E) Diagnósticos y registros operativos (pueden almacenarse)
Viktot Bot puede almacenar registros operativos para mejorar la confiabilidad y el rendimiento. Estos registros pueden incluir:
- Trazas de error
- Métricas de rendimiento básicas e información de tiempo
- Registros necesarios para correlacionar respuestas del bot a eventos (p. ej., IDs de mensaje/marcas de tiempo)

## 3) Cómo Usamos la Información
Utilizamos la información recopilada/procesada para:
- Proporcionar nombres de apariciones y características relacionadas
- Almacenar y aplicar configuraciones de usuario (Collections/Shiny Hunt e alternancias de preferencia)
- Almacenar y aplicar configuración del servidor (roles/categorías/opciones)
- Prevenir abusos, mantener seguridad, diagnosticar problemas y mejorar confiabilidad/rendimiento

## 4) Retención y Eliminación de Datos
**Política de retención:** retenido **hasta eliminarse**.

- Si un usuario borra sus configuraciones de collections o Shiny Hunt, las entradas correspondientes se eliminan de la base de datos y **no son recuperables** (no se mantiene copia de seguridad para collections/Shiny Hunt borradas).
- Los datos de configuración del servidor pueden eliminarse cuando se remove el Bot de un servidor, o por solicitud de administradores del servidor (donde sea posible).

## 5) Intercambio y Divulgación
**No** vendemos, alquilamos ni comercializamos información.

Podemos divulgar información solo:
- Cuando sea necesario para operar el Bot en su infraestructura de alojamiento (alojado en un servidor personal de DigitalOcean)
- Si lo requiere la ley o un proceso legal válido
- Para proteger la seguridad e integridad del Bot y sus usuarios

## 6) Seguridad
Tomamos medidas razonables para proteger los datos almacenados mediante controles de acceso y salvaguardas operativas. Ningún sistema es perfectamente seguro.

## 7) Privacidad de Menores / Edad
Viktot Bot es un bot de servicio de propósito general y no incluye características específicas por edad. Los usuarios deben cumplir con los requisitos de edad mínima de Discord y cumplir con sus políticas.

## 8) Contacto y Solicitudes
Para solicitar la eliminación de datos almacenados asociados con tu ID de usuario de Discord o para hacer preguntas sobre privacidad, contacta:

**Correo:** uca1111@hotmail.com  
Incluye tu ID de usuario de Discord e (si aplica) el ID de servidor (guild) relevante para ayudar a localizar registros.

## 9) Cambios
Podemos actualizar esta Política de Privacidad de vez en cuando. Las actualizaciones se reflejarán actualizando la Fecha de Vigencia anterior.
