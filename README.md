# ECUAEXPLORE - App Móvil de Turismo Ciudadano

## Descripción

La empresa de desarrollo **El Búho** presenta *ECUAEXPLORE*, una aplicación móvil orientada al turismo ciudadano. La app permite a los usuarios explorar y compartir sitios turísticos en Ecuador a través de un microblog interactivo, reseñas y fotografías.

---

## Funcionalidades principales

- ✅ Registro e inicio de sesión de usuarios (Soporte para roles: Publicador y Visitante)
- ✅ Publicación de entradas (lugares turísticos) en el microblog
- ✅ Subida de imágenes (hasta 5 fotos por sitio), desde la cámara o galería
- ✅ Validación de tamaño y tipo de archivo en las fotos
- ✅ Redacción de reseñas sobre sitios turísticos
- ✅ Responder a reseñas existentes

---

## Perfiles de usuario

### Visitante

- Puede visualizar contenido (lugares, fotos y reseñas)
- No puede publicar entradas ni responder

### Publicador

- Puede crear lugares turísticos
- Puede subir fotos y agregar ubicaciones
- Puede escribir y responder reseñas

---

## Tecnologías utilizadas

- **Frontend**: Flutter
- **Backend**: Supabase
- **Autenticación**: Supabase Auth
- **Almacenamiento**: Supabase Storage (para imágenes)
- **Base de datos**: Supabase Postgres

---

## Flujos principales

### Registro e inicio de sesión

- Usuarios pueden registrarse como publicadores (con nombre, email y contraseña)
- Visitantes pueden ingresar sin registro

### Publicación de lugares

- Crear lugares con nombre, descripción, calificación y fotos
- Agregar ubicación actual (enlace a Google Maps)

### Reseñas

- Usuarios pueden dejar reseñas en lugares
- Publicadores pueden responder a reseñas

---

## Estructura del repositorio sugerida

```
/lib
  ├── login_page.dart
  ├── turismo_page.dart
  ├── detalle_lugar.dart
  ├── services
       ├── auth_service.dart
       ├── image_service.dart
       ├── location_service.dart
```

Incluye además:

- Documentación técnica
- Capturas de pantalla (adjuntar en carpeta `/screenshots`)

---

## Entregables

- ✅ APK funcional para dispositivos Android
- ✅ Repositorio GitHub con código fuente completo

---

## Capturas sugeridas

- Registro e inicio de sesión
  ![IMG-20250708-WA0028](https://github.com/user-attachments/assets/a4abf36c-d4cd-465e-af9e-abe276bae833)
  ![IMG-20250708-WA0027](https://github.com/user-attachments/assets/21745699-42f0-4df0-88b3-a1e1dc37faa7)

  
- Pantalla principal (lista de lugares)
  <img width="160" alt="imagen lugares " src="https://github.com/user-attachments/assets/2244a662-71db-410e-8f3c-37ef6acba098" />


- Formulario para agregar lugar
  ![IMG-20250708-WA0025](https://github.com/user-attachments/assets/cb249ba0-f047-4108-ac73-ce1644016c26)


- Vista de detalle de lugar (reseñas y fotos)
  <img width="163" alt="imagen lugar" src="https://github.com/user-attachments/assets/9db512fa-b402-4a0b-95fd-60a2fa7f3daf" />
  ![IMG-20250708-WA0026](https://github.com/user-attachments/assets/fc662c7f-48c4-4204-8490-d3ccf6979abe)


- Respuesta a reseñas
![IMG-20250708-WA0024](https://github.com/user-attachments/assets/b3b27993-9ad0-4b05-ae13-da50ac73928f)
![IMG-20250708-WA0023](https://github.com/user-attachments/assets/5f3d2c35-0bed-4c33-b5b9-967eba2e8bf1)
![IMG-20250708-WA0029](https://github.com/user-attachments/assets/246a5042-54c5-4f58-baba-33e22a2061c7)


---

## Créditos

De: Isaac Quinapallo 

