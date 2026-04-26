# Calm / BreathSync

An interactive web application that provides a minimalist breathing interface with synchronized visual timing and ambient audio to support focus and relaxation.

## Overview

This project is a lightweight browser-based breathing guide that uses a simple timed visual rhythm (1–4 count cycle) combined with ambient audio playback. Users can interact with the page to toggle sound on and off while following a structured breathing pattern.

The goal was to build a calming, distraction-free interface using only vanilla web technologies.

---

## Features

- Animated 4-step breathing count (1–4 cycle)
- Click-to-toggle audio mute/unmute functionality
- Continuous looping ambient background audio
- Minimal UI design focused on reducing cognitive load
- Icon-based controls using Lucide icons
- Fully responsive, browser-based implementation

---

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Lucide Icons
- HTML5 Audio API

---

## How It Works

- On page load, the application initializes icon rendering and starts background audio playback
- A global click event listener toggles audio state between muted and unmuted
- Visual breathing indicators (1–4) are displayed as a repeating cycle to guide pacing
- Audio playback runs in a continuous loop to support focus and relaxation

---

## Key Implementation Details

- Uses the HTML5 `<audio>` element with looped playback for ambient sound
- Controls audio state dynamically through JavaScript event listeners
- Icon states are updated in real time by modifying DOM opacity
- External icon library (Lucide) is loaded via CDN for lightweight UI enhancement

---

## Purpose

This project was built to explore:
- DOM manipulation and event handling in JavaScript
- Real-time UI state changes
- Minimalist interface design principles
- Creating calming user experiences through web technologies

---

## Future Improvements

- Add configurable breathing patterns (e.g., 4-7-8 breathing)
- Add start/pause cycle control instead of click toggle
- Improve accessibility (keyboard controls + ARIA labels)
- Add visual animations synced to breathing cycle
- Volume slider instead of binary mute toggle

---

## Author

Christopher Wong  
