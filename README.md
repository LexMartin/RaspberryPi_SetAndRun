# Raspberry Pi Set&Run Config
Estos son los pasos básicos para configurar una Raspberry Pi Headless.

### Prerrequisitos
* SD con Raspian instalado
* Lector de SD

### Instalación
#### Activar WiFi 
* Modificar en el archivo `wpa_supplicant.conf` los siguientes valores 
```Bash
ssid = "NombreRed"
psk = "Password"
```
* Copiar el archivo a la SD


#### Activar SSH
Para activar SSH basta con crear un archivo vacío en la SD con el nombre `ssh`

### Referencias
[Configuración de Red](https://www.raspberrypi.org/documentation/configuration/wireless/wireless-cli.md)

[Habilitar SSH](hhttps://www.raspberrypi.org/documentation/remote-access/ssh/README.md#3-enable-ssh-on-a-headless-raspberry-pi-add-file-to-sd-card-on-another-machine)

### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
