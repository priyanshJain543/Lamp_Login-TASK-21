# 💡 Interactive Lamp Login Form

A whimsical, interactive login interface where a draggable SVG lamp cord toggles the visibility of a "glowing" login form. Built with heavy focus on SVG animations and dynamic CSS variables.

## 🔗 Live Demo
[**Click here to view the Live Demo**]() 🚀

---

## ✨ Features

* **Interactive Physics:** A draggable SVG cord using GSAP's `Draggable` and `MorphSVG`.
* **Dynamic UI Reveal:** The login form is hidden in the "dark" and pops into view with a scale animation when the lamp is toggled ON.
* **Procedural Coloring:** Every pull of the cord generates a random `hue` that updates the lampshade, the form glow, and the button gradient.
* **Expressive SVG:** The lamp character features animated eyes and a mouth that reacts to the light state.
* **Audio Feedback:** Includes a tactile "click" sound effect when the switch is activated.

## 🛠️ Tech Stack

* **HTML5 / SVG:** For the complex vector-based character and structure.
* **CSS3 Custom Properties:** Uses variables like `--on` and `--glow-color` to sync the JS logic with the stylesheet.
* **GSAP (GreenSock):**
    * `Draggable`: For the cord-pulling interaction.
    * `MorphSVG`: For realistic cord movement and snapping.
    * `Timeline`: To orchestrate the light and form transitions.

