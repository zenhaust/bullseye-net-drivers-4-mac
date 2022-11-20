# Net wifi drivers Debian Bullseye

Los driver a utilizar aplican para una distribución Debian 11 (bullseye) en una máquina **Mackbook pro 15 pulgadas retina** de 2014.

## Lista de paquetes

* broadcom-sta-dkms_6.30.223.271-17_all.deb
* dctrl-tools_2.24-3+b1_amd64.deb
* distro-info-data_0.51+deb11u2_all.deb
* dkms_2.8.4-3_all.deb
* lsb-release_11.1.0_all.deb

## Intalación de paquetes

```bash
dpkg -i dctrl-tools_2.24-3+b1_amd64.deb 
dpkg -i distro-info-data_0.51+deb11u2_all.deb
dpkg -i lsb-release_11.1.0_all.deb
dpkg -i dkms_2.8.4-3_all.deb 
dpkg -i broadcom-sta-dkms_6.30.223.271-17_all.deb 
```

Los paquetes listados funcionan sin problema. Se recomienda, no obstante, revisar si existen versiones actualizadas.


