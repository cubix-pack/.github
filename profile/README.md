<p align="center">
  <img src="../assets/cubix_logo.svg" width="200" />
</p>


<h3 align="center">The Smart Cube for Intentional Focus</h3>

<p align="center">
  <a href="https://cubix-website-weld.vercel.app">
    <img src="https://img.shields.io/badge/Website-cubix--website-blueviolet?style=for-the-badge&logo=vercel" alt="Website" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tauri-%2324C8DB.svg?style=for-the-badge&logo=tauri&logoColor=white" alt="Tauri" />
  <img src="https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="NodeJS" />
  <img src="https://img.shields.io/badge/Express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB" alt="ExpressJS" />
  <img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white" alt="WebSockets" />
</p>


Cubix is a physical productivity system designed to make context-switching intentional and tangible. Instead of juggling focus modes through apps or shortcuts, users flip a **physical smart cube** to activate different productivity modes across their entire ecosystem.

---

## 🚀 The Vision

In a world full of digital distractions, Cubix brings physicality back to productivity. By moving the "mode switch" from the screen to a physical device, users create a psychological anchor for their work, study, and leisure time.

### 🎥 See it in Action
<p align="center">
  <img src="../assets/demo.gif" width="400" alt="Cubix Demo" />
</p>



---

## 🛠️ The Cubix Ecosystem

The Cubix ecosystem is a multi-platform powerhouse that ensures your focus is never broken, regardless of which device you're using.

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Physical Cube** | Hardware (BLE) | The tangible interface with 6 detectable orientations. |
| **Mobile App** | [Flutter](https://github.com/cubix-pack/cubix-mobile) | The control center. Reads the cube via BLE and broadcasts modes. |
| **Backend Server** | [Express.js](https://github.com/cubix-pack/cubix-backend) | The real-time relay using WebSockets to sync all devices. |
| **Desktop App** | [React + Tauri](https://github.com/cubix-pack/cubix-desktop) | Enforces system-level app blocking and provides UI feedback. |
| **Web Extension** | [Chrome Extension](https://github.com/cubix-pack/cubix-web-extenstion) | Blocks distracting websites instantly based on the current mode. |
| **Website** | [React + Vite](https://github.com/cubix-pack/cubix-website) | The informational hub and landing page for the project. |

---

## 🛠️ Technical Architecture

<p align="center">
  <img src="../assets/arch.png" width="100%" alt="Cubix Architecture Diagram" />
</p>

---

## 🌓 Productivity Modes

Each face of the cube corresponds to a unique mode tailored for specific tasks:

*   🔴 **Deep Work**: Maximum focus. Blocks all non-essential apps and sites.
*   🟢 **Pomodoro**: Structured 25-minute sprints with automated break reminders.
*   🟣 **Entertainment**: Curated leisure time mode. Work apps are hidden.
*   🔵 **Meetings**: Optimized for collaboration. Clears the workspace for calls.
*   ⚪ **Offline**: Zero distractions. Ultimate isolation for deep thought.
*   🟡 **Idle**: The default state. Full access to all tools.

---

## ✨ Key Features

*   **Physicality Matters**: Flipping a cube is an intentional act that signals your brain to focus.
*   **Multi-Device Sync**: Activation on the physical cube auto-syncs to your phone, desktop, and browser extension.
*   **Hardcore Blocking**: System-level restrictions that go beyond simple app-blocking.
*   **Time-Locked Tasks**: Lock the cube face for a set duration to ensure accountability.
*   **Offline Resilience**: Works even if one device is disconnected; syncs instantly upon reconnecting.

---

## 🧠 Meet the Minds

<table align="center">
  <!-- Leader Row -->
  <tr>
    <td align="center" colspan="4">
      <a href="https://github.com/bradocola">
        <img src="https://github.com/bradocola.png" width="100">
        <br />
        <sub><b>Omar Nagy</b><br/>(Leader)</sub>
      </a>
    </td>
  </tr>
  <!-- Team Row 1 -->
  <tr>
    <td align="center">
      <a href="https://github.com/georgeibrahim1">
        <img src="https://github.com/georgeibrahim1.png" width="100">
        <br />
        <sub>George Ibrahim</sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Astronaut1984">
        <img src="https://github.com/Astronaut1984.png" width="100">
        <br />
        <sub>George Bahij</sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/karimnader121">
        <img src="https://github.com/karimnader121.png" width="100">
        <br />
        <sub>Karim Nader</sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/PierreEhab-1337">
        <img src="https://github.com/PierreEhab-1337.png" width="100">
        <br />
        <sub>Pierre Ehab</sub>
      </a>
    </td>
  </tr>
  <!-- Team Row 2 -->
  <tr>
    <td align="center">
      <a href="https://github.com/adham-19">
        <img src="https://github.com/adham-19.png" width="100">
        <br />
        <sub>Adham Mansour</sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/AhmedEssam005">
        <img src="https://github.com/AhmedEssam005.png" width="100">
        <br />
        <sub>Ahmed Essam</sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Hussein-M-H">
        <img src="https://github.com/Hussein-M-H.png" width="100">
        <br />
        <sub>Hussien Mohamed</sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Matou1306">
        <img src="https://github.com/Matou1306.png" width="100">
        <br />
        <sub>Mathieu Morcos</sub>
      </a>
    </td>
  </tr>
  <!-- Team Row 3 -->
  <tr>
    <td align="center" colspan="2">
      <a href="https://github.com/Hassan7Eladl">
        <img src="https://github.com/Hassan7Eladl.png" width="100">
        <br />
        <sub>Hassan Eladl</sub>
      </a>
    </td>
    <td align="center" colspan="2">
      <a href="https://github.com/YoussefMaged004">
        <img src="https://github.com/YoussefMaged004.png" width="100">
        <br />
        <sub>Youssef Maged</sub>
      </a>
    </td>
  </tr>
</table>

---

<p align="center">
  Built with ❤️ by the Cubix Team
</p>
