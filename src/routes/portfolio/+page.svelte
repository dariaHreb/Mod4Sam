<script>
  import photo1 from "$lib/images/photo1.jpg";
  import photo2 from "$lib/images/photo2.jpg";
  import photo3 from "$lib/images/photo3.jpg";
  import photo4 from "$lib/images/photo4.jpg";
  import photo5 from "$lib/images/photo5.jpg";
  import photo6 from "$lib/images/photo6.jpg";
</script>

<div class="container">
  <img alt="фото котика 1" src={photo1} width="400" />
  <br />
  <img alt="фото котика 2" src={photo2} width="400" />
  <br />
  <img alt="фото котика 3" src={photo3} width="400" />
  <br />
  <img alt="фото котика 4" src={photo4} width="400" />
  <br />
  <img alt="фото котика 5" src={photo5} width="400" />
  <br />
  <img alt="фото котика 6" src={photo6} width="400" />
</div>

<style>
  .container {
    margin: 50px auto;
    max-width: 800px;
    padding: 0 20px;
  }
</style>
