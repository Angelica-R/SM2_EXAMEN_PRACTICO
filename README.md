# SM2_EXAMEN_PRACTICO

**Código:** 2019063327  
**Nombres:** Angelica Beatriz Romero Roque

## Descripción del Proyecto
Este proyecto tiene como objetivo el desarrollo de una aplicación para la recomendación de ejercicios y rutinas personalizadas, que ayuda a los usuarios a mejorar su estado físico de acuerdo con sus metas. En este repositorio se implementaron las siguientes dos funcionalidades:

### Funcionalidad Implementada: Recopilar Datos de Usuarios

1. **Recopilación de Datos del Usuario**  
   El sistema solicita los siguientes datos básicos del usuario:
   - **Edad**
   - **Peso**
   - **Altura**
   - **Objetivos** (pérdida de peso, aumento de masa muscular, mejora de resistencia, etc.)

   Esta información se utiliza para crear perfiles personalizados y adaptar las recomendaciones de entrenamiento y nutrición a las necesidades de cada usuario.

   **Historia de Usuario**:  
   *Como* sistema, *quiero* recopilar los datos de los usuarios (edad, peso, altura, objetivos, etc.) *para* personalizar las recomendaciones de entrenamiento y nutrición.

   **Implementación**:
   - El sistema permite que los usuarios ingresen sus datos mediante un formulario sencillo.
   - Los datos ingresados se almacenan en una base de datos segura y se utilizan para generar recomendaciones personalizadas.

   ![Formulario de Datos del Usuario](/SM2_EXAMEN_PRACTICO/img/captura01.jpg)  
   *Ejemplo de la interfaz de recopilación de datos del usuario.*

---

### Funcionalidad Implementada: Sistema de Reconocimiento Facial

2. **Implementación del Sistema de Reconocimiento Facial**  
   Esta funcionalidad permite que los usuarios se autentiquen en la aplicación utilizando su rostro, en lugar de introducir manualmente sus credenciales.

   **Historia de Usuario**:  
   *Como* usuario, *quiero* poder utilizar el reconocimiento facial para acceder a mi perfil en la aplicación *para* tener una forma rápida y segura de iniciar sesión.

   **Implementación**:
   - Se utiliza una librería de **Reconocimiento Facial** (https://opencv.org/) para realizar el reconocimiento en tiempo real desde la cámara del dispositivo.
   - El sistema captura la imagen del rostro del usuario y la compara con una base de datos de rostros previamente almacenados para verificar su identidad.
   - Si la identidad es verificada correctamente, el usuario obtiene acceso a su perfil en la aplicación.

   ![Reconocimiento Facial](/SM2_EXAMEN_PRACTICO/img/captura2.png) 
    ![Reconocimiento Facial](/SM2_EXAMEN_PRACTICO/img/captura3.png) 

   *Ejemplo de la interfaz de reconocimiento facial durante el inicio de sesión.*

---