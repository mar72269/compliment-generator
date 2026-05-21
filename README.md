# AI Output Engine | Card UI

A sleek, futuristic single-page web application that generates developer-focused compliments and programming jokes. It features a cyberpunk-inspired "Playing Card" interface, ambient CSS animations, and a real-time 3D visualization powered by Three.js.

## ✨ Features

* **3D Interactive Art**: A rotating, wireframe Torus Knot with a particle ring rendered via Three.js. The animation accelerates when "fetching" data.
* **Ambient Aurora Background**: A soothing, CSS-animated glowing background that floats behind the interface.
* **Typewriter Reveal Effect**: Text is printed to the screen character-by-character. Jokes feature a custom 2-second dramatic pause before delivering the punchline.
* **Dynamic UI Elements**: Corner card icons change randomly (both emoji and color) upon every interaction.
* **Curated Content**: Includes exactly 100 quirky, developer-centric compliments and 50 classic programming jokes.
* **Zero Dependencies**: Entirely self-contained in a single HTML file (Three.js is imported via CDN). No build tools required!

## 🚀 Technologies Used

* **HTML5** & **CSS3** (Flexbox, CSS Variables, Keyframe Animations)
* **Vanilla JavaScript** (ES6+)
* **Three.js** (WebGL 3D Rendering)
* **Google Fonts** (Inter & JetBrains Mono)

## 🛠️ Getting Started

Because this project is a single-file application with no build steps or local dependencies, running it is incredibly simple:

1. Clone or download this repository.
2. Ensure you have an active internet connection (required to load the Google Fonts and Three.js CDN).
3. Open the `index.html` file directly in any modern web browser (Chrome, Firefox, Safari, Edge).

## 🎮 Usage

Once the application is loaded, you will see the system initialize. You have two actions available at the bottom of the card:

* **Generate Compliment**: Click this to receive a wholesome, tech-related compliment to boost your day.
* **Generate Joke**: Click this to receive a programming joke. Watch the state badge update and wait for the punchline!

## ⚙️ Customization

You can easily modify the content to suit your own needs by editing the JavaScript arrays inside the `<script>` tag:

* **Compliments**: Find the `const compliments = [...]` array and add/replace strings. 
* **Jokes**: Find the `const jokes = [...]` array. Jokes must be formatted with a pipe character (`|`) separating the setup and the punchline.
  * *Example:* `"Setup goes here|Punchline goes here"`
* **Icons & Colors**: Modify the `icons` and `colors` arrays to change the random visual flairs applied to the card corners.