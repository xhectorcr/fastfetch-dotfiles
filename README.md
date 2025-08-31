# Fastfetch Dotfiles

Configuración personalizada de **[Fastfetch](https://github.com/fastfetch-cli/fastfetch)** con logo ASCII y detalles del sistema.

![Preview](https://github.com/xhectorcr/fastfetch-dotfiles/blob/1a7bc60908a2f6f2ec45b74e50a965c8938c9fa8/Image/fastfetch-kittyterminal.png)

## 📦 Contenido
- `config.jsonc`: configuración principal de Fastfetch.
- `logo.txt`: logo ASCII personalizado mostrado en la terminal.
- Archivos de soporte para estilos y personalización.

## ⚙️ Requisitos
- [Fastfetch](https://github.com/fastfetch-cli/fastfetch)
- Una terminal compatible (ejemplo: [Kitty](https://sw.kovidgoyal.net/kitty/))
- Fuente con soporte para símbolos (ejemplo: FiraCode Nerd Font)

## 🚀 Instalación
Clona el repositorio y copia los archivos de configuración:

```bash
git clone https://github.com/xhectorcr/fastfetch-dotfiles.git
cd fastfetch-dotfiles
mkdir -p ~/.config/fastfetch
cp config.jsonc logo.txt ~/.config/fastfetch/
