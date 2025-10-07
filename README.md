# 🔋 Symulacja Baterii dla ROS2

Node ROS2 symulujący realistyczne zachowanie baterii w robotach mobilnych. Bateria rozładowuje się podczas pracy i ładuje się automatycznie.

## ✨ Funkcje

- ⚡ Realistyczna symulacja rozładowania i ładowania baterii
- 💡 Wizualizacja stanu baterii za pomocą diod LED
- 🔄 Automatyczne przełączanie między trybami rozładowania i ładowania
- 📊 Monitoring stanu baterii w czasie rzeczywistym

## 📦 Packages

### `my_robot_interfaces`
Niestandardowe interfejsy ROS2 dla komunikacji:

- 🔌 **SetLed.srv** - Serwis do sterowania diodami LED
- 📡 **LedStateArray.msg** - Wiadomość ze stanem panelu LED

## 📁 Pliki
battery.py          # 🔋 Główny node symulacji baterii
led_panel.py        # 💡 Node kontrolujący panel LED
