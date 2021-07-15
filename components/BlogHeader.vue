<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <nuxt-link to="/" className="navbar-brand">
        <img
          src="https://res.cloudinary.com/echsd/image/upload/v1589721564/Do_ngv0eo.jpg"
          width="30"
          height="30"
          className="d-inline-block align-top rounded-circle mr-2"
          alt=""
        />
        Do-Blog
      </nuxt-link>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul>
          <li>
            <nuxt-link to="/">Home</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/about">About</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/blog">Blog</nuxt-link>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>
<script>
export default {
  name: 'AppHeader'
}
</script>
<style>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 1rem;
  padding-bottom: 1rem;
  border-bottom: 1px dotted #ccc;
}

.header .title {
  font-size: 3rem;
  color: #526488;
}

.header ul {
  display: flex;
}

.header a {
  display: inline-block;
  background: #333;
  color: #fff;
  padding: 0.3rem 1rem;
  margin-right: 0.5rem;
}
</style>
