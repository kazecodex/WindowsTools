# Things to do Windows 11

## 1. Cargar la ISO en la herramienta MicroWin de Christitus
- **MicroWin de Christitus** permite personalizar ISOs de Windows antes de la instalación. 
- Carga la **ISO de Windows 11**, realiza las modificaciones necesarias y guarda la versión personalizada.

## 2. Instalar Ventoy en el Pendrive
- Descarga **Ventoy**, conecta tu pendrive y sigue el proceso de instalación.
- Instalar Ventoy en el pendrive hará que sea un dispositivo booteable múltiple.

## 3. Copiar y pegar la ISO modificada en el Pendrive
- Una vez instalado **Ventoy**, abre el pendrive desde el **explorador de archivos**.
- Copia la **ISO modificada de Windows 11** y pégala directamente en el pendrive (Ventoy se encargará del arranque).

## 4. Reiniciar el PC
- Reinicia tu PC y accede al **BIOS/UEFI** (generalmente presionando una tecla como **F2**, **Esc**, **Del** o **F12**).
- Configura el **pendrive como primera opción de arranque**.

## 5. Iniciar la instalación desde el Pendrive
- Una vez reiniciado, arranca desde el **pendrive con Ventoy**.
- Selecciona la **ISO de Windows 11** desde el menú de Ventoy y sigue los pasos para instalar Windows 11.

---

## 6. Verificar que la licencia de Windows esté activada, solucionarlo si no es así
- Una vez instalado, ve a **Configuración > Actualización y seguridad > Activación**.
- Si Windows no está activado, puedes ingresar la **clave de producto** o activar Windows mediante otros métodos (como la licencia digital vinculada a tu cuenta de Microsoft).

## 7. Buscar actualizaciones en Windows Update, hasta que no quede ninguna
- Ve a **Configuración > Actualización y seguridad > Windows Update**.
- Haz clic en **Buscar actualizaciones** y asegúrate de instalar todas las actualizaciones disponibles. Repite el proceso hasta que no queden más actualizaciones pendientes.

## 8. Buscar los controladores desde la página oficial o usar 3dpchip para los principales controladores
- Descarga los controladores más recientes desde las páginas oficiales del fabricante (placa base, tarjeta gráfica, etc.).
- También puedes usar **3dpchip** para obtener y actualizar los controladores más importantes como los de red, gráficos y chipset.

## 9. Actualizar con DriverBooster para los controladores restantes
- Instala **DriverBooster**, que buscará y actualizará automáticamente los controladores obsoletos.
- Realiza un respaldo o crea un punto de restauración antes de realizar actualizaciones masivas de controladores, por si ocurre algún inconveniente.

## 10. Aplicar las tweaks en la herramienta WinUtil de Christitus
- Usa **WinUtil de Christitus** para aplicar **tweaks** y optimizaciones del sistema.
- Selecciona las opciones de personalización para desactivar servicios innecesarios, mejorar el rendimiento, ajustar configuraciones de red, y optimizar aspectos visuales.

## 11. Revisar el OOShutop con configuraciones a desactivar
- **OOShutop** te permite gestionar servicios y configuraciones avanzadas de Windows.
- Revisa y desactiva los servicios y configuraciones que consideres innecesarios. Asegúrate de no desactivar algo crítico para el funcionamiento del sistema.

## 12. Dependiendo de la cantidad de RAM que tengas, agregar memoria virtual
- Si tienes menos de 16 GB de RAM, ajusta la **memoria virtual**:
  - Ve a **Configuración > Sistema > Acerca de** y selecciona **Configuración avanzada del sistema**.
  - En **Rendimiento**, haz clic en **Configuración**, luego en **Opciones avanzadas** y ajusta el tamaño del archivo de paginación (memoria virtual).

## 13. Con tecla Windows + R, escribir msconfig, ventana arranque > opciones avanzadas, y tildar la opción del procesador, y marcar el número máximo de núcleos
- Pulsa **Windows + R**, escribe **msconfig** y presiona Enter.
- En la ventana de **Configuración del sistema**, ve a la pestaña **Arranque > Opciones avanzadas**.
- Marca la casilla **Número de procesadores** y selecciona el número máximo de núcleos disponibles de tu CPU para mejorar el rendimiento del arranque.

## 14. Al final de todo, para una limpieza profunda utilizar BleachBit
- Descarga **BleachBit** desde su página oficial y ejecútalo.
- **BleachBit** eliminará archivos temporales, cachés, registros y otros archivos innecesarios de tu sistema, liberando espacio en el disco y mejorando el rendimiento general.
- Ten cuidado de no eliminar elementos críticos como cookies si las necesitas.

---

## Resumen de pasos adicionales:
1. **Verifica y soluciona la activación** de la licencia de Windows.
2. Realiza todas las **actualizaciones disponibles** en **Windows Update**.
3. Instala y actualiza los **controladores** utilizando herramientas como **3dpchip** y **DriverBooster**.
4. Aplica las **optimización** de **WinUtil**.
5. Revisa y desactiva configuraciones innecesarias con **OOShutop**.
6. Ajusta la **memoria virtual** según tu cantidad de RAM.
7. Configura el número de **núcleos** a usar en **msconfig**.
8. Realiza una **limpieza profunda** con **BleachBit**.
