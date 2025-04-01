# 🔮 zMenu - Smart Minecraft GUI Menu Plugin

✨ **Ein flexibles Menü-System für Minecraft-Server mit vollständiger Konfiguration via YAML** ✨

## 🚀 Features
- 🎛️ **Voll konfigurierbar** über `config.yml`
- 🔄 **Live-Reload** mit `/zmenu reload`
- 🏗️ **27 Slots** für individuelle Menü-Items
- 🎨 **Farbcodes** & Formatierung unterstützt
- 🔊 **Custom Sounds** beim Klicken
- 🖱️ **Inventory-Klicks** intelligent verarbeitet
- 📁 **Einfache Setup** mit automatischer Config-Generierung

## ⚙️ Konfiguration
```yaml
menu_title: "&aMENU"  # 🏷️ Menü-Titel mit Farbcodes

teleports:
  0:  # 🔢 Slot-Nummer (0-27)
    command: "warp hub"  # 🎮 Auszuführender Befehl
    name: "&aHub"  # 🏷️ Item-Name
    material: "DIRT"  # 🧱 Minecraft-Material
    sound: "ENTITY_PLAYER_LEVELUP"  # 🔔 Klick-Sound
