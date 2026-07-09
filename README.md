#  DeskBot
*A Wi-Fi Connected Desktop Companion built with an ESP32*

ESPBuddy is a desktop companion robot powered by an ESP32. It features expressive animated eyes, real-time phone notifications, Spotify integration, charging animations, sounds, and personality—all displayed on a tiny OLED screen.

Unlike many simple OLED face projects, ESPBuddy behaves like a living desk companion that reacts to events around it.

---

#  Features

### Expressive Animated Face
- Smooth eye movement
- Multiple facial expressions
- Animated pupils
- Mouth animation while speaking
- Automatic blinking
- Curious eye movements
- Sleepy, angry, surprised, happy and many more expressions

---

### Phone Notifications
- Receives notifications over Wi-Fi
- Displays:
  - App
  - Sender
  - Message
- Smart notification queue
- Duplicate notification filtering
- Notification sounds
- Expression changes based on events

---

### Spotify Integration
- Shows currently playing song
- Displays artist
- Automatic Spotify screen
- Spotify notification sound

---

### Charging Detection
- Detects charger connection
- Animated charging battery
- Smooth charging animation
- Charging status updates instantly

---

### Clock
- Real-time clock via NTP
- 12-hour format
- AM/PM display
- Animated top bar

---

### Audio
- Robot sounds
- Notification sounds
- Spotify sounds
- Future support for voice effects

---

### Personality System

Current emotions include:

- Normal
- Happy
- Curious
- Angry
- Sleepy
- Sad
- Heart Eyes
- Dizzy
- Dead
- Surprised

The robot automatically reacts to:
- Notifications
- Spotify
- Charging
- Random idle behaviour

---

# Hardware

## Main Components

- ESP32 LOLIN32
- SSD1306 OLED Display (128×64)
- Passive Buzzer
- TP4056 Charging Module
- 18650 Li-ion Battery
- USB-C Charging Board
- Switch
- 3D Printed Enclosure *(Coming Soon)*

---

# Connectivity

- Wi-Fi
- WebSockets
- JSON Communication
- Android Notification Forwarding
- Spotify Integration

---

# Project Structure

```
src/
│
├── Face Animation
├── Expressions
├── Notification System
├── Spotify Integration
├── OLED Rendering
├── Battery Management
├── Audio
├── WiFi
├── WebSocket
├── Utilities
```

---

# Technologies

- ESP32
- PlatformIO
- Arduino Framework
- ArduinoJson
- Adafruit SSD1306
- Adafruit GFX
- WebSockets

---

# Current Features

✔ Animated eyes

✔ Multiple expressions

✔ Mouth animation

✔ Notification queue

✔ Spotify support

✔ Charging animation

✔ Robot sounds

✔ NTP Clock

✔ Wi-Fi connectivity

✔ OLED UI

✔ Battery charging detection

---

#  Planned Features

- Voice assistant
- Weather
- Calendar reminders
- AI conversations
- Servo head movement
- Capacitive touch
- Ambient lighting
- Companion mode
- Sleep mode
- More animations

---

# Companion Android App

A companion Android application sends:

- Notifications
- Spotify metadata
- Future sensor data

to the ESPBuddy over Wi-Fi.


# ❤️ Author

Created by **Harshul**
