# 🚀 ChatP2Plus - Mensajería Segura y Transferencia de Archivos

Una aplicación de escritorio moderna, privada y descentralizada construida con **Go (Backend)** y **React (Frontend)** utilizando el framework [Wails](https://wails.io/).
<img width="1007" height="767" alt="image" src="https://github.com/user-attachments/assets/5fc0ea88-cfd3-4b03-a69a-bb8c749c36fe" />


## ✨ Características Principales

* **🔗 Conexión P2P Real:** Arquitectura *Full Mesh* utilizando `libp2p` y DHT. Sin servidores centrales.
* **📂 Transferencia de Archivos Inteligente:**
    * Soporte para archivos grandes (+2GB) con gestión eficiente de memoria (Streams).
    * **Barra de progreso** en tiempo real.
    * **Verificación de Integridad:** Cálculo de hash **SHA256** al vuelo para validar que el archivo no esté corrupto.
* **🛡️ Privacidad Total:** Los mensajes viajan encriptados y directos entre pares.
* **👁️ Previsualización Multimedia Unificada:**
    * Reproductor nativo para Video (4K soportado), Audio e Imágenes.
    * Sistema híbrido: Carga instantánea de archivos locales y streaming de recibidos.
* **⚡ Rendimiento:** Buffer de transferencia optimizado (1MB) y bajo consumo de RAM.

## 🛠️ Tecnologías

* **Backend:** Go (Golang)
* **Frontend:** React + Vite
* **Network:** Libp2p (MDNS para LAN, DHT para Internet)
* **GUI:** Wails v2 (WebView2 en Windows)

## 🚀 Instalación y Desarrollo

### Prerrequisitos
* Go 1.21+
* Node.js 18+
* NSIS (Opcional, solo para generar instalador en Windows)

### Ejecutar en modo Dev
```bash
wails dev
