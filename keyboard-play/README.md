# Toddler Keyboard Fun 🎹

A simple, interactive web game designed for toddlers (approx. age 2+) to make learning letters, numbers, and words fun.


## ✨ Features



* **Instant Feedback:** Every key press displays a large Emoji, the letter, and the associated word (e.g., "A" for "Apple").
* **Audio Learning:** Uses the browser's built-in Text-to-Speech engine to read the letters and words aloud.
    * *Note:* Automatically prioritizes a female voice (e.g., Google US English, Samantha, Zira) for a friendly tone.
* **Visual Stimulation:** Background changes to a random pastel color with every interaction to keep engagement high.
* **Touch Friendly:** Tapping anywhere on the screen (on tablets/phones) generates a random letter/surprise, so precision isn't required for little ones.
* **Single File:** The entire game is contained in one HTML file. No downloads, servers, or complex installation required.


## 🚀 How to Play



1. Download the toddler_keyboard_game.html file.
2. Open the file in any modern web browser (Chrome, Safari, Edge, Firefox).
3. Click the **"Click to Play"** button (required to enable audio).
4. Let your toddler mash the keyboard or tap the screen!


## 🛠️ Customization

You can easily change the emojis or words by editing the keyMap object inside the &lt;script> tag in the HTML file:

const keyMap = { \
    'a': { emoji: '🍎', word: 'Apple' }, \
    'b': { emoji: '🐻', word: 'Bear' }, \
    // ... add your own! \
}; \



## 📱 Compatibility

Works on desktop, tablets, and mobile devices.



* **Desktop:** Keyboard navigation.
* **Mobile/Tablet:** Tap interaction (randomizes input).

*Note: Audio functionality relies on the Web Speech API, supported by all modern browsers.*


## 📄 License

Feel free to use, modify, and share this project!

