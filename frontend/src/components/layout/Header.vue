<template>
  <header class="header">
    <div class="logo">
      SMRN
    </div>

    <nav>
      <router-link to="/login">Login</router-link>
      <router-link to="/Register">Register</router-link>

    </nav>
  </header>
</template>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 20px;
  background: #1e1e2f;
}

.logo {
  color: white;
  font-size: 22px;
  font-weight: bold;
  letter-spacing: 1px;
}

nav {
  display: flex;
  gap: 25px;
}

a {
  color: #ccc;
  text-decoration: none;   /* remove underline */
  padding: 8px 14px;
  border-radius: 6px;
  transition: all 0.3s ease;
}

/* Hover effect */
a:hover {
  background: #2d2d44;
  color: white;
}

/* Active page style */
a.router-link-active {
  background: #4f46e5;
  color: white;
}
</style>
