# ZERO HOUR — Outbreak Simulator 🌍

<img width="1906" height="886" alt="screenshot" src="https://github.com/user-attachments/assets/bcd7eaf1-dbd2-4040-a3d0-75b77774c764" />

---

ZERO HOUR is a browser-based global outbreak strategy simulator featuring 12 playable pathogen types, branching evolution trees, international transmission networks, reactive governments, and a fully playable Cure Mode.

Create a pathogen and guide its evolution across an interactive world map — or switch sides and coordinate humanity’s response through research, containment, manufacturing, distribution, and public trust.

Built as a single-file application, the project combines a custom simulation engine, Canvas-based cartography, procedural audiovisual systems, live reference media, and persistent browser saves.

## 🌐 Live Website

**Live site:** https://zero-hour-coral.vercel.app/

---

## 🎮 About the Project

ZERO HOUR offers two opposing strategic perspectives.

### Pathogen Mode

Choose a pathogen, name it, and select the country where patient zero appears.

Spend Evolution Points on transmission, symptoms, resistance, and genetic adaptations. Balance spread, visibility, and lethality while governments introduce countermeasures and researchers work toward a treatment.

Different evolutionary strategies can lead to extinction, civilization collapse, or a silent global takeover.

### Cure Mode

Take control of the global response to an evolving outbreak.

Identify the threat, develop a viable intervention, manage containment policies, expand production, distribute doses, and maintain public cooperation.

Success requires more than completing research: treatments must reach populations, hospitals must remain functional, and public trust must survive the response.

---

## 🚀 Features

### Interactive World Map

* **Custom Canvas Map:** World geography rendered directly through the Canvas 2D API.
* **Embedded Geographic Data:** Natural Earth boundaries distributed through world-atlas and TopoJSON.
* **Country Selection:** Choose a starting country and inspect individual national conditions.
* **Pan & Zoom:** Explore the map with mouse and touch interactions.
* **Animated Travel Networks:** Visualize international movement and outbreak activity.
* **Population Lights:** City-light effects reflect the state of the simulated world.
* **Country Detail Panels:** Inspect population, infections, deaths, infrastructure, stability, and response measures.

### 12 Playable Pathogen Types

Each pathogen has its own starting characteristics, passive advantages, trade-offs, and exclusive evolution content.

| Pathogen | Strategic Identity |
| :--- | :--- |
| Bacteria | Balanced adaptation and affordable resistance |
| Virus | Frequent mutations and rapid evolution |
| Fungus | Resilient spores and environmental survival |
| Parasite | Stealthy, patient spread |
| Prion | Low visibility and difficult research |
| Nano-Swarm | Controlled evolution without random mutations |
| Bio-Weapon | High starting lethality and immediate visibility |
| Neuro-Strain | Behavioral disruption and weakened compliance |
| Cryo-Relic | Cold resistance and environmental adaptation |
| Symbiont | Strong stealth and additional evolution income |
| Xeno-Spore | Unusual biology and broad climate resistance |
| Zoonotic Spillover | Animal reservoirs and transmission advantages |

### Evolution & Adaptation

* **Four Shared Evolution Branches:**
  * Transmission
  * Symptoms
  * Abilities
  * Genome
* **Type-Exclusive Trees:** Additional evolutionary options unique to each pathogen.
* **Prerequisite-Based Progression:** Unlock advanced traits through connected dependencies.
* **Trait Synergies:** Discover combinations that produce additional effects.
* **Random Mutations:** Adapt to unexpected changes during the outbreak.
* **Evolution Point Economy:** Earn and spend points to shape your strategy.
* **Tree Navigation:** Search traits, navigate prerequisites, and pan or zoom through the upgrade interface.

### Global Transmission Simulation

* **International Spread:** Infection moves through land connections, flights, and shipping.
* **Environmental Differences:** Climate affects how effectively pathogens spread.
* **National Characteristics:** Wealth, healthcare, urbanization, population, and government type influence outcomes.
* **Regional Dynamics:** Countries contain multiple population compartments rather than a single uniform infection counter.
* **Travel Restrictions:** Border, airport, and port closures alter international transmission.

### Reactive Governments & Society

* **Growing Awareness:** Public and government responses intensify as the outbreak becomes visible.
* **Containment Measures:** Countries introduce interventions such as masking, lockdowns, and travel restrictions.
* **Healthcare Pressure:** Severe outbreaks strain hospitals.
* **Social Instability:** Worsening conditions can damage stability and lead to collapse.
* **Research Race:** Humanity develops and deploys treatment while the pathogen continues evolving.

### Playable Cure Mode

Cure Mode introduces a separate response-focused progression system.

* **Four Response Branches:**
  * Research
  * Logistics
  * Containment
  * Public Trust
* **Outbreak Investigation:** Improve detection and identification of the threat.
* **Research Pipeline:** Advance through development, trials, approval, manufacturing, and deployment.
* **Clinical Setbacks:** Failed trials can delay progress.
* **Manufacturing Capacity:** Expand facilities, secure supplies, and increase output.
* **Distribution Networks:** Improve cold-chain infrastructure, delivery, and access.
* **Country Policies:** Apply containment measures while managing their social consequences.
* **Public Trust:** Cooperation and uptake depend on public confidence.
* **Evolving Opposition:** Respond to a pathogen that continues adapting during the operation.

### News, Statistics & Endings

* **Dynamic News Feed:** Follow outbreak developments, government responses, mutations, and major events.
* **Country Tables:** Compare national conditions through sortable data panels.
* **Timeline Charts:** Review the outbreak’s progression over time.
* **Multiple Pathogen Endings:** Extinction, civilization collapse, silent takeover, treatment deployment, or pathogen eradication.
* **Separate Cure Outcomes:** Review the results of humanity’s response.
* **Scores & Rankings:** Receive an end-of-run score and rank.
* **Local Best Scores:** Store high-scoring results in the browser.
* **Result Sharing:** Copy a text summary of the completed run.

### Audio, Broadcasts & Reference Media

* **Procedural Music:** Generate a dynamic score through the Web Audio API.
* **Synthesized Sound Effects:** Audio feedback for interactions and simulation events.
* **Speech Synthesis:** Browser-generated spoken broadcasts.
* **Archive Recordings:** Optional recordings resolved through Wikimedia Commons.
* **City Photography:** Live photographs and summaries retrieved from Wikipedia and Wikimedia sources.
* **Media Controls:** Adjust audio levels, speech, captions, and optional media.

### Saving & Interface Options

* **Save & Continue:** Resume an outbreak from local browser storage.
* **Automatic Saving:** Optional autosaves during play.
* **Persistent Settings:** Store audio and interface preferences locally.
* **Responsive Layout:** Adapt panels and controls to smaller screens.
* **Touch Navigation:** Map interaction supports touch input.
* **Reduced-Motion Options:** Adjust visual effects and motion preferences.
* **Built-In Tips:** Contextual guidance for game systems.

---

## 🛠 Tools & Technologies Used

* **HTML5:** Application structure.
* **CSS3:** Responsive layouts, custom properties, overlays, and interface effects.
* **JavaScript:** Simulation, progression, event handling, saving, and UI state.
* **Canvas 2D API:** World map, charts, particles, and animated overlays.
* **SVG:** Procedural pathogen illustrations and interface graphics.
* **TopoJSON Client:** Geographic topology conversion and boundary processing.
* **world-atlas / Natural Earth:** Embedded world-map data.
* **Web Audio API:** Procedural music and sound effects.
* **Web Speech API:** Synthesized spoken broadcasts.
* **Wikipedia / Wikimedia APIs:** Optional photographs, summaries, and archive recordings.
* **localStorage:** Saves, settings, tips, cached media metadata, and best scores.
* **Google Fonts:** Rajdhani and Orbitron typography.

The application does not require a backend service or build pipeline for its core simulation.

---

## ▶️ How to Run Locally

The application is contained in `zero-hour.html`.

### Recommended Method

1. Open the project folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `zero-hour.html`.
4. Select **Open with Live Server**.

No dependency installation or compilation is required.

For static hosting, rename the game file to `index.html`.

### Network Requirements

World-map data and simulation code are embedded in the file.

Optional external features — including Google Fonts, city photographs, summaries, and archive recordings — require an internet connection.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| Spacebar | Pause / resume |
| 1 | Select simulation speed 1 |
| 2 | Select simulation speed 2 |
| 3 | Select simulation speed 3 |
| E | Open / close evolution or response research |
| S | Open statistics |
| N | Open news |
| C | Fit the world map to the screen |
| M | Toggle audio mute |
| Escape | Close the active panel, clear country selection, or open the menu |

Keyboard shortcuts are disabled while typing in form fields.

---

## 💾 Save Data

Game saves, settings, tips, and best scores are stored in the current browser using localStorage.

Saves are local to the browser and device. They are not synchronized through an account or cloud service.

Clearing site data can remove saved progress.

---

## 📁 Project Structure

Current single-file layout:

```text
zero-hour/
└── zero-hour.html
```

The file contains the interface, styles, geographic data, simulation engine, evolution systems, Cure Mode, rendering, audio, and save logic.

---

## 📌 Status

### Currently Playable

* Pathogen Mode with 12 pathogen types.
* Cure Mode with dedicated research and response systems.
* Five difficulty levels: Casual, Normal, Brutal, Mega Brutal, and Nightmare.
* Saving, statistics, news, scoring, and configurable audiovisual features.

### Coming Soon

The current interface previews these special modes, but they are not playable:

* **Zombie Mode**
* **War Mode**

**Deployment:** Deployed using Vercel

---

## 🧠 Technical Takeaways

This project demonstrates:

* **Simulation Architecture:** Separating core simulation logic from DOM-based interface code.
* **Event-Driven Systems:** Connecting simulation events to news, audio, notifications, and UI updates.
* **Custom Cartography:** Converting geographic topology into interactive Canvas paths.
* **Compartment-Based Modeling:** Tracking changing population states across interconnected regions.
* **Dependency Graphs:** Building searchable evolution and response trees with prerequisites and synergies.
* **Asymmetric Game Design:** Supporting both outbreak creation and humanity’s response.
* **State Serialization:** Saving and restoring complex simulation state.
* **Asynchronous Media:** Loading optional reference media without making it part of the core simulation.
* **Browser Audiovisual Programming:** Combining procedural music, sound effects, speech, and animation.

---

## 📚 Credits & Attribution

* **Map boundaries:** Natural Earth, distributed through world-atlas.
* **Topology processing:** TopoJSON Client.
* **City photographs and summaries:** Wikipedia and Wikimedia Commons contributors.
* **Archive recordings:** Wikimedia Commons contributors.
* **Selected orchestral recordings:** Musopen performances available through Wikimedia Commons.
* **Typography:** Rajdhani and Orbitron through Google Fonts.

External media may carry individual attribution and licensing requirements. Retain the application’s credits and check asset-specific terms when redistributing media.

---

## ⚠️ Note

ZERO HOUR is a fictional strategy game, not a scientific forecasting tool or a source of medical guidance.

Population characteristics, pathogen behavior, research timelines, and public-health systems are simplified or fictionalized for gameplay.

The project is an independent outbreak simulation and is not affiliated with other games in the genre.
