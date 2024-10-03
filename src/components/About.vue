<template>
  <div class="About">
    <h1>{{ title }}</h1>
    <nav>
      <ul>
        <li><a href="#mission">Our Mission</a></li>
        <li><a href="#team">Our Team</a></li>
        <li><a href="#story">Our Story</a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'About',
  data() {
    return {
      title: 'About'
    };
  }
};
</script>

<style scoped>
.About {
  text-align: center;
  padding: 50px;
  background-color: #f0f4f8; /* Soft background color */
}

h1 {
  font-size: 2.5em;
  color: #333;
  margin-bottom: 20px;
}

nav ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
  display: inline-flex;
  gap: 20px;
}

nav ul li {
  font-size: 1.2em;
}

nav ul li a {
  text-decoration: none;
  color: #555;
  padding: 10px 15px;
  border-radius: 5px;
  transition: all 0.3s ease;
}

nav ul li a:hover {
  background-color: #e0e7ff; /* Subtle hover background */
  color: #000;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

</style>
