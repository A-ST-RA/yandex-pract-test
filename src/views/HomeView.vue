<template>
  <main class="content">
    <section class="content__block">
      <h1 class="title-1">Тестовое задание Владислав Бахмацкий</h1>
    </section>
    <section class="content__block">
      <h2 class="content__title title-2">Мои фото &#128526;</h2>
      <div class="photos">
        <div class="photo">
          <h3 class="photo__title title-3">Последнее селфи</h3>
          <img class="photo__image" alt="Последнее Селфи" src="@/assets/images/my-self.jpg" />
        </div>
        <div class="photo">
          <h3 class="photo__title title-3">Cо старшей школы</h3>
          <img class="photo__image" alt="Последнее Селфи" src="@/assets/images/my-self.jpg" />
        </div>
      </div>
    </section>
    <section class="content__block">
      <h2 class="content__title title-2">Как программирование стало любимым делом &#128220;</h2>
      <p class="content__description description">
        Мне было 9 лет, я был у бабушки и дедушки в деревне и играл в The the legend of zelda: Ocarina of time На своей nintendo 3DS.
        Вдруг, мне стало интересно, как делают игры, первым к кому я побежал, это к своему дедушки узнать как делают игры, вдруг знает.
        Тогда дедушка мне сказал, что игры делают программисты. Я этим заинерисовался и через неделю он установил на свой компьютер game maker
        и приходя с работы он учил меня делать игры, я почти ничего не понимал, получалось плохо, но мне это очень нравилось.
        <br />
        <br />
        Так я и познакомился с прорграммированием, далее я развивался в этом направлении и это стало моим любимым делом.
      </p>
    </section>
    <section class="content__block">
      <h2 class="content__title title-2">Видео о программировании</h2>
      <video class="video" controls><source src="@/assets/videos/untitled.mp4" type="video/mp4" /></video>
    </section>
  </main>
</template>

<style scoped>

.content {
  display: flex;
  flex-direction: column;
  min-height: 100dvh;
}

.content__block {
  margin-bottom: 1.5rem;
}

.content__title {
  margin-bottom: 1rem;
}

.content__description {
  max-width: 40rem;
}

.photos {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  column-gap: 2rem;
}

.video {
  width: 100%;
}

.photo {
  display: flex;
  
  flex-grow: 1;

  max-width: 20rem;
  min-width: 4rem;
  
  flex-direction: column;
  justify-content: space-between;
}

.photo__title {
  flex-grow: 1;
  margin-bottom: 0.5rem;
}

.photo__image {
  width: 100%;
}

</style>