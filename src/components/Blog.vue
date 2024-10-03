<template>
  <div class="Blog">
    <h1>{{ title }}</h1>
    <nav>
      <ul>
        <li><a href="#latest">Latest Posts</a></li>
        <li><a href="#categories">Categories</a></li>
        <li><a href="#archive">Archive</a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Blog',
  data() {
    return {
      title: 'Blog'
    };
  }
};
</script>

<style scoped>
.Blog {
  text-align: center;
  padding: 50px;
  background-color: #f0f4f8; /* Same soft background color as About */
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
  background-color: #e0e7ff; /* Soft hover effect with light blue */
  color: #000;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}
</style>
