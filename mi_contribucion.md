# Pasos para hacer un Fork y Clonarlo en Local

Hacer un *fork* de un repositorio en GitHub y clonarlo en tu máquina local es un proceso bastante sencillo, pero con varios pasos para asegurarte de que tienes tu propia copia del repositorio para modificarlo y trabajar con él. Aquí te explico cómo hacerlo utilizando el repositorio de ejemplo `https://github.com/cesarlpb/libro-de-programacion`.

## Paso 1: Hacer un Fork del repositorio en GitHub

1. **Accede al repositorio en GitHub**:
   - Abre tu navegador y visita el enlace del repositorio que deseas *forkear*: [https://github.com/cesarlpb/libro-de-programacion](https://github.com/cesarlpb/libro-de-programacion).
   
2. **Hacer un Fork**:
   - Una vez en el repositorio, en la parte superior derecha de la página encontrarás un botón verde que dice **Fork**. Haz clic en este botón.
   
3. **Seleccionar la cuenta de destino**:
   - Si tienes varias cuentas de GitHub o pertenencias a organizaciones, GitHub te preguntará dónde quieres hacer el *fork*. Si solo tienes una cuenta personal, simplemente aparecerá tu nombre de usuario como la opción predeterminada.
   - Selecciona tu cuenta personal para crear el fork en tu perfil de GitHub.

4. **Espera que se cree el Fork**:
   - GitHub te redirigirá automáticamente a tu nuevo repositorio *forkeado*, que es una copia del repositorio original, pero bajo tu cuenta. Ahora, tienes una copia que puedes modificar sin afectar al proyecto original.

## Paso 2: Clonar el repositorio Forkeado a tu máquina local

1. **Accede a tu repositorio Forkeado**:
   - Ve a tu cuenta de GitHub, y busca el repositorio *forkeado* en tu perfil. Debería tener el mismo nombre que el repositorio original, pero con tu nombre de usuario como parte de la URL. Por ejemplo, `https://github.com/TuUsuario/libro-de-programacion`.

2. **Copiar la URL del repositorio**:
   - En tu repositorio *forkeado*, haz clic en el botón verde que dice **Code**.
   - En el menú desplegable, verás diferentes opciones de URL. Asegúrate de seleccionar **SSH** y copia la URL que aparece. Esta URL será algo como `git@github.com:/TuUsuario/libro-de-programacion.git`.

3. **Clonar el repositorio en tu máquina local**:
   - Abre la terminal (o Git Bash si usas Windows).
   - Navega a la carpeta donde quieres guardar el repositorio en tu máquina local.
   - Ejecuta el siguiente comando en la terminal, reemplazando `<URL del repositorio>` con la URL copiada:

   ```bash
   git clone git@github.com:/TuUsuario/libro-de-programacion.git
   ```

4. **Acceder al directorio del repositorio**:
   - Después de que el repositorio se haya clonado, navega a la carpeta del repositorio usando:

   ```bash
   cd libro-de-programacion
   ```
