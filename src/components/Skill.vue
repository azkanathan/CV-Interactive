<script setup>
  import WelcomeItem from './WelcomeItem.vue'
  import DocumentationIcon from './icons/IconDocumentation.vue'
  import ToolingIcon from './icons/IconTooling.vue'
  import EcosystemIcon from './icons/IconEcosystem.vue'
  import CommunityIcon from './icons/IconCommunity.vue'
  import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <div class="content">
    <div class="card shadow mb-1 bg-body rounded col-8">
      <h1 class="green">Experience</h1>
      <div class="greetings">
        <ul>
          <li>Mengerjakan Tugas Fullstack Developer</li>
          <li>Membuat Web Menggunakan WordPress</li>
          <li>Membuat Crud Laravel Menggunakan Template</li>
          <li>Membuat Website Template Menggunakan CSS Native</li>
          <li>Membuat Website Template Full Bootstrap</li>
          <li>Membuat Crud Laravel</li>
        </ul>
      </div>
    </div>

    <div class="card2 shadow mb-1 bg-body rounded col-4">
      <h1 class="green">Education</h1>
      <div class="greetings">
        <ul>
          <li>SDN Pondok Cina 1 - 2016/2017</li>
          <li>MTs Al Husna - 2019/2020</li>
          <li>SMK Taruna Bhakti - Now</li>
        </ul>
      </div>
    </div>
  </div>


  <div class="card3 shadow mb-1 bg-body rounded">
    <div class="email">
      <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" fill="currentColor" class="bi bi-envelope-fill" viewBox="0 0 16 16">
      <path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414.05 3.555ZM0 4.697v7.104l5.803-3.558L0 4.697ZM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586l-1.239-.757Zm3.436-.586L16 11.801V4.697l-5.803 3.546Z"/>
      </svg>
      <h5>darizkyfaz@gmail.com</h5>
    </div>
    <div class="telp">
      <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" fill="currentColor" class="bi bi-telephone-fill" viewBox="0 0 16 16">
      <path fill-rule="evenodd" d="M1.885.511a1.745 1.745 0 0 1 2.61.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.678.678 0 0 0 .178.643l2.457 2.457a.678.678 0 0 0 .644.178l2.189-.547a1.745 1.745 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.634 18.634 0 0 1-7.01-4.42 18.634 18.634 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877L1.885.511z"/>
      </svg>
      <h5>+62 87879450103</h5>
    </div>
    <div class="address">
      <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" fill="currentColor" class="bi bi-geo-alt-fill" viewBox="0 0 16 16">
      <path d="M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10zm0-7a3 3 0 1 1 0-6 3 3 0 0 1 0 6z"/>
      </svg>
      <h5>Margonda Depok, Jawa Barat</h5>
    </div>
  </div>
</template>

<style scoped>

  .card3{
    margin-top: 20px;
    width: 100%;
    display: flex;
    justify-content: space-around;
    place-items: center;
    /* color:  hsla(160, 100%, 37%, 1); */
    height: 60px;
  }

  .card3 svg{
    color:  hsla(160, 100%, 37%, 1);
  }

  .card3 .email{
    display: flex;
  }

  .card3 .email h5{
    margin-left: 5px;
  }

  .telp{
    display: flex;
  }

  .address{
    display: flex;
  }
  .content {
    margin-top: 40px;
    display: flex;
    /* padding: 20px; */
    height: 100%;
    width: 90%;
  }

  .card {
    padding: 25px;
    border: none;
  }

  .card2 {
    padding: 25px;
    margin-left: 14px;
    width: 43%;
  }

  .greetings ul li {
    list-style: none;
    line-height: 3rem;
    font-size: 20px;
  }

  .greetings {
    margin-top: 30px;
    padding: 10px 0px;
    border-left: 7px hsla(160, 100%, 37%, 1) solid;
  }
</style>