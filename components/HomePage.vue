<template>
  <div class="home">
    <img
      src="https://res.cloudinary.com/echsd/image/upload/v1589721564/Do_ngv0eo.jpg"
      width="190"
      height="190"
      class="mt-2 mb-3 rounded-circle hover"
    />
    <h1 class="m-2 text-secondary font-weight-bolder">Nguyen Thanh Do</h1>
    <h5 class="mb-5 text-black-50 font-weight-normal">
      Full-stack Web Developer
    </h5>
    <div class="contact mt-100">
      <a href="https://www.facebook.com/ntdo2506/" class="link ">
        <Tooltip arrow title="fb.com/ntdo2506" class="text-info">
          <FacebookIcon fontSize="large" />
        </Tooltip>
      </a>
      <a href="https://github.com/taythaytu0905" class="icon link  ml-5">
        <Tooltip arrow title="github.com/taythaytu0905" class="text-info">
          <GitHubIcon fontSize="large" />
        </Tooltip>
      </a>
      <a href="mailto:ntdo.13cdt1@gmail.com" class="link  ml-5">
        <Tooltip
          arrow
          title="ntdo.13cdt1@gmail.com"
          placement="bottom"
          class="text-info"
        >
          <EmailIcon fontSize="large" />
        </Tooltip>
      </a>
      <div class="mt-5">
        <ul>
          <li>
            <nuxt-link to="/blog">Blog</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/about">About</nuxt-link>
          </li>
        </ul>
      </div>
    </div>
    <footer>
      <hr class="mt-5"/>
      <div class="text-black-50">
        <p>Copyright © Thanh Do 2020</p>
        <p>Design parameters: Language(Javascript) - Framework(React)</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "HomePage"
}
</script>

<style scoped>
.home {
  text-align: center;
  margin-top: 100px;
}

.home .hover:hover {
  opacity: 0.6;
  transform: scale(1.05);
  transition: width 1s, height 2s;
}
</style>
