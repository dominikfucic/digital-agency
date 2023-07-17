<template>
  <section class="projects">
    <h2 class="projects__title">Our Recent Projects</h2>
    <p class="projects__decription">
      Lorem Ipsum is simply dummy text of the printing and typesetting industry.
    </p>
    <div class="projects-list">
      <div class="project">
        <img src="../assets/img1.png" />
      </div>
      <div class="project">
        <img src="../assets/img2.png" />
      </div>
      <div class="project">
        <img src="../assets/img3.png" />
      </div>
      <div class="project">
        <img src="../assets/img4.png" />
      </div>
    </div>
  </section>
</template>

<style scoped>
.projects__title {
  color: #222;
  font-size: 1.25rem;
  font-weight: 600;
  text-align: center;
  margin-bottom: 1.5rem;
}

.projects {
  margin: 3.75rem 1.35rem;
}

.projects__decription {
  color: #525252;
  font-size: 0.75rem;
  font-weight: 400;
  text-align: center;
  margin-bottom: 3rem;
}

.project {
  display: flex;
  justify-content: center;
}

.projects-list {
  display: flex;
  flex-direction: column;
  gap: 1.75rem;
}
</style>
