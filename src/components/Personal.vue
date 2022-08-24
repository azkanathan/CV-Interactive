<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
<div class="card shadow mb-1 bg-body rounded">
  <div class="greetings">
    <h1 class="green">Muhammad Azka Nathan</h1>
    <p>Nama saya Muhammad Azka Nathan, saya belajar di jurusan Rekayasa Perangkat Lunak dan sangat<br>tertarik untuk menjadi programmer. Saya memiliki pengalaman belajar selama<br>setahun sudah menguasai html,css dan bootstrap</p>
  </div>
</div>
</template>

<style scoped>
.card{
  margin-left: 50px;      
  /* height: 100%; */
  border: none;
  padding: 30px;
  width: 103%;
  min-height: 25vh;

}

.card p{
  font-size: 20px;
}

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
