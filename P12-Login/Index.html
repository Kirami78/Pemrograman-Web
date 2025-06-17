<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Login Sederhana - LocalStorage</title>

</head>
<body>

<div class="login-box" id="loginBox">
  <h2>Login</h2>
  <form id="loginForm">
    <label>Username:
      <input type="text" id="username" required>
    </label>
    <label>Password:
      <input type="password" id="password" required>
    </label>
    <button type="submit">Login</button>
  </form>
</div>

<div class="login-box" id="welcomeBox" style="display: none;">
  <h2 id="welcome">Halo, User!</h2>
  <button onclick="logout()">Logout</button>
</div>

<script>
  // Simulasi user login (hardcoded)
  const users = {
    admin: '12345',
    user: 'pass'
  };

  // Cek apakah user sudah login
  function checkLogin() {
    const session = localStorage.getItem('sessionUser');
    if (session) {
      document.getElementById('loginBox').style.display = 'none';
      document.getElementById('welcomeBox').style.display = 'block';
      document.getElementById('welcome').innerText = `Halo, ${session}!`;
    }
  }

  // Tangani login
  document.getElementById('loginForm').addEventListener('submit', function(e) {
    e.preventDefault();
    const uname = document.getElementById('username').value.trim();
    const pass = document.getElementById('password').value.trim();

    if (users[uname] && users[uname] === pass) {
      localStorage.setItem('sessionUser', uname);
      checkLogin();
    } else {
      alert('Username atau password salah!');
    }
  });

  // Logout
  function logout() {
    localStorage.removeItem('sessionUser');
    location.reload();
  }

  // Jalankan saat pertama dimuat
  checkLogin();
</script>

</body>
</html>
