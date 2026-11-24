# Valet Parking

A canvas-based car movement exercise.

**Repository created:** 2021-07-29  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2021-07-29

## Features and implementation

- Parking background and green car assets.
- Arrow-key event handling.
- Position updates in four directions.

## Technologies

HTML, CSS, JavaScript, Bootstrap, jQuery.

## How the code works

`uploadBackground()` and `uploadgreencar()` place the scene assets; `my_keydown()` dispatches movement to the four direction functions.

## Project structure

| File | Purpose |
| --- | --- |
| [`index.html`](index.html) | Main page and user interface |
| [`main.js`](main.js) | Project-specific JavaScript |

Key functions in the source:
- `main.js`: `add()`, `uploadBackground()`, `uploadgreencar()`, `my_keydown()`, `up()`, `down()`, `left()`, `right()`.

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/Valvet_Parking_app.git
cd Valvet_Parking_app
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Use the arrow keys to move the car.

## Current status and limitations

No parking validation or scoring system is demonstrated.

---

Source reference: [`f4c78250`](https://github.com/Avenger-Sonic123/Valvet_Parking_app/tree/f4c7825029e7a704569dc4397fca7ae23b1bae5c) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
