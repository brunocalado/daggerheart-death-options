# 🗡️ Daggerheart: Death Options

**Daggerheart: Death Options** is a Foundry VTT module designed to elevate the tension and immersion of the "Death Move" moment in the game. Instead of a simple manual procedure, this module presents the player with the three canonical choices in a dramatic, audiovisual interface.

---

## 🌟 Features

* **Cinematic Selection Screen:** When triggered, the player is presented with a full-screen overlay featuring three distinct options: **Avoid Death**, **Blaze of Glory**, and **Risk it All**.
* **Avoid Death:**
    * **Suspenseful Countdown:** A 6-second countdown builds tension before the roll.
    * **Automatic Check:** Automatically rolls a die and compares it against the linked character's Level.
    * **Visual Results:** Displays a unique cinematic image depending on whether the result is **Safe** or a **Scar**.
* **Blaze of Glory:**
    * Triggers a dramatic sound effect and displays a "Blaze of Glory" splash art, allowing the player to narrate their final heroic moment.
* **Risk it All:**
    * **The Classic Experience:** A 6-second countdown followed by the rolling of the Hope and Fear dice.
    * **3D Dice Integration:** Seamlessly integrates with Dice So Nice!
    * **Cinematic Results:** Plays specific images and sounds for **Hope**, **Fear**, or **Critical Success**.
    * **Rule Explanations:** Automatically posts the correct rule interpretation in the chat (e.g., clearing stress, taking scars, or death) based on the roll result.
* **Immersive UI:** Unselected buttons fade away when a choice is made, focusing everyone's attention on the unfolding fate.

---

## 🛠️ Usage

1.  **GM Trigger:** As a Gamemaster, create a macro with the following command:
    ```javascript
    DeathOptions.trigger();
    ```
    *(Note: The old `RiskItAll.trigger()` is deprecated but still supported for compatibility).*

2.  **Select Player:** Run the macro and select the dying player from the list.
3.  **Choose Your Fate:** The player receives the Death Options screen. Once they click a button, the sequence begins for all connected players.

---

## ⚙️ Configuration

Go to **Configure Settings > Module Settings > Daggerheart: Death Options** to customize every aspect of the experience:

### Images
* **Image: Main Screen:** Background for the selection menu.
* **Image: Blaze of Glory:** Shown when Blaze of Glory is chosen.
* **Image: Avoid Death (Scar):** Shown if the Avoid Death roll fails.
* **Image: Avoid Death (Safe):** Shown if the Avoid Death roll succeeds.
* **Image: Result Hope:** Shown for a Risk it All Hope result.
* **Image: Result Fear:** Shown for a Risk it All Fear result.
* **Image: Result Critical:** Shown for a Risk it All Critical result.

### Audio
* **Sound: Countdown:** Suspense music played during the 6s countdowns.
* **Sound: Blaze of Glory:** Sound effect for the Blaze of Glory choice.
* **Sound: Result Hope:** Audio for a Hope result.
* **Sound: Result Fear:** Audio for a Fear result.
* **Sound: Result Critical:** Audio for a Critical result.

---

## Manual Instalation
Go to **modules** and paste the link. 
Link: https://raw.githubusercontent.com/brunocalado/daggerheart-death-options/main/module.json

---

# Changelog
You can read changes at [Changelog](CHANGELOG.md)

---

### Credits and License
-   Code license at [LICENSE](LICENSE).
- The audio and images are AI, so they are under [public domain](https://creativecommons.org/publicdomain/zero/1.0/).

**Disclaimer:** This module is an independent creation and is not affiliated with Darrington Press.

