```
         ______ __      __  __  __  __ ____ __  __    ____   ____ ____   ___  
        / ____// /     / / / / /  |/  // __// / / /   / __ ) /  _// __ \ / __ \ 
       / /    / /     / / / / / /|_/ /_\ \ / /_/ /   / __  | / / / /_/ // / / / 
      / /___ / /___  / /_/ / / /  / //___// __  /   / /_/ /_/ / / _, _// /_/ /  
      \____//_____/  \____/ /_/  /_//___//_/ /_/   /_____//___//_/ |_|/_____/   
                                                                                
                    [ COCKPIT FLIGHT INTERFACE v2.0.sh ]
```

---

A high-fidelity, retro-futuristic **Flappy Bird** clone built on the **melonJS** framework. Upgraded with an immersive spaceship cockpit simulator wrapper, real-time diagnostic systems, custom neon styles, and a scrolling telemetry console log.

## 🛰️ SYSTEM FEATURES

| MODULE | DESCRIPTION | INFRASTRUCTURE |
| :--- | :--- | :--- |
| **Cockpit HUD Wrapper** | Futuristic dashboard frame containing real-time flight telemetry indicators. | HTML5 / CSS Grid |
| **Active Flight Hiding** | The sidebars collapse automatically to expand the gameplay window. | Custom State Hooks |
| **Theme Customizer** | Choose between `Matrix green`, `Cyberpink`, `Amber terminal`, or `Classic retro` palettes. | CSS Theme Tokens |
| **Scrolling Telemetry** | A command-line console printing real-time event logs for flaps, scores, and collisions. | JavaScript Logger |
| **Event Leaderboard** | Scrollable records saving unlimited players and scores locally for group events. | LocalStorage |
| **Record Purging** | Passcode-protected (`Nikita@271007`) bulk delete system to manage leaderboard slots. | SHA-Secure Purger |
| **Scanline Overlay** | A hardware scanline simulation CRT filter toggled straight from the settings dashboard. | CSS Scanline Mesh |

---

## 🚀 STARTING THE SIMULATION

### Prerequisites
Ensure you have [NodeJS](https://nodejs.org/) installed on your machine.

### Installation
Clone the repository and install the dependencies:
```bash
git clone https://github.com/simplyvardaan/clumsy_bird.git
cd clumsy_bird
npm install
```

### Running Locally
To launch the cockpit server, execute:
```bash
npm run dev
# Or run with http-server:
npx -y http-server -p 8000
```
Open **[http://localhost:8000](http://localhost:8000)** in your web browser.

---

## 🎮 FLIGHT MANUAL

1. **Credentials**: Enter your Pilot Handle on start to link database records.
2. **Propulsion**: Click **anywhere on the game screen** to engage engines (500ms ghost click protection enabled).
3. **Flap**: Press `SPACEBAR` or click/tap the screen to jump.
4. **Volume**: Adjust volume sliders directly on the settings board, or press `M` to toggle mute.
5. **Fullscreen**: Click the expand icon on the game title bar to enter a distraction-free, floating HUD desktop cockpit.
6. **Leaderboard Purging**: Click checkboxes next to scores on the leaderboard, click the red trash icon in the header, and authenticate with `Nikita@271007` to delete.

---

```
[SYSTEM STATUS: READY]
[PILOT ACCESS PORTAL: LINKED]
[AWAITING ENGINE IGNITION COGNITIVE PROTOCOLS...]
```
