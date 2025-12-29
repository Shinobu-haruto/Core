# Core Icon Theme

Minimal Core Icon Theme para Linux (Cinnamon / GNOME / MATE)

## Contenido

- **Apps**: Iconos de aplicaciones comunes
- **Devices**: Audio, red, batería, pantalla
- **Status**: Sync, update, installing, error, warning, paused
- **Actions**: Play, Stop, Pause, Forward, Rewind, Refresh
- **Folders**: Normal, especiales, overlays, abiertos/cerrados
- **Mimetypes**: Documentos, imágenes, comprimidos, etc.
- **Cursors**: Left pointer, hand, xterm, watch (busy)
- **Spinner**: Icono estático de carga

## Instalación

```bash
# Copiar al usuario
mkdir -p ~/.icons
cp -r Core ~/.icons/

# Activar tema
gsettings set org.cinnamon.desktop.interface icon-theme "Core"
# o para MATE
gsettings set org.mate.interface icon-theme "Core"
