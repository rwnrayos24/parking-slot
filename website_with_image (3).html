<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Smart Parking & User Monitoring System</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      text-align: center;
      background-color: #f4f4f9;
    }
    header {
      background: #2c3e50;
      color: white;
      padding: 15px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 22px;
    }
    #datetime {
      font-size: 16px;
      font-weight: bold;
    }
    .image-container {
      margin: 20px auto;
      max-width: 90%;
    }
    .image-container img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
    .slots, .users {
      margin: 20px auto;
      max-width: 600px;
      text-align: left;
    }
    .slot, .user {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px;
      margin: 5px 0;
      border-radius: 8px;
      background: #ecf0f1;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .available {
      color: green;
      font-weight: bold;
    }
    .occupied {
      color: red;
      font-weight: bold;
    }
    .active {
      color: green;
      font-weight: bold;
    }
    .inactive {
      color: gray;
      font-weight: bold;
    }
    .admin {
      background: #dff9fb;
    }
    .logs {
      font-size: 13px;
      color: #555;
      margin-left: 10px;
      flex: 1;
      text-align: left;
    }
  </style>
</head>
<body>
  <header>
    <h1>Smart Parking & User Monitoring System</h1>
    <div id="datetime"></div>
  </header>

  <div class="image-container">
    <img src="552222581_782518974753018_5440383913470254334_n.png" alt="Parking Lot View 1">
  </div>
  <div class="image-container">
    <img src="552543116_2272753579849996_8489431576083383228_n.png" alt="Parking Lot View 2">
  </div>
  <div class="image-container">
    <img src="552360883_1332359335196636_6132304847752890405_n.png" alt="Parking Lot View 3">
  </div>

  <section class="slots">
    <h2>Parking Slot Status</h2>
    <div id="slotList"></div>
  </section>

  <section class="users">
    <h2>User Monitoring</h2>
    <div id="userList"></div>
  </section>

  <script>
    // Live Date and Time
    function updateDateTime() {
      const now = new Date();
      document.getElementById('datetime').textContent = now.toLocaleString();
    }
    setInterval(updateDateTime, 1000);
    updateDateTime();

    // Example Slot Data
    const slots = [
      { id: 'A1', status: 'available' },
      { id: 'A2', status: 'occupied' },
      { id: 'B1', status: 'available' },
      { id: 'B2', status: 'occupied' },
      { id: 'C1', status: 'available' },
      { id: 'C2', status: 'occupied' },
    ];
    function loadSlots() {
      const slotList = document.getElementById('slotList');
      slotList.innerHTML = '';
      slots.forEach(slot => {
        const div = document.createElement('div');
        div.className = 'slot';
        div.innerHTML = `<span>Slot ${slot.id}</span> <span class="${slot.status}">${slot.status.toUpperCase()}</span>`;
        slotList.appendChild(div);
      });
    }
    loadSlots();

    // Example User Data (Simulated)
    const users = [
      { username: "admin1", role: "admin", status: "active", logs: ["Logged in", "Viewed slots", "Changed slot A2 to occupied"] },
      { username: "userA",  role: "user", status: "active", logs: ["Logged in", "Viewed slots"] },
      { username: "userB",  role: "user", status: "inactive", logs: ["Logged out"] },
      { username: "manager",role: "admin", status: "active", logs: ["Logged in", "Viewed user activity"] },
      { username: "staffX", role: "user", status: "active", logs: ["Logged in", "Viewed slots", "Logged out"] }
    ];
    function loadUsers() {
      const userList = document.getElementById('userList');
      userList.innerHTML = '';
      users.forEach(user => {
        const div = document.createElement('div');
        div.className = 'user' + (user.role === 'admin' ? ' admin' : '');
        div.innerHTML = `<span>${user.username} (${user.role})</span>
          <span class="${user.status}">${user.status.toUpperCase()}</span>
          <span class="logs">${user.logs.join(", ")}</span>`;
        userList.appendChild(div);
      });
    }
    loadUsers();
  </script>
</body>
</html>
