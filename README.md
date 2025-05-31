# UI-UX-Design-Task-2
COMPANY : CODTECH IT SOLUTIONS
NAME : KATARU USHASREE 
INTERN ID : CT08DM303 
DOMAIN : UI/UX DESIGN 
DURATION : 8 WEEKS 
MENTOR : NEELA SANTHOSH 
DESCRIPTION:  In this task, I designed and developed a responsive landing page for a fictional coffee shop called Coffee Haven using HTML and CSS. The aim was to create a user-friendly and visually appealing interface that captures the cozy, handcrafted essence of a modern coffee brand.

🌟 Key Features Implemented:
Header Section:
          Includes the brand title Coffee Haven.
Navigation links: 
         Home, Menu, About, Contact.
Bottom Navigation Bar (Mobile-Friendly):
         Fixed at the bottom with four options: Home, Search, Cart, Profile.Enhances mobile user experience and ease of navigation.
         
🎨 Design Aesthetics:
         Theme Colors: 
                   Deep coffee tones like dark brown (#3e2723), medium brown (#6d4c41), and soft caramel (#ffe0b2).
         Font: 
                   Clean and modern Segoe UI for easy readability.
         Layout:  
                   Flexbox-based responsive layout for adaptability on all screen sizes.Rounded buttons and cards to give a friendly and smooth user interface.
                   
📱 Responsiveness:
               Fully mobile responsive using media queries.Layout shifts gracefully on smaller screens.Button sizes and text scale appropriately for accessibility.
               
🧠 Skills Demonstrated:
               HTML5 and CSS3 proficiency.UI/UX design thinking.Responsive layout using Flexbox and media queries.Color theory and typography for branding.

CODE using HTML / CSS :

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Coffee Shop</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
     
body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #4e342e;
      color: #fff;
    }

header {
      background-color: #3e2723;
      padding: 20px;
      text-align: center;
      position: relative;
    }

header h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin-top: 10px;
    }

nav a {
      color: #ffe0b2;
      text-decoration: none;
      font-weight: bold;
    }

.login-btn {
      position: absolute;
      top: 20px;
      right: 20px;
      background-color: #8d6e63;
      color: white;
      border: none;
      padding: 8px 16px;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
    }

.login-btn:hover {
      background-color: #a1887f;
    }

.hero {
      text-align: center;
      padding: 60px 20px;
      background: #6d4c41;
    }

.hero h2 {
      font-size: 2em;
      margin-bottom: 10px;
    }

.hero p {
      font-size: 1.1em;
    }

.menu {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      padding: 40px 20px;
    }

.menu-item {
      background-color: #5d4037;
      width: 280px;
      margin: 15px;
      padding: 20px;
      border-radius: 10px;
    }

.menu-item h3 {
      color: #ffe0b2;
      margin-bottom: 10px;
    }

footer {
      background-color: #3e2723;
      text-align: center;
      padding: 20px;
      margin-bottom: 70px; /* Space for bottom nav */
    }

/* Bottom Navigation */
    .bottom-nav {
      position: fixed;
      bottom: 0;
      left: 0;
      right: 0;
      background-color: #3e2723;
      display: flex;
      justify-content: space-around;
      align-items: center;
      padding: 10px 0;
      border-top: 1px solid #795548;
    }

.bottom-nav button {
      background: none;
      border: none;
      color: #ffe0b2;
      font-size: 16px;
      cursor: pointer;
      text-align: center;
      flex: 1;
    }

.bottom-nav button:hover {
      color: #fff;
    }

@media (max-width: 600px) {
      header h1 {
        font-size: 1.8em;
      }

.hero h2 {
        font-size: 1.5em;
      }

.menu {
        flex-direction: column;
        align-items: center;
      }

.bottom-nav button {
        font-size: 14px;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>Coffee Haven</h1>
    <button class="login-btn">Login</button>
    <nav>
      <a href="#">Home</a>
      <a href="#">Menu</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to Coffee Haven</h2>
    <p>Your cozy escape for handcrafted coffee and warm pastries.</p>
  </section>

  <section class="menu">
    <div class="menu-item">
      <h3>Espresso</h3>
      <p>Strong and bold shot of espresso made from premium beans.</p>
    </div>
    <div class="menu-item">
      <h3>Latte</h3>
      <p>Smooth blend of espresso and steamed milk topped with foam.</p>
    </div>
    <div class="menu-item">
      <h3>Cappuccino</h3>
      <p>Rich espresso layered with steamed milk and thick foam.</p>
    </div>
    <div class="menu-item">
      <h3>Mocha</h3>
      <p>Chocolate-flavored coffee drink with espresso and steamed milk.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Coffee Haven. All rights reserved.</p>
  </footer>

  <div class="bottom-nav">
    <button>Home</button>
    <button>Search</button>
    <button>Cart</button>
    <button>Profile</button>
  </div>

</body>
</html>


Output : 
        ![Image](https://github.com/user-attachments/assets/d253151d-3e8d-41f8-a55c-602980cc55fe)
