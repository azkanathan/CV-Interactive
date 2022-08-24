<template>
  <div class="card  shadow mb-1 bg-body rounded">
    <h1>Skills</h1>
    <div class="container">
      <h4>HTML</h4>
      <div class="progress">
        <div class="progress-bar bg-warning" role="progressbar" aria-label="Success example" style="width: 85%"
          aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">85%</div>
      </div>
      <h4>CSS</h4>
      <div class="progress">
        <div class="progress-bar bg-info" role="progressbar" aria-label="Info example" style="width: 95%" aria-valuenow="50"
          aria-valuemin="0" aria-valuemax="100">95%</div>
      </div>
      <h4>Laravel</h4>
      <div class="progress">
        <div class="progress-bar bg-danger" role="progressbar" aria-label="Warning example" style="width: 80%"
          aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">80%</div>
      </div>
      <h4>Figma Design</h4> 
      <div class="progress">
        <div class="progress-bar bg-secondary" role="progressbar" aria-label="Danger example" style="width: 80%"
          aria-valuenow="100" aria-valuemin="0" aria-valuemax="100">80%</div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .card {
  margin-top: 30px;
  min-height: 50vh;
  display: flex;
  align-items: center;
  width: 100%;
  border: none;
  }
  h4 {
    margin: 0;
    padding: 0;
    top: 20px;
  }

  .container {
    width: 100%;
    margin-top: 20px;
    margin-bottom: 20px;
    }

  .container .progress {
    margin-top: 20px;
    height: 35px;
    /* background-color: blueviolet; */
  }
</style>