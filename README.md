# basic_ios_app4

## 📱 Descripción
Este proyecto es una aplicación iOS que utiliza varias librerías para autenticación, redes, manejo de imágenes, integración con Facebook y más.

## 📦 Librerías Importadas
El proyecto usa **Swift Package Manager (SPM)** para la gestión de dependencias. A continuación, se detallan las librerías incluidas:

### 🔹 **Frameworks de Capacitor y Cordova**
- **Capacitor** → Plataforma para crear aplicaciones híbridas con integración de Web y nativo.

### 🔹 **SDK de Facebook**
Las siguientes librerías provienen del SDK de Facebook:
- **FBAEMKit** → Atribución de eventos en Facebook Ads.
- **FBSDKCoreKit** → Funcionalidades básicas del SDK de Facebook.
- **FBSDKLoginKit** → Implementación de autenticación con Facebook Login.
- **FBSDKShareKit** → Compartición de contenido en Facebook.

### 🔹 **Gestión de Imágenes y Galerías**
- **DKImagePickerController** → Selector de imágenes avanzado para iOS.
- **DKPhotoGallery** → Visor de imágenes con múltiples opciones de presentación.

### 🔹 **Gestión de Redes y Conectividad**
- **Alamofire** → Cliente HTTP basado en Swift para redes avanzadas.

## 🔧 Instalación
Este proyecto usa **Swift Package Manager (SPM)** para gestionar dependencias. Para instalar las librerías, sigue estos pasos:

1. **Abrir el proyecto en Xcode**.
2. **Ir a `File > Add Packages...`**.
3. **Agregar las siguientes dependencias con sus URLs**:

   | 📦 **Librería**                 | 🔗 **URL del Repositorio SPM** |
   |---------------------------------|--------------------------------|
   | **Capacitor**                   | `https://github.com/ionic-team/capacitor.git` |
   | **DKImagePickerController**     | `https://github.com/zhangao0086/DKImagePickerController.git` |
   | **DKPhotoGallery**              | `https://github.com/zhangao0086/DKPhotoGallery.git` |
   | **FBAEMKit**                    | `https://github.com/facebook/facebook-ios-sdk.git` *(Selecciona `FBAEMKit` en Xcode)* |
   | **FBSDKCoreKit**                | `https://github.com/facebook/facebook-ios-sdk.git` *(Selecciona `FBSDKCoreKit` en Xcode)* |
   | **FBSDKLoginKit**               | `https://github.com/facebook/facebook-ios-sdk.git` *(Selecciona `FBSDKLoginKit` en Xcode)* |
   | **FBSDKShareKit**               | `https://github.com/facebook/facebook-ios-sdk.git` *(Selecciona `FBSDKShareKit` en Xcode)* |

4. **Ir a `File > Swift Packages > Resolve Package Versions`.**
5. **Compilar (`Cmd + B`)** y verificar que no haya errores.

## 🚀 Uso
Para compilar y ejecutar el proyecto en Xcode:

1. Asegúrate de tener **Xcode 14+** instalado.
2. Descarga las dependencias con `SPM` según la sección anterior.
3. Abre `basic_ios_app4.xcodeproj`.
4. Ejecuta la aplicación en un simulador o dispositivo (`Cmd + R`).

## 📜 Licencia
Este proyecto está bajo la licencia **MIT**.

---
