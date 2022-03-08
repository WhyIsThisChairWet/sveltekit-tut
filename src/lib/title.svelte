<script>
  export let title = "Ninja Gaming";
</script>

<div class="title">
  <img src="/controller.svg" alt="site logo" />
  <h1>{title}</h1>
</div>

<style>
  .title {
    display: flex;
  }
  .title img {
    display: inline-block;
    filter: invert(90%) sepia(38%) saturate(7481%) hue-rotate(35deg)
      brightness(89%) contrast(91%);
  }
  .title h1 {
    margin-left: 1rem;
    text-align: center;
  }
</style>
