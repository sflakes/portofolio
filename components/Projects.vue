<template>
  <section>
    <div class="project">
      <b-card
        :title="repo.name"
        tag="article"
        style="max-width: 20rem"
        class="mb-5"
        v-for="repo in repos"
        :key="repo.id"
      >
        <b-card-text>
          {{ repo.Detail }}
        </b-card-text>

        <b-button :href="repo.link" variant="primary">Repository</b-button>
      </b-card>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      repos: [
        {
          id: 1,
          name: "The Card",
          link: "https://github.com/sflakes/challenge_1",
          Detail: "Html5, Css3, VueJS, Responsive",
        },
        {
          id: 2,
          name: "Hundle Landing Page",
          link: "https://github.com/sflakes/hundle-landing-page",
          Detail: "Html5.  Css3, VueJS, Responsive",
        },
        {
          id: 3,
          name: "The Restaurant",
          link: "https://github.com/sflakes/submission",
          Detail:
            "Html5, Css3, VueJS, BoostrapVue, Axios, ToastNotification, Responsive",
        },
        {
          id: 4,
          name: "Refactory",
          link: "https://github.com/sflakes/refactoryClone/tree/master",
          Detail: "Html5, Css3, VueJS",
        },
        {
          id: 5,
          name: "Portofolio",
          link: "https://github.com/sflakes/portofolio/tree/master",
          Detail: "Html5, Css3, VueJS, Responsives",
        },
      ],
    };
  },
};
</script>

<style>
@import url("assets/style/Projects.css");
</style>