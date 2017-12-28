{
  "name": "crypto-trading-tracker",
  "version": "1.0.0",
  "main": "main.js",
  "description": "A menu bar app that provides cryptocurrencies prices on trading markets in real-time",
  "author": "Hardik Jain",
  "scripts": {
    "publish": "build -p always"
  },
  "devDependencies": {
    "electron": "^1.7.9",
    "electron-builder": "^19.49.0"
  },
  "dependencies": {
    "axios": "^0.17.1",
    "cloudscraper": "^1.4.1",
    "electron-google-analytics": "0.0.24",
    "electron-log": "^1.3.0",
    "electron-prompt": "^0.5.0",
    "electron-store": "^1.3.0",
    "electron-updater": "^2.16.1",
    "node-notifier": "^5.1.2",
    "path": "^0.12.7",
    "raven": "^2.3.0",
    "request": "^2.49.0",
    "tough-cookie": "^0.12.1"
  },
  "build": {
    "publish": [
      {
        "provider": "github",
        "owner": "hardikjain29",
        "repo": "crypto-trading-tracker"
      }
    ],
    "appId": "com.github.hardikjain29.crypto-trading-tracker",
    "mac": {
      "category": "public.app-category.utilities",
      "icon": "assets/mac_icon.icns",
      "target": [
        "zip",
        "dmg"
      ]
    },
    "dmg": {
      "background": "assets/background.tiff"
    }
  }
}
