<template>
  <div class="home">
    <h3>Home</h3>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Deserunt harum
      hic doloribus quos ratione, culpa placeat doloremque tenetur blanditiis
      labore quam commodi molestiae libero animi ipsa dolorum vero illo
      reprehenderit.
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem saepe
      minima dolorem sed totam voluptates molestiae nulla eum laborum quasi?
      Totam possimus aliquid repellendus temporibus eius illum quaerat officiis
      veniam.
    </p>
  </div>
</template>

<script>
export default {
  name: "Home",
  data() {
    return {};
  }
};
</script>

<style scoped>
.home {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-content: left;
}
h3 {
  color: rgb(200, 91, 23);
}
p {
  color: darkgreen;
}
</style>
