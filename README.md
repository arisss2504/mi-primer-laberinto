## ✨ _HOLAA SOY ARISS_ ✨

**🎉 _ESTUDIANTE DE PROGRAMACION_ 🎉**

¡¡ Welcome to my GitHub profile!!

---

Hi! Today I’m going to explain how I made my first maze

¡¡ IN THREE DIFFERENT SCENARIOS !!

---

The first scenario is this:
<img width="921" height="445" alt="image" src="https://github.com/user-attachments/assets/a4f2df87-b8f0-412a-974d-2378543bc30d" />

### 🎯 Game Objective

Move the **pink ball** from the upper left corner to the **treasure chest** located in the lower right corner, avoiding the obstacles (black walls) along the way.



### ⚙️ Mechanics and Operation

1. **Motion Control (Physics/Tilt):**
* The ball's movement is not controlled with buttons, but rather using the phone's **accelerometer**.

* By tilting the phone in any direction, the sensor detects the changes in orientation and moves the ball proportionally.


2. **Collision Detection:**
* **With walls (`bar_1` to `bar_7`):** If the ball touches a wall, it can bounce or restart from its starting position to make the journey more challenging.

* **With the chest:** Upon reaching the goal, a notification (`Notifier1`) is activated, congratulating the player on winning.

3. **Reset Button (`btnreset`):**
* Allows you to restart the game at any time, returning the ball to its starting point.



### 🧱 Key Components in MIT App Inventor

* **`Canvas1`:** The graphical surface on which the ball, walls, and chest interact.

* **`Ball1`:** The main element of the player that moves across the screen.

* * **`bar_1` to `bar_7` (Barriers/Walls):** Image sprites or lines that make up the maze circuit.

* **`AccelerometerSensor1` (Accelerometer Sensor):** Captures the device's tilt to assign speed and direction to `Ball1`.

* **`btnreset` (Button):** Resets the game to its original state.

* **`Notifier1` (Notifier):** Displays on-screen alerts (for example: *"Congratulations, you won!"*).

---
