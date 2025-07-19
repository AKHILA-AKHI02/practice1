<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>User Home</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f9f9f9;
    }
    header {
      background-color: #007bff;
      color: white;
      padding: 1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav {
      display: flex;
      gap: 0.5rem;
      align-items: center;
    }
    nav button {
      background: transparent;
      border: none;
      color: white;
      font-size: 0.85rem;
      cursor: pointer;
      padding: 0.3rem 0.6rem;
      border-radius: 4px;
      transition: background-color 0.3s ease;
    }
    nav button:hover {
      background-color: rgba(255, 255, 255, 0.2);
    }
    #logoutBtn {
      background-color: #dc3545;
      border: none;
      padding: 0.3rem 0.6rem;
      border-radius: 4px;
      cursor: pointer;
      font-size: 0.85rem;
      color: white;
      transition: background-color 0.3s ease;
    }
    #logoutBtn:hover {
      background-color: #c82333;
    }
    main {
      padding: 2rem;
      text-align: center;
    }
    /* New class for promo images to unify size */
    .promo-image {
      max-width: 300px;
      border-radius: 8px;
      height: auto;
      object-fit: cover;
    }
    </style>
    <style>
      .dynamic-image {
        max-width: 600px;
        height: auto;
        margin-bottom: 0.3rem;
        border-radius: 4px;
      }
      .dynamic-button {
        margin-top: 0.3rem;
        padding: 0.2rem 0.4rem;
        border-radius: 4px;
        border: none;
        background-color: #007bff;
        color: white;
        cursor: pointer;
        font-size: 0.75rem;
      }
    </style>
    <style>
      .dynamic-image {
        max-width: 600px;
        height: auto;
        margin-bottom: 0.3rem;
        border-radius: 4px;
      }
      .dynamic-button {
        margin-top: 0.3rem;
        padding: 0.2rem 0.4rem;
        border-radius: 4px;
        border: none;
        background-color: #007bff;
        color: white;
        cursor: pointer;
        font-size: 0.75rem;
      }
    </style>
    <style>
      .dynamic-image {
        max-width: 600px;
        height: auto;
        margin-bottom: 0.3rem;
        border-radius: 4px;
        display: block;
        margin-left: auto;
        margin-right: auto;
      }
      .dynamic-button {
        margin-top: 0.3rem;
        padding: 0.3rem 0.6rem;
        border-radius: 4px;
        border: none;
        background-color: #007bff;
        color: white;
        cursor: pointer;
        font-size: 0.85rem;
        display: block;
        margin-left: auto;
        margin-right: auto;
      }
    </style>
</head>
<body>
  <video autoplay muted loop id="background-video" style="position: fixed; right: 0; bottom: 0; min-width: 100%; min-height: 100%; object-fit: cover; z-index: -1;">
    <source src="https://videos.pexels.com/video-files/853800/853800-sd_640_360_25fps.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <header style="display: flex; justify-content: space-between; align-items: center; padding: 1rem; background-color: #007bff; color: white;">
    <div id="welcomeMessage" style="font-weight: bold;">Welcome to ZUDIO</div>
    <div style="display: flex; gap: 0.5rem; align-items: center;">
      <button id="cartBtn" style="background-color: #ffc107; color: black; border-radius: 4px; padding: 0.3rem 0.6rem; border: none; cursor: pointer; font-size: 0.85rem;">Cart</button>
      <button id="logoutBtn" style="background-color: #dc3545; border: none; padding: 0.3rem 0.6rem; border-radius: 4px; cursor: pointer; font-size: 0.85rem; color: white;">Logout</button>
    </div>
  </header>

    <script>
      document.getElementById('cartBtn').addEventListener('click', () => {
        window.location.href = 'cart.html';
      });

      // Removed event listeners for header category buttons as they are removed from header
      document.addEventListener('DOMContentLoaded', () => {
        // Add event listeners for promo section buttons
        document.getElementById('promoMensWearBtn').addEventListener('click', () => {
          window.location.href = 'mens_wear.html';
        });
        document.getElementById('promoWomensWearBtn').addEventListener('click', () => {
          window.location.href = 'womens_wear.html';
        });
        document.getElementById('promoKidsBoysBtn').addEventListener('click', () => {
          window.location.href = 'kidwear(boy).html';
        });
        document.getElementById('promoKidsGirlsBtn').addEventListener('click', () => {
          window.location.href = 'kidwear(girl).html';
        });
      });

      // Add event listeners for shoes and watches buttons
      document.getElementById('promoShoesBtn').addEventListener('click', () => {
        window.location.href = 'shoe_wear.html';
      });
      document.getElementById('promoWatchesBtn').addEventListener('click', () => {
        window.location.href = 'watch.html';
      });
    </script>
  <main>
    <h1>Welcome to ZUDIO</h1>
    <p>Select a category from the header above.</p>

      <section id="promoSection" style="margin-top: 3rem; padding: 2rem; border-radius: 8px; text-align: center;">
        <h2 style="font-weight: bold; color: #007bff; margin-bottom: 1rem;">Fashions</h2>
        <div style="display: flex; flex-direction: column; gap: 1rem; align-items: center;">
          <div style="text-align: center; width: 300px;">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcROUWQ-6Iwv9cTkGIXudQqRKWXlPLIg0r63Xw&s" alt="Promo 1" class="promo-image" style="width: 100%; height: 200px; object-fit: cover;" />
            <button id="promoMensWearBtn" style="margin-top: 0.5rem; padding: 0.3rem 0.6rem; border-radius: 4px; border: none; background-color: #007bff; color: white; cursor: pointer; font-size: 0.85rem;">Mens Wear</button>
          </div>
          <div style="text-align: center; width: 300px;">
            <img src="https://imgeng.jagran.com/images/2024/11/06/article/image/mehreen-pirzada-ethnic-outfits-1730890482702_v.webp" alt="Promo 2" class="promo-image" style="width: 100%; height: 200px; object-fit: cover;" />
            <button id="promoWomensWearBtn" style="margin-top: 0.5rem; padding: 0.3rem 0.6rem; border-radius: 4px; border: none; background-color: #007bff; color: white; cursor: pointer; font-size: 0.85rem;">Womens Wear</button>
          </div>
          <div style="text-align: center; width: 300px;">
            <img src="img.png" alt="Promo 3" class="promo-image" style="width: 100%; height: 200px; object-fit: cover;" />
            <button id="promoKidsBoysBtn" style="margin-top: 0.5rem; padding: 0.3rem 0.6rem; border-radius: 4px; border: none; background-color: #007bff; color: white; cursor: pointer; font-size: 0.85rem;">Kids Wear (Boys)</button>
          </div>
          <div style="text-align: center; width: 300px;">
            <img src="image.png"  alt="promo 4" class="promo-image" style="width: 100%; height: 200px; object-fit: cover;" />
            <button id="promoKidsGirlsBtn" style="margin-top: 0.5rem; padding: 0.3rem 0.6rem; border-radius: 4px; border: none; background-color: #007bff; color: white; cursor: pointer; font-size: 0.85rem;">Kids Wear (Girls)</button>
          </div>
  </main>

  <!-- Firebase App (the core Firebase SDK) -->
  <script src="https://www.gstatic.com/firebasejs/9.22.1/firebase-app-compat.js"></script>
  <!-- Firebase Authentication -->
  <script src="https://www.gstatic.com/firebasejs/9.22.1/firebase-auth-compat.js"></script>

  <script>
    const firebaseConfig = {
  apiKey: "AIzaSyBiGco-t0d1Iej2yaVKYMU_73hBcWBILrE",
  authDomain: "game-c8057.firebaseapp.com",
  databaseURL: "https://game-c8057-default-rtdb.firebaseio.com",
  projectId: "game-c8057",
  storageBucket: "game-c8057.firebasestorage.app",
  messagingSenderId: "482964467564",
  appId: "1:482964467564:web:0cd8925807fe3ac5200d49",
  measurementId: "G-Z0RZCLXSR6"
};
    // Initialize Firebase
    firebase.initializeApp(firebaseConfig);
    const auth = firebase.auth();

    // Redirect to login if not logged in and show welcome message
    auth.onAuthStateChanged(user => {
      if (!user) {
        window.location.href = 'signup.html';
      } else {
        const welcomeMessage = document.getElementById('welcomeMessage');
        welcomeMessage.textContent = `Hello, ${user.displayName || user.email}!`;
      }
    });

    // Button click handlers
    document.getElementById('mensWearBtn').addEventListener('click', () => {
      window.location.href = 'mens_wear.html';
    });
    document.getElementById('womensWearBtn').addEventListener('click', () => {
      window.location.href = 'womens_wear.html';
    });
    document.getElementById('kidsBoysBtn').addEventListener('click', () => {
      window.location.href = 'kidwear(boy).html';
    });
    document.getElementById('kidsGirlsBtn').addEventListener('click', () => {
      window.location.href = 'kidwear(girl).html';
    });

      // Logout button handler - direct inline onclick attribute for guaranteed navigation
      const logoutBtn = document.getElementById('logoutBtn');
      if (logoutBtn) {
        logoutBtn.onclick = function() {
          window.location.href = 'logout.html';
        };
      }
  </script>
  <script>
    const database = firebase.database();

    function createItemElement(item) {
      const itemDiv = document.createElement('div');
      itemDiv.className = 'item';
      itemDiv.innerHTML = `
        <h3>${item.name}</h3>
        <p>${item.description}</p>
        ${item.imageUrl ? `<img src="${item.imageUrl}" alt="${item.name}" style="max-width:100%; height:auto; margin-bottom: 0.5rem; border-radius: 4px; display: block; margin-left: auto; margin-right: auto;" />` : ''}
        <p class="price">$${item.price.toFixed(2)}</p>
      `;
      return itemDiv;
    }

    function displayItems(refPath, containerId) {
      const container = document.getElementById(containerId);
      database.ref(refPath).on('value', (snapshot) => {
        const data = snapshot.val();
        container.innerHTML = '';
        if (!data) {
          container.innerHTML = '<p>No items found.</p>';
          return;
        }
        Object.keys(data).forEach(key => {
          const item = data[key];
          const itemElement = createItemElement(item);
          container.appendChild(itemElement);
          // Add button under each item image
          const button = document.createElement('button');
          button.textContent = 'View Item';
          button.className = 'dynamic-button';
          // Append button after the itemElement content to ensure it is under the image
          itemElement.appendChild(button);
        });
      });
    }

    displayItems('mens_wear', 'mensItems');
    displayItems('womens_wear', 'womensItems');
    displayItems('kidwear_boy', 'kidsBoysItems');
    displayItems('kidwear_girl', 'kidsGirlsItems');
  </script>
</body>
</html>
