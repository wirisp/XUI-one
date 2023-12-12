# Instalacion de XUI one en Debian o ubuntu

## Proceso de Instalacion del programa XUI one
- Instalar algunos programas

```
apt install zip git unzip -y
timedatectl set-timezone America/Mexico_City
```

- Descargar los archivos , elegir cual version

```
wget "https://update.xui.one/XUI_1.5.5.zip" -O /tmp/XUI_1.5.5.zip
wget "https://update.xui.one/XUI_1.5.12.zip" -O /tmp/XUI_1.5.12.zip
```

- Descomprimir de acuerdo a la version
```
cd /tmp
unzip XUI_1.5.5.zip
```

- Ejecutar el instalador
```
./install
```

## Proceso de Licencia
- Clonar repo
```
git clone https://github.com/wirisp/XUI-one
```

- Entrar a la carpeta
```
cd XUI-one/
```
- Descomprimir
```
unzip xui-license.zip
```
- Permisos
```
chmod -R 777 install.sh
```
- Instalacion
```
./install.sh
```
