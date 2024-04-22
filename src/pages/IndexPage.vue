<template>
  <q-page class="flex flex-center main_title">
    <h4>Красивые взлеты и посадки в Домодедово</h4>
    <iframe
      width="560"
      height="315"
      src="https://www.youtube.com/embed/ZkwRTp3hdd8?si=22VYZWTUKMcMk0KU&amp;controls=0"
    ></iframe>

    <div class="wrap">
      <h6>Управлять самолетом</h6>
      <q-btn-group class="q-ml-lg">
        <q-btn color="secondary" glossy label="Лево" />
        <q-btn color="secondary" glossy label="Право" />
        <q-btn color="secondary" glossy label="Вперед" />
        <q-btn color="secondary" glossy label="Назад" />
      </q-btn-group>
    </div>
  </q-page>
</template>

<script setup>
defineOptions({
  name: "IndexPage",
});
</script>

<style scoped>
.main_title {
  display: flex;
  flex-direction: column;
}
.wrap{
  display: flex;
  flex-direction: row;
  align-items: center;
}
</style>