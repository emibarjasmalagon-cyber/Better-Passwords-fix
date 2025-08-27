# 🌟 BetterPasswords


**BetterPasswords** es una aplicación de escritorio para generar y gestionar contraseñas de manera **rápida, sencilla y segura**.


---


## 📂 Contenido del proyecto


- **dist/**
  - `BetterPasswords.exe` → Aplicación lista para ejecutar
  - `BetterPasswords.cer` → Certificado público para validar la app
- **src/** (opcional) → Código fuente en Python
- `README.md` → Este archivo


---


## ⚙️ Requisitos


- Windows 10 o superior
- No se necesita Python, la app ya está compilada
- Para evitar alertas de seguridad de Windows, se recomienda confiar en el certificado `.cer`


---


## 🚀 Cómo usar


1. **Descargar o clonar** este repositorio.
2. Abrir la carpeta `dist/`.
3. Ejecutar `BetterPasswords.exe` haciendo doble clic.
4. **Si Windows Defender muestra una alerta:**
   1. Haz clic derecho sobre `BetterPasswords.cer` → `Instalar certificado`
   2. Selecciona **Ubicación del certificado: Usuario actual**
   3. Finaliza el asistente  
   ✅ Esto permite que Windows reconozca la app como segura.


---


## 🛠 Funcionalidades


- Generación de contraseñas seguras
- Guardado de contraseñas con nombre propio
- Lista de contraseñas guardadas
- Eliminación de contraseñas guardadas
- Interfaz sencilla, clara y visual


---


## 💡 Consejos


- Nunca subas el archivo `.pfx` a GitHub, solo el `.cer`.
- La aplicación funciona **sin abrir CMD o terminal**.
- Las contraseñas permanecen guardadas incluso al apagar la computadora.


---


## 📜 Licencia


Proyecto de **código abierto**, libre para uso y distribución.


---


## 🎨 Colores de la interfaz


- Verde → Contraseña segura
- Amarillo → Contraseña aceptable
- Rojo → Contraseña débil


---


## 🇬🇧 English Instructions


**BetterPasswords** is a desktop application to generate and manage passwords **quickly, easily, and securely**.


### Project Contents


- **dist/**
  - `BetterPasswords.exe` → Ready-to-run application
  - `BetterPasswords.cer` → Public certificate to verify the app
- **src/** (optional) → Python source code
- `README.md` → This file


### Requirements


- Windows 10 or higher
- Python is **not required**, the app is precompiled
- To avoid Windows security warnings, it is recommended to trust the `.cer` certificate


### How to Use


1. **Download or clone** this repository.
2. Open the `dist/` folder.
3. Run `BetterPasswords.exe` by double-clicking.
4. **If Windows Defender shows a warning:**
   1. Right-click `BetterPasswords.cer` → `Install Certificate`
   2. Select **Certificate Store: Current User**
   3. Finish the wizard  
   ✅ This ensures Windows recognizes the app as safe.


### Features


- Secure password generation
- Save passwords with custom names
- View saved passwords
- Delete saved passwords
- Simple and clear user interface


### Tips


- Never upload the `.pfx` file to GitHub, only the `.cer`.
- The application runs **without opening CMD or terminal**.
- Passwords remain saved even after restarting the computer.


### Interface Colors


- Green → Secure password
- Yellow → Acceptable password
- Red → Weak password