<template>
  <main class="home">
    <h1>
      <span class="title-main">OlcaRena</span>

    </h1>
    <a class="contact" href="mailto:studio@olcarena.com">studio@olcarena.com</a>
  </main>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Crimson+Pro:wght@400;500;600&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Geist:wght@400;500;600&display=swap");

:global(html),
:global(body),
:global(#__nuxt) {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
}

.home {
  width: 100vw;
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0;
  background: linear-gradient(135deg, #ffffff 0%, #f2f2f2 100%);
  position: relative;
  overflow: hidden;
}

h1 {
  margin: 0;
  font-family: "Crimson Pro", serif;
  font-weight: 500;
  color: #2a2a2a;
  letter-spacing: 0.08em;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.08em;
  text-shadow:
    0 0 0.55px rgba(0, 0, 0, 0.32),
    0 0 9px rgba(0, 0, 0, 0.11),
    0 0 16px rgba(0, 0, 0, 0.04);
}

.title-main {
  font-size: clamp(2.45rem, 8vw, 5.8rem);
}


.title-sub {
  font-size: clamp(2rem, 6.4vw, 4.6rem);
}

.contact {
  position: absolute;
  right: 2.2rem;
  bottom: 1.8rem;
  font-family: "Geist", sans-serif;
  font-size: 0.9rem;
  font-weight: 500;
  letter-spacing: 0.04em;
  color: #3a3a3a;
  text-decoration: none;
  opacity: 0.9;
}
</style>
