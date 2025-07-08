# 🚀 Titan Space Program

A complete spaceflight simulation from Earth to Titan with JavaFX. Includes orbital mechanics, engine physics, landing dynamics, and a fully interactive UI.

## 🛠 Tech Stack

Java · JavaFX · Gradle · JUnit · Object-Oriented Programming · Numerical Simulation

---

## ✨ Features

- Real-time spaceflight simulation from Earth to Titan
- Accurate orbital mechanics and atmospheric physics
- Wind and landing experiments using numerical solvers
- Fully interactive JavaFX GUI with mission and engine logs
- Runnable JARs for both full mission and landing simulation
- Built-in unit tests and complete documentation

## 🎮 How to Run

1. Open Terminal and go to the project folder:
   ```
   cd path/to/your/folder
   ```

2. To start the full mission:
   ```
   java --module-path /path/to/javafx/lib --add-modules javafx.controls,javafx.fxml -jar dist/titanApproach.jar
   ```

3. To start directly from the Titan landing phase:
   ```
   java --module-path /path/to/javafx/lib --add-modules javafx.controls,javafx.fxml -jar dist/titanLanding.jar
   ```

> ℹ️ Make sure JavaFX is installed and the module path is correct.

---

## 🧪 Run Wind Experiments

To simulate atmospheric conditions (without UI), run the `WindExperiments` class from your IDE or CLI.

---

## 🕹 Controls

- `Spacebar`: Start/Pause simulation
- `Scroll / Trackpad`: Zoom in/out
- `Mouse drag`: Move through space
- Buttons:
  - `Center on...`: Follow objects
  - `Mission Log` / `Engine Log`: View details

---

## 📸 Screenshots

### 🚀 Full Solar System View
![Solar System](screenshots/Solar_system_GUI.png)

### 🪐 Approaching Titan
![Approach](screenshots/mission_and_engine_log.png)

### ✅ Successful Landing
![Landing](screenshots/Landing_GUI.png)

---

## 📄 Documentation

Full API reference available in the Javadoc.  
👉 Open [`docs/index.html`](docs/index.html) manually in your browser if VS Code cannot preview it.

---

## 🧑‍💻 Author & Use Case

This project was built as part of a university simulation course and showcases advanced skills in physics modeling, UI development, and software design.  
It demonstrates my ability to:
- Design modular, testable code
- Apply numerical methods for solving differential equations
- Build and document full-stack Java applications

---

## 📘 Final Report

For the full academic write-up of the mission design, solvers, and experiments, see [TitanMission_FinalReport.pdf](docs/TitanMission_FinalReport.pdf).

---

## 👨‍🚀 Credits

Built by:
Emre Pelzer
Mikolaj Gawrys
Weronika Gorak
Leo Ebeling
Martin Popov
Yuri Manna
Alejandro Ibarrola
(30.05.2023)  
Background image from: https://www.pixel4k.com/dark-milky-way-galaxy-4k-74663.html (© not our original work)

---

## 📜 License

This project is open source under the MIT License.
