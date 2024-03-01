# ZX80/ZX81 POSEIDON

Source: https://github.com/gyurco/ZX8X_MiST

### Características:
- Basado en la [página ZX80] de Grant Searle (http://searle.hostei.com/grant/zx80/zx80.html)
- ZX80/ZX81 seleccionable
- Paquetes de RAM de 16k/32k/64k
- Placa CHR128 a $3000
- Chip de sonido YM2149 (compatible con ZON X-81)
- Joystick tipo Sinclar (teclas 67890)
- Horarios PAL/NTSC
- Carga turbo de archivos .o y .p
- Carga de cintas originales desde el puerto UART RX

### Tape loading
Al seleccionar un archivo .o (ZX80) o .p (ZX81), se abre la cinta. Esto lo indica el
LED de usuario. El comando LOAD lo cargará como lo haría en una cinta estándar.
Si no hay ningún archivo abierto, se ejecuta la rutina de carga de ROM estándar y
Puede recibir datos de cinta desde el puerto UART.
Restablecer (ALT-F11 o la opción Restablecer OSD) cierra el archivo .o o .p.

### Download precompiled binaries and system ROMs:
zx8x.rom a la raíz de la tarjeta SD.
