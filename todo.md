# TEAM MCP - Check-in de Asesorías - TODO

## Base de Datos
- [x] Crear tabla de clientes (id, nombre, código único, createdAt, updatedAt)
- [x] Crear tabla de check-ins (id, clientId, respuestas JSON, comentarios, createdAt)
- [x] Crear tabla de fotos (id, checkInId, storageKey, url, createdAt)
- [x] Ejecutar migraciones SQL

## Backend - APIs
- [x] API para crear cliente (solo admin)
- [x] API para listar clientes (solo admin)
- [x] API para actualizar cliente (solo admin)
- [x] API para eliminar cliente (solo admin)
- [x] API para obtener cliente por código (público)
- [x] API para crear check-in (público con código)
- [x] API para subir fotos a S3 (público con código)
- [x] API para listar check-ins de un cliente (solo admin)
- [x] API para obtener detalle de check-in (solo admin)
- [x] Implementar notificaciones automáticas al entrenador

## Frontend - Página de Acceso
- [x] Crear página de login por código
- [x] Validar código y redirigir a formulario

## Frontend - Formulario de Check-in
- [x] Crear formulario con 10 escalas 1-10
- [x] Agregar campo de comentarios
- [x] Implementar carga de múltiples fotos
- [x] Validar y enviar formulario
- [x] Mostrar confirmación de envío

## Frontend - Dashboard del Entrenador
- [x] Crear layout de dashboard con sidebar
- [x] Listar todos los clientes
- [x] Crear nuevo cliente (modal con nombre y código)
- [x] Renombrar cliente
- [x] Eliminar cliente (con confirmación)
- [x] Ver check-ins de cada cliente
- [x] Ver detalle de check-in con fotos
- [x] Mostrar fecha de envío

## Diseño Visual
- [x] Aplicar tema negro y rojo
- [x] Integrar logo de TEAM MCP
- [x] Tipografía bold y energética (Montserrat)
- [x] Responsive design
- [x] Animaciones suaves (transiciones CSS)

## Testing
- [x] Tests para APIs de clientes (validaciones en backend) - 23 tests pasando
- [x] Tests para APIs de check-ins (validaciones de código) - 23 tests pasando
- [x] Tests para autenticación por código (endpoint getByCode) - 23 tests pasando

## Deployment
- [x] Crear checkpoint final
- [x] Publicar aplicación (lista para publicar en Management UI)
