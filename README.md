# Manual de Instalación - Guía de Información y Cuidado para un Jardín Botánico

## Requisitos Previos:

### Backend:

1. Node.js y npm instalados.
2. Conocimientos básicos de TypeScript.
3. Acceso a una base de datos compatible (por ejemplo, MongoDB).

### Frontend:

1. Node.js y npm instalados.
2. Conocimientos básicos de Angular.

## Pasos de Instalación:

### Backend:

1. **Clonar el Repositorio**:

   ```bash
   git clone <repositorio_backend>
   ```

2. **Navegar al Directorio del Backend**:

   ```bash
   cd <directorio_backend>
   ```

3. **Instalar Dependencias**:

   ```bash
   npm install
   ```

4. **Configurar Variables de Entorno**:

   - Copia el archivo `.env.example` a `.env`.
   - Configura las variables de entorno necesarias (por ejemplo, la conexión a la base de datos).

5. **Compilar y Ejecutar el Servidor**:
   ```bash
   npm run build
   npm start
   ```

### Frontend:

1. **Clonar el Repositorio**:

   ```bash
   git clone <repositorio_frontend>
   ```

2. **Navegar al Directorio del Frontend**:

   ```bash
   cd <directorio_frontend>
   ```

3. **Instalar Dependencias**:

   ```bash
   npm install
   ```

4. **Configurar Variables de Entorno**:

   - Edita el archivo `environment.ts` en `src/environments/` para configurar la URL de la API del backend.

5. **Compilar el Proyecto**:

   ```bash
   ng build --prod
   ```

6. **Desplegar en un Servidor Web**:
   - Copia los archivos generados en la carpeta `dist/` a un servidor web compatible.

## Acceso a la Aplicación:

1. Abre un navegador web.
2. Ingresa la URL del servidor donde se ha desplegado el frontend.
3. ¡Disfruta de la Guía de Información y Cuidado para el Jardín Botánico!

Este manual te guiará a través de la instalación del sistema, asegurando que tanto el backend como el frontend estén correctamente configurados y listos para su uso. Asegúrate de seguir los pasos cuidadosamente y de configurar adecuadamente las variables de entorno para adaptar el sistema a tu entorno específico.
