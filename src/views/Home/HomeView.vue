<template>
  <div class="home">

    <header>
      <TopUserCard />
    </header>

    <main>
      <section class="weather">
        <WeatherCard />
      </section>

      <section class="menu">
        <CategoryMenu />
      </section>

      <section class="features">
        <FeatureButtons />
      </section>
    </main>

    <footer>
      <BottomNavigation />
    </footer>

  </div>
</template>

<script>
import TopUserCard from '@/components/TopUserCard.vue'
import WeatherCard from '@/components/WeatherCard.vue'

export default {
  components: {
    TopUserCard,
    WeatherCard
  }

}
</script>

<style>

</style>
