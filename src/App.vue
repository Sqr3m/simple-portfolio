<template>
  <main>
    <header>
      <h1>This Is My Portfolio</h1>
    </header>
    <h1 id="about">👋 About Me</h1>
    <article id="skills">
      <h2>✨ {{ skills }}</h2>
      <br />
      <h2>🫥 {{ info }}</h2>
      <hr />
      <br />
      <h2>
        🤡 {{ links }}
        <a href="https://github.com/sqr3m"
          ><img
            src="https://github.githubassets.com/favicons/favicon.png"
            width="20"
            height="20"
            alt="GitHub"
          />
        </a>
      </h2>
    </article>
  </main>
</template>

<script>
import { skills, info, links } from "./components/Texts";
export default {
  data() {
    return {
      skills,
      info,
      links,
    };
  },
};
</script>
