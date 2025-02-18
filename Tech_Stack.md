# ⏰ Technologies Used

### 1️⃣ **HTML** - Structure & Elements  
- **`<div class="clock">`** → The main container for the clock.  
- **`<div class="numbers">`** → Holds the **12, 3, 6, 9** numbers.  
- **`<div class="arrows">`** → Contains the moving hands (hour, minute, second).  
- **`<script src="cl.js"></script>`** → Links the JavaScript file for dynamic updates.  

### 2️⃣ **CSS** - Styling & Layout  
- **`background-color: steelblue;`** → Sets the background color of the page.  
- **`.clock`** → Defines the circular clock structure with borders and shadows.  
- **`.numbers div`** → Positions the numbers **(12, 3, 6, 9)** at correct angles.  
- **`.arrows::before`** → Creates the central pivot point of the clock hands.  
- **`.hour`, `.minute`, `.second`** → Uses **`transform: rotate()`** for real-time movement.  

### 3️⃣ **JavaScript** - Functionality  
- **`new Date()`** → Fetches the **current time** from the system.  
- **`setInterval(setDate, 1000);`** → Updates the clock **every second**.  
- **`style.transform = rotate(degrees)`** → Rotates clock hands dynamically.  
- **Mathematical calculations:**  
  - `getSeconds() / 60 * 360` → Converts seconds into **degrees**.  
  - `getMinutes() / 60 * 360` → Converts minutes into **degrees**.  
  - `getHours() % 12 / 12 * 360` → Converts hours into **degrees** (12-hour format).  

---

## 🎯 Key Concepts Learned  

✅ **CSS Transformations** - Using `rotate()` for smooth animations  
✅ **JavaScript Date API** - Fetching & manipulating real-time clock data  
✅ **Positioning in CSS** - Absolute positioning for clock hands & numbers  
✅ **Dynamic Styling** - Changing CSS styles dynamically via JavaScript  

---

📌 *This project is beginner-friendly and can be enhanced with additional features like themes or a digital clock overlay.*  
