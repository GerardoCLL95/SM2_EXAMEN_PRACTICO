# SM2_EXAMEN_PRACTICO

## 🔗 Repositorio del Proyecto

👉 https://github.com/GerardoCLL95/SM2_EXAMEN_PRACTICO

## 🧾 Descripción del Proyecto

Este proyecto consiste en la implementación de dos historias de usuario seleccionadas del Product Backlog de un sistema de asistencia con autenticación biométrica. Las funcionalidades implementadas son:

### ✅ Historia 1: Registro de empleados con datos biométricos
- Permite al administrador registrar nuevos empleados, incluyendo su información biométrica como  reconocimiento facial.

### ✅ Historia 2: Marcar asistencia con geolocalización y reconocimiento facial
- Permite a los empleados registrar su asistencia utilizando su ubicación GPS y autenticación facial.

## 🖼️ Capturas de Pantalla

### Registro de empleados
![WhatsApp Image 2025-05-21 at 3 14 53 PM (2)](https://github.com/user-attachments/assets/af8df1dd-5e8e-4423-bafb-e987718356ea)
![image](https://github.com/user-attachments/assets/8d3c38c9-5b32-4c19-a97f-3d7dc2df9dc1)
### Marcar asistencia
> Las imágenes deben guardarse en una carpeta llamada `capturas/` dentro del repositorio.
![WhatsApp Image 2025-05-21 at 3 14 53 PM](https://github.com/user-attachments/assets/c99eba9a-9345-4583-9ec6-a8ae4a11edd8)
![WhatsApp Image 2025-05-21 at 3 14 53 PM (1)](https://github.com/user-attachments/assets/9e9f5a3a-8994-43bd-9592-31c156698cf0)
![WhatsApp Image 2025-05-21 at 3 15 44 PM](https://github.com/user-attachments/assets/32ba34bb-478b-4bd7-9fee-05143e69b9f9)
## 🔗 Enlaces y Referencias

- [Flutter](https://flutter.dev/) – Framework para construir interfaces móviles
- [Google Maps API](https://developers.google.com/maps/documentation)
- [Face Recognition Plugin](https://pub.dev/packages/face_camera) – Para reconocimiento facial en Flutter
- [Firebase](https://firebase.google.com/) – Backend para autenticación y almacenamiento


## 🔗 PARA COMPILAR Y EJECUTAR EL PROYECTO EN FLUTTER

1. Requisitos Previos
Asegúrate de tener instalado:

Flutter SDK
👉 https://docs.flutter.dev/get-started/install

Android Studio (para emulador y SDK de Android)

Visual Studio Code
Con las extensiones:

Flutter

Dart

Emulador Android o un dispositivo físico conectado (con depuración USB activada)

## 🔗 Instalar Dependencias

flutter pub get

Esto descargará todas las librerías necesarias declaradas en pubspec.yaml.

## Verificar el Dispositivo Disponible

Para ver si hay un emulador o dispositivo físico conectado: flutter devices 
y para ejecutar: flutter run

## Probar Funcionalidades Implementadas
Una vez que la app esté corriendo:

## Historia 1: Registro de empleados con datos biométricos

1. Ingresar como administrador a la aplicacion en acceso admin

Usuario: admin
contraseña: 123456

2. ir a la pestaña inferior de empleados
3. darle a agregar empleado ubicado en la parte inferior derecha
4. se llena los datos
5. se da a guardar empleado

## Historia 2: Marcar asistencia con geolocalización y reconocimiento facial

1. una vez registrado el empleado, salimos como admin
2. ahora entramos a registro de usuario
3. ingresamos la identificacion (DNI)
4. tomamos una foto de verificacion
5. y marcamos entrada
