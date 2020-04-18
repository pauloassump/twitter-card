<template>
  <div class="custom-card">
    <div class="card-content">
        <div class="media">
            <div class="media-left">
                <figure class="image is-48x48">
                <img class="is-rounded" src="../images/paulo.jpeg" alt="Placeholder image">
                </figure>
            </div>
            
            <div class="media-content">
                <p class="title is-5">Paulo H. de Assumpção</p>
                <p class="subtitle is-6">28 anos, Joinville/SC</p>
            </div>
        </div>

        <div class="content">
            <br>
            Desenvolvedor Frontend na Agapys Tecnologia. Cursando TADS na faculdade Anhanguera - 5ª fase.
        </div>
        <div class="content">
            <span class="tag is-link">VueJs</span> <span class="tag is-link">Quasar Framework</span>
        </div>
  </div>
</div>
</template>

<script>
export default {
  name: "Card"
};
</script>

<style scoped>
.custom-card {
  height: 100%;
  width: 100%;
  padding: 15px;
}
</style>
