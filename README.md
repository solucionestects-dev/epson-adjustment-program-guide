# 🖨️ Guía de Uso: Epson Adjustment Program (AdjProg)

Repositorio con la documentación paso a paso para utilizar la herramienta **Adjustment Program**, solucionar el error de *"Almohadillas de tinta al final de su vida útil"* y realizar procedimientos de mantenimiento en impresoras de la marca Epson.

---

## 📋 Requisitos Previos

Antes de ejecutar el programa de ajuste, asegúrate de cumplir con las siguientes condiciones:

1. **Conexión Directa:** La impresora debe estar encendida y conectada a la computadora mediante un **cable USB** en buen estado. No realices este proceso a través de conexiones por Wi-Fi o red local.
2. **Controladores Instalados:** Asegúrate de tener instalados los controladores oficiales (drivers) de la impresora, no los genéricos que asigna Windows por defecto.
3. **Antivirus y Seguridad:** Desactiva temporalmente la protección en tiempo real de tu antivirus o Windows Defender, ya que los ejecutables `.exe` de reseteo suelen ser detectados como falsos positivos.
4. **Cola de Impresión Vacía:** Cancela y elimina cualquier documento pendiente de impresión en la cola del sistema.

---

## 🚀 Paso a Paso: Reseteo del Contador (Waste Ink Pad Counter)

Sigue estos pasos cuidadosamente para reiniciar el contador de las almohadillas de tinta:

1. **Ejecutar como Administrador:**
   - Descarga y extrae el archivo `.zip` del Adjustment Program correspondiente a tu modelo.
   - Pagina para descargar el programa: https://specialistechnology.com/usar-adjustment-program/
   - Opción: https://camosystemsreset.com/descargas/
   - Haz clic derecho sobre el archivo `AdjProg.exe` y selecciona **Ejecutar como Administrador**.

2. **Seleccionar Modelo y Puerto:**
   - Haz clic en el botón **Select**.
   - En la opción **Model Name**, elige el modelo exacto de tu impresora.
   - En **Port**, selecciona el puerto USB asignado a tu impresora o déjalo en **Auto Selection**. Presiona **OK**.

3. **Entrar al Modo de Ajuste:**
   - Haz clic en el botón **Particular Adjustment Mode** (ubicado en el panel derecho).

4. **Localizar el Contador de Almohadillas:**
   - Desplázate hacia la sección **Maintenance** y selecciona **Waste Ink Pad Counter**.
   - Haz clic en **OK**.

5. **Verificar e Inicializar el Contador:**
   - Marca la casilla **Main Pad Counter** (y la casilla *Platen Pad Counter* si está disponible en tu modelo).
   - Haz clic en el botón **Check** para leer el número de puntos acumulados.
   - Vuelve a marcar las casillas y haz clic en el botón **Initialization**.
   - Presiona **OK** cuando aparezca la ventana flotante de confirmación.

6. **Reiniciar el Equipo:**
   - Cuando el programa indique la instrucción *"Please turn off the printer"*, apaga la impresora mediante su botón físico de encendido.
   - Haz clic en **OK** en la pantalla del programa, cierra el *Adjustment Program* y vuelve a encender la impresora.

---

## ⚠️ Solución de Problemas Frecuentes

| Error | Causa Probable | Solución |
| :--- | :--- | :--- |
| **Communication Error** | Cable desconectado, puerto USB defectuoso o falta del driver adecuado. | Cambia el cable USB a otro puerto físico de la PC, asegúrate de haber encendido la impresora y reconfigura la opción *Port Selection*. |
| **Error 20000010** | Conflicto de comunicación con la cola de impresión o los controladores. | Reinicia el servicio de cola de impresión (`Spooler`) desde los Servicios de Windows o reinstala los controladores oficiales. |
| **El programa se cierra automáticamente** | Bloqueo automático por parte del antivirus. | Restaura el ejecutable desde la cuarentena de tu antivirus y añade la carpeta del programa a la lista de excepciones. |

---

## 💡 Recomendaciones Importantes

> ⚠️ **Atención:** El reseteo por software limpia el error digital del sistema, pero no limpia el residuo físico de tinta. Si utilizas la impresora con frecuencia, se recomienda reemplazar las almohadillas físicas o instalar un tanque/depósito de descarga externo para evitar derrames internos de tinta en la placa principal del equipo.

---

## 📄 Licencia

Este proyecto de documentación está bajo la [Licencia MIT](LICENSE).
