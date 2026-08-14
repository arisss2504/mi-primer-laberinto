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

THE SECOND SCENARIO IS THIS:
<img width="921" height="445" alt="image" src="https://github.com/user-attachments/assets/0b41da22-68c9-42ce-a4fd-899c7f2c2de5" />

### 🎯 Game Objective

Move the **pink ball** (`Ball1`) from the top left corner to the goal represented by the **treasure chest** (`chest`), navigating the new arrangement of vertical and horizontal barriers.

### ⚙️ Mechanics and Operation of this Stage

1. **Tilt Navigation:**
* The **`AccelerometerSensor1`** sensor detects the angle and tilt of the smartphone on the $X$ and $Y$ axes, translating this into continuous movement of the ball.

2. **New Route and Corridor Design:**
* The wall structure creates a new route: it features a **central right horizontal barrier** (`bar_7`), stepped upper walls, and a cross intersection in the lower left area.

* If the ball collides with any of the barriers (`bar_1`, `bar_2`, `bar_3`, `bar_6`, `bar_7`), the collision is handled (stopping the ball's movement, causing it to bounce, or returning the player to the starting point).

3. **Victory and Reset Conditions:**
* **Victory:** Upon contact between `Ball1` and `chest`, the **`Notifier1`** displays a congratulatory pop-up message.

* **Reset:** The **`btnreset`** button located at the top allows you to reset the ball's coordinates to their initial $(x, y)$.

### 🧱 Specific Stage Components

* **`Canvas1`:** The interactive drawing canvas on which all game elements are positioned.

* **`Ball1`:** The pink ball controlled by the user.

* * **Maze Barriers (`bar_1` to `bar_7`):** Image sprites (`ImageSprite`) generated from the uploaded resources:
* `Lineahor...al(1).jpg` (Horizontal Barrier)
* `LineaVertical(1).jpg` (Vertical Barrier)

* **`chest`:** Target object located in the lower right corner (`chest(1).jpg`).

* **`AccelerometerSensor1`:** Sensor that reads the device's physical movement.

* **`Notifier1`:** Invisible component responsible for sending on-screen notifications.

* **`btnreiniciar`:** Button to restart the game.

---






