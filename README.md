### Guía paso a paso para instalar Pentaho Data Integration

#### Requisitos Previos
Antes de comenzar con la instalación, asegúrate de tener los siguientes requisitos:
- Java JDK 8 (u 11, dependiendo de la versión de Pentaho)
- Un sistema operativo compatible (Windows, macOS, Linux)
- Suficiente espacio en disco para la instalación y operación de Pentaho

#### Paso 1: Descargar Pentaho Data Integration
1. Visita el sitio oficial de Hitachi Vantara y navega a la sección de descargas de Pentaho.
2. Descarga la última versión de Pentaho Data Integration (PDI) también conocido como Spoon.

#### Paso 2: Extraer el Archivo
1. Una vez descargado el archivo ZIP, extráelo en una ubicación de tu preferencia en tu sistema.

#### Paso 3: Configurar Variables de Entorno
1. Configura la variable de entorno `JAVA_HOME` apuntando a la ruta de instalación del JDK.
2. Añade el binario de Java a la variable de entorno `PATH`.

#### Paso 4: Ejecutar Pentaho Data Integration
1. Navega a la carpeta donde extrajiste PDI.
2. Ejecuta el archivo `Spoon.bat` (Windows) o `Spoon.sh` (macOS/Linux).

#### Paso 5: Configuración Inicial
1. Al iniciar Spoon por primera vez, es posible que se te pida configurar ciertos parámetros como la conexión a la base de datos.
2. Sigue las instrucciones en pantalla para completar la configuración inicial.

### Verificación de la Instalación
1. Para verificar que la instalación fue exitosa, abre Spoon y asegúrate de que la interfaz se carga correctamente.
2. Puedes probar creando un simple trabajo o transformación para asegurarte de que todo funciona como se espera.

Para más detalles sobre la instalación y configuración, puedes consultar la [documentación oficial de Pentaho](https://help.hitachivantara.com/Documentation/Pentaho).

Si necesitas más ayuda, por favor visita los recursos adicionales disponibles en la [comunidad de Pentaho](https://community.hitachivantara.com/s/).

Para configurar Pentaho Data Integration, generalmente necesitas configurar las siguientes variables de entorno:

1. `JAVA_HOME`: Esta variable debe apuntar al directorio donde está instalado Java JDK.
   - **Windows**: 
     ```sh
     set JAVA_HOME=C:\Program Files\Java\jdk1.8.0_251
     ```
   - **macOS/Linux**:
     ```sh
     export JAVA_HOME=/usr/lib/jvm/java-8-openjdk
     ```

2. `PATH`: Asegúrate de que el binario de Java esté en el `PATH`.
   - **Windows**:
     ```sh
     set PATH=%JAVA_HOME%\bin;%PATH%
     ```
   - **macOS/Linux**:
     ```sh
     export PATH=$JAVA_HOME/bin:$PATH
     ```

Estas configuraciones aseguran que Pentaho Data Integration pueda encontrar y utilizar la versión correcta de Java.
