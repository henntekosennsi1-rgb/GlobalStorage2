# GlobalStorage2

[![Version](https://img.shields.io/badge/version-1.0-green.svg)]()
[![Minecraft](https://img.shields.io/badge/Minecraft-1.21-blue.svg)]()
[![License](https://img.shields.io/badge/license-MIT-yellow.svg)]()

Advanced shared storage system with infinite stacking and automation

## 🗄️ Features

- **Global Shared Storage** - Server-wide accessible storage
- **Infinite Stacking** - Store billions of items per stack
- **10 Auto-Categories** - Automatic item categorization
- **Auto-Storage Chests** - Automatic item transfer
- **Transfer Filters** - Per-player auto-transfer rules
- **Smart Search** - Quick item finding
- **World Restrictions** - Disable in specific worlds
- **JSON Persistence** - Reliable data storage

## 📂 Categories

| Category | Description | Icon |
|----------|-------------|------|
| Building Blocks | Construction materials | Bricks |
| Colored Blocks | Wool, concrete, terracotta | White Wool |
| Natural Blocks | Stone, dirt, wood | Grass Block |
| Functional Blocks | Workstations | Crafting Table |
| Redstone | Components & circuits | Redstone |
| Tools | All tools & utilities | Iron Pickaxe |
| Combat | Weapons & armor | Iron Sword |
| Food | Edibles & potions | Apple |
| Materials | Crafting ingredients | Stick |
| Misc | Everything else | Barrier |

## 🚀 Quick Start

1. Download GlobalStorage2.jar
2. Place in `/plugins/` folder
3. Restart server
4. Give stick: `/gs give`
5. Right-click to open storage!

## 📋 Commands

| Command | Description | Permission |
|---------|-------------|-----------|
| `/gs give [player]` | Give storage stick | gs.use |
| `/gs open` | Open storage GUI | gs.admin |
| `/gs sort` | Sort items | gs.admin |
| `/gs save` | Manual save | gs.admin |
| `/gs setchest` | Set auto-chest | gs.admin |
| `/gs removechest` | Remove auto-chest | gs.admin |
| `/gs listchests` | List auto-chests | gs.admin |
| `/gs tensou` | Open filter GUI | gs.use |
| `/gs ngworld <world>` | Disable in world | gs.admin |
| `/gs okworld <world>` | Enable in world | gs.admin |

## ⚙️ Configuration
```yaml
# GlobalStorage2 Configuration

# Worlds where stick is disabled
ng-worlds:
  - "example_world_disable"
```

## 🎮 Usage

### Storage Access
- Get stick with `/gs give`
- Right-click to open storage
- Use categories to filter items
- Search by typing in chat
- Navigate pages with arrows

### GUI Controls
- **Left Click** - Take 1 item
- **Right Click** - Take stack (64)
- **Shift+Left** - Take all
- **Q Key** - Custom amount
- **Middle Click** - Take half

### Auto-Storage Chests
1. Place chest
2. Use `/gs setchest`
3. Right-click chest
4. Items auto-transfer

### Transfer Filters
1. Open with `/gs tensou`
2. Add items to filter
3. Items auto-transfer from inventory

## 📦 Requirements

- Paper/Spigot 1.21+
- Java 21+

## 💾 Data Files

- `storage.json` - Item storage data
- `auto_chests.json` - Chest locations
- `tensou_filters.json` - Player filters
- Auto-saves every 5 minutes

## 🔧 Building from Source
```bash
git clone https://github.com/henrry/GlobalStorage2.git
cd GlobalStorage2
mvn clean package
```

## 🔑 Permissions

- `gs.use` - Basic usage (default: true)
- `gs.admin` - Admin commands (default: op)

## 💬 Support

Discord: https://discord.gg/zYY55dzhjd

## 📄 License

This project is licensed under the MIT License.

## 👤 Author

**henrry (へんりー)**
- MattariMinecraft Server Owner/Developer

---

<p align="center">
Made with ❤️ for MattariMinecraft<br>
© 2024 henrry. All rights reserved.
</p>
