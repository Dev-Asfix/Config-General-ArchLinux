<div align="center">
  
  <h2>
    🌐Arch Linux Config - QTILE 📩
  </h2>

<p align="center">
    <!-- Insignias para Discord-Message con color morado -->
    <a href="https://github.com/Dev-Asfix/Discord-Message?tab=License-1-ov-file"><img src="https://img.shields.io/github/license/Dev-Asfix/Foro-Hub?style=for-the-badge" alt="License"></a>
    <a href="https://github.com/Dev-Asfix/Discord-Message/issues"><img src="https://img.shields.io/github/issues/Dev-Asfix/Discord-Message?style=for-the-badge&color=8A2BE2" alt="Open Issues"></a>
    <a href="https://github.com/Dev-Asfix/Discord-Message/graphs/contributors"><img src="https://img.shields.io/github/contributors/Dev-Asfix/Discord-Message?style=for-the-badge&color=8A2BE2" alt="Contributors"></a>
</p>
</div>


# 🔧 Config-General-ArchLinux

Personalización completa y modular de **Arch Linux**, optimizada para sistemas modernos. Scripts, dotfiles y configuraciones listas para instalar y mantener un entorno robusto, elegante y funcional.

---

## 🚀 ¿Qué incluye?

* **Instalador automatizado** (`install.sh`) para instalación básica del sistema.
* **Dotfiles personalizados** para shell (Zsh), Git, Neovim, tmux y más.
* **Gestión de paquetes**: instalación de `pacman`, `paru`, AUR helpers y herramientas esenciales.
* **Entorno gráfico**: configuración ligera para i3, Sway o escritorio minimalista.
* **Temas y look & feel**: íconos, fuentes y tema GTK personalizado.
* **Backups y sincronización**: scripts para respaldar configuración y restaurarla en otro equipo.

---

## 🛠️ Requisitos

* Arch Linux instalado con soporte **UEFI** o **BIOS**.
* Conexión a internet durante la instalación.
* Permisos de sudo o acceso a `root`.

---

## ⚙️ Uso

1.  **Clona el repo**
    ```bash
    git clone [https://github.com/Dev-Asfix/Config-General-ArchLinux.git](https://github.com/Dev-Asfix/Config-General-ArchLinux.git)
    cd Config-General-ArchLinux
    ```
2.  **Haz tu revisión previa**
    Edita variables como `USERNAME`, `HOSTNAME` y rutas en `config.ini` o `install.sh` si aplica.
3.  **Ejecuta el instalador**
    ```bash
    chmod +x install.sh
    sudo ./install.sh
    ```
4.  **Reinicia**
    Luego de completar el script, reinicia y accede con tu usuario configurado.

---

## 📂 Estructura del repositorio

```bash
.
├── install.sh        # Script principal
├── config.ini        # Variables configurables
├── dotfiles/         # Configuración personal (Zsh, Vim, tmux…)
├── i3/               # Archivos de configuración de i3wm
├── sway/             # Configuración de Sway (Wayland)
├── themes/           # Temas GTK, iconos, fuentes
└── tools/            # Scripts para backups, sincronización y mantenimiento
```

---

## 🎯 ¿Por qué usar esta configuración?

* 💡 **Automatización total**: Desde la instalación base hasta un entorno de desarrollo completo.
* 🔄 **Modularidad**: Flexibilidad para activar i3, Sway o un escritorio tradicional según tus preferencias.
* 🎨 **Diseño moderno**: Incluye íconos, temas y una distribución visual limpia para una experiencia agradable.
* 🛡️ **Mantención fácil**: Scripts de **backups** y **sincronización** que facilitan replicar o actualizar tu configuración.
* 📈 **Orientado a la productividad**: Un enfoque minimalista que no sacrifica estilo ni funcionalidad.

---

## 🧩 Personalización

* **Tweaks** para `pacman` y `mirrorlist` para optimizar tu gestión de paquetes.
* **Plugins Zsh**: Autocompletado, `llm-history` y `syntax highlighting` para mejorar tu experiencia en la terminal.
* **Configuración de Neovim** con **plugins LSP** y **Tmux** para un flujo de trabajo de desarrollo eficiente.
* **Temas compatibles** con GNOME, XFCE, i3 y Sway.

---

## 🤝 Contribuye

¡Tus contribuciones son bienvenidas!

1.  Haz **fork** del repositorio.
2.  Crea tu rama: `git checkout -b feature-nombre`.
3.  Realiza tus modificaciones.
4.  Envía un **pull request** y describe detalladamente tus aportes.

---

## 📜 Licencia

Este proyecto está disponible bajo la **MIT License**. Eres libre de usarlo para fines personales, educativos o profesionales. ¡No dudes en copiar, adaptar y mejorar!

---

## 💬 Contacto

* **Creador**: Dev-Asfix - Pablo
* **Twitter / GitHub**: [@Dev-Asfix](https://github.com/Dev-Asfix)

