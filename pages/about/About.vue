<template>
  <div class="container">
    about1111111
  </div>
</template>

<script setup>
</script>

<style scoped>
.container {
  font-family: 'Arial, sans-serif';
  color: #fff;
  background-color: #1a1a1a;
  padding: 20px;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 0;
  flex-wrap: wrap;
}

.logo {
  font-size: 1.2em;
  font-weight: bold;
}

.nav {
  display: flex;
  gap: 15px;
  flex-wrap: wrap;
}

.nav a {
  color: #fff;
  text-decoration: none;
}

.consult-btn {
  background-color: #3b82f6;
  border: none;
  padding: 10px 20px;
  color: white;
  cursor: pointer;
  border-radius: 5px;
  margin-top: 10px;
}

.main-content {
  display: flex;
  justify-content: space-between;
  margin-top: 20px;
  flex-wrap: wrap;
}

.intro {
  max-width: 60%;
  min-width: 300px;
}

.intro h1 {
  font-size: 2.5em;
  color: #3b82f6;
}

.intro p {
  font-size: 1.2em;
  margin-top: 10px;
}

.telegram-btn {
  background-color: #3b82f6;
  border: none;
  padding: 10px 20px;
  color: white;
  cursor: pointer;
  border-radius: 5px;
  margin-top: 20px;
}

.image-section {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 20px;
}

.profile-image {
  width: 450px;
  border-radius: 10px;
}

.caption {
  margin-top: 10px;
  font-size: 1em;
  text-align: center;
}

.services {
  display: flex;
  justify-content: space-between;
  margin-top: 30px;
  flex-wrap: wrap;
}

.service {
  background-color: #333;
  padding: 20px;
  border-radius: 10px;
  flex: 1;
  margin: 10px;
  min-width: 200px;
}

.service p {
  margin: 0;
  font-size: 1.1em;
}

/* Media Queries for responsiveness */
@media (max-width: 768px) {
  .main-content {
    flex-direction: column;
  }

  .intro {
    max-width: 100%;
    text-align: center;
  }

  .telegram-btn {
    margin-left: auto;
    margin-right: auto;
  }

  .image-section {
    margin-top: 20px;
  }
}

@media (max-width: 480px) {
  .intro h1 {
    font-size: 2em;
  }

  .intro p {
    font-size: 1em;
  }

  .consult-btn, .telegram-btn {
    width: 100%;
  }

  .service {
    flex: 1 1 100%;
  }
}
</style>
