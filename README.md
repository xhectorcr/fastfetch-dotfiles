# 🚀 Fastfetch Dotfiles

Configuración personalizada de **Fastfetch** con logo ASCII, módulos organizados y apartado de redes sociales.  
Perfecto para mostrar información del sistema de forma elegante en la terminal.

![Preview](https://github.com/xhectorcr/fastfetch-dotfiles/blob/8e343f1405671ddada92d267e2efe47d3f9eeef2/fastfetch-dotfiles/Image/fastfetch-kittyterminal.png) <!-- Puedes poner una captura de pantalla -->

---

## 📦 Requisitos

- Linux (probado en Linux Mint / Debian / Ubuntu y Derivadas)
- [Fastfetch](https://github.com/fastfetch-cli/fastfetch)
- Git
- Python (opcional, si usas `disk.py` para mostrar discos)

---

## ⚙️ Instalación

Clona este repositorio en tu máquina:

```bash
https://github.com/xhectorcr/fastfetch-dotfiles.git
cd fastfetch-dotfiles
```

Copia la configuración a tu directorio de usuario:

```bash
mkdir -p ~/.config/fastfetch
cp -r fastfetch/* ~/.config/fastfetch/
```

Verifica que funcione ejecutando:

```bash
fastfetch
```
## 🎨 Personalización

- El **logo ASCII** se encuentra en (Si quieres cambiarlo solo copia y pega tu diseño en el .txt): 

```bash
~/.config/fastfetch/logo.txt
```
Para editar tu nombre o las redes sociales, abre con:
```bash
nano ~/.config/fastfetch/config.jsonc
```
Dentro del archivo busca la sección:
```bash
{
  "type":"custom",
  "key":"┣━ ",
  "format":"Red Social: @tu_usuario"
}
```
