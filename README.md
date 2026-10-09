# Neon Crust Diner

A retro neon pizzeria game you play with your hands. Take orders at the window, build each pie, bake it, slice it and serve it. It runs on desktop with your webcam, and in VR on a headset.

## Play

- **Desktop:** open `index.html` in Chrome or Edge, press **Open the diner** and allow the camera. There's also a mouse mode for practice.
- **VR:** open the page in your headset's browser (for example Meta Quest Browser) and press **Enter VR**. Use your hands (pinch) or controllers (trigger).

An internet connection is needed the first time, to load three.js and MediaPipe hand tracking from public CDNs.

## How it plays

1. **Order:** customers queue at the window. Ring the bell to take the order, and a ticket prints with toppings by region, bake level and slice count.
2. **Build:** start with dough, paint on sauce and cheese, then drop toppings where the ticket asks.
3. **Bake:** two ovens keep baking while you work elsewhere. Take each pie out when the needle is in the green zone.
4. **Cut:** drag across the centre to slice the pie evenly, then serve.

Each customer scores you on **Waiting, Building, Baking and Cutting**. Good scores earn tips and points, points raise your rank, and ranks unlock new toppings. Progress saves in your browser.

## Tech

A single HTML file. It uses three.js (WebGL and WebXR), MediaPipe Tasks Vision for webcam hand tracking, and the Web Audio API for sound and the jukebox loop.
