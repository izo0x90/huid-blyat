# HUID BLYAT! 💥

> **The Tsoding Collision Collider** — A retro 80s canvas terminal game about generating HUID collisions and avoiding catastrophic traps.

Inspired by [Tsoding](https://youtube.com/@Tsoding)'s concept of **HUID** (*Human-Understandable ID*), derived from the current timestamp down to the second. In an interactive approval stream, if you mash `[Y]` fast enough within the exact same second... **collisions happen!**

In this game, collisions aren't bugs — they're **features**. Mash `[Y]` as fast as possible within each second window to rack up massive collision multipliers, but beware of devious traps that will reset your score all the way back to zero!

---

## 🕹️ Gameplay Mechanics

1. **Approval Prompts**:
   * Valid low-level programming tasks stream in (`da_append(&da, item)`, `nob_cmd_run_sync(&cmd)`, debugging missing semicolons, etc.).
   * Mash `[Y]`, `[Space]`, or click **`[ Y: APPROVE & COLLIDE ]`** as fast as you can.
2. **HUID Collisions**:
   * The 1st press in a second creates the ID.
   * Every subsequent press in that **exact same second** generates a **Collision**!
   * Collisions earn exponential points, spawn Mario coins, trigger casino dings, and build **Point Velocity**.
3. **Chaining & Multipliers**:
   * Chaining multi-collision seconds across consecutive seconds builds your multiplier up to **10x**!
   * Pausing or slowing down cools off your velocity.
4. **Hazard Traps (`[N]` Required!)**:
   * Devious prompts appear randomly (e.g., *Rewrite in Java Spring Boot?*, *rm -rf / --no-preserve-root*, *Switch to CMake 3.28?*, *Add 4,200 npm packages?*).
   * You **must press `[N]`** to reject and defuse the trap for bonus points.
   * Blindly mashing `[Y]` on a trap triggers **CATASTROPHIC FAILURE: Score resets to 0!**
5. **Dynamic Lemmings & Reactive Tsoding Mascot**:
   * Tiny pixel lemmings walk along terminal code lines and tumble with gravity when screen-shakes occur.
   * Tsoding's procedural avatar reacts dynamically: smug grins on combos, screaming *"BLYAT!"* on rapid collisions, flaming hair during overdrive, and tears on score wipes.
6. **Top 10 Hall of Fame**:
   * Local high scores are automatically preserved in `localStorage`. Press **`[H]`** or click **`[ H: TOP 10 ]`** anytime to view the Hall of Fame.
   * Press **`[C]`** to copy a bragging snippet to share with friends!

---

## ⌨️ Controls

| Action | Keyboard | Touch / Mouse |
| :--- | :--- | :--- |
| **Approve / Collide** | `Y`, `Space`, or `Enter` | Click `[ Y: APPROVE & COLLIDE ]` or tap screen |
| **Reject Trap** | `N`, `Backspace`, or `Escape` | Click `[ N: REJECT TRAP ]` |
| **Toggle Hall of Fame** | `H` or `Tab` | Click `[ H: TOP 10 ]` |
| **Toggle Audio** | `M` | Click `[ M: AUDIO ]` |
| **Copy Score Brag** | `C` | Click on Hall of Fame footer |

---

## 🚀 Hosting on GitHub Pages

1. Commit and push to your GitHub repository:
   ```bash
   git add .
   git commit -m "feat: initial release of HUID BLYAT game"
   git push -u origin main
   ```
2. In your repository on GitHub:
   * Go to **Settings** > **Pages**.
   * Under **Build and deployment** > **Source**, select **Deploy from a branch**.
   * Select branch `main` and folder `/ (root)`.
   * Click **Save**.
3. Your game is live at `https://<username>.github.io/huid-blyat/`!

---

*Pure Canvas & Web Audio API. Zero external dependencies.*
