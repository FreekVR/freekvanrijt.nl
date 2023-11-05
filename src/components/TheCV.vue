<template>
    <article class="a4">
        <header class="intro">
            <h1>Curiculum Vitae</h1>
            <h2>Freek van Rijt</h2>
            <h3>Full-stack webdeveloper</h3>
        </header>

        <section>
            <p class="lead">
                Hi! My name is Freek. I am a full-stack webdeveloper specialized in Vue.js and Nuxt.js applications.
            </p>

            <p>
                I enjoy developing not (just) because I like to code, but to meet the needs and exceed the expectations of the end-user and build beautiful and smooth experiences.
            </p>

            <p>
                To reach this goals, over the years I've tried and used various technologies and frameworks. I like working with open source, building re-usable components and packages.
                I hope to work on projects that have a positive impact on the world, in diverse teams of highly skilled and involved people.
            </p>
        </section>

        <section>
            <h3>About me</h3>
            <ul>
                <li>Age: 33</li>
                <li>Location: <br>Amstelveen, The Netherlands</li>
                <li>Education: <br>HBO Bachelor, Communication and multimedia design</li>
                <li>Availability:<br>32-36 hours per week</li>
            </ul>
        </section>

        <section>
            <hgroup>
                <h3>Work experience</h3>
                <p>I started programming on Visual Basic when I was 12. I've since picked up web development and have over 10 years of professional experience at these great companies.</p>
            </hgroup>

            <ul class="work">
                <li>
                    <WorkExperience from="october 2015" to="now">
                        <template #company>
                            Digital Natives
                        </template>
                        <template #location>
                            Amsterdam, The Netherlands
                        </template>
                        <template #position>
                            Lead Full-stack developer
                        </template>
                    </WorkExperience>
                </li>

                <li>
                    <WorkExperience from="september 2010" to="october 2015">
                        <template #location>
                            Utrecht, The Netherlands
                        </template>
                        <template #company>
                            One Shoe
                        </template>
                        <template #position>
                            Full-stack (Drupal) developer
                        </template>
                    </WorkExperience>
                </li>

                <li>
                    <WorkExperience from="april 2019" to="september 2010">
                        <template #location>
                            Aalsmeer / Amsterdam, The Netherlands
                        </template>
                        <template #company>
                            Endemol Nederland Mediagroep BV
                        </template>
                        <template #position>
                            Internship / Part-time full-stack developer
                        </template>
                    </WorkExperience>
                </li>
            </ul>
        </section>

        <section>
             <hgroup>
                <h3>Skills & Experience</h3>
                <p>I excel when working in multidisciplinairy teams, where we can ideate and iterate together.</p>
            </hgroup>
            <ul>
                <li>Leading development teams</li>
                <li>Problem solving and debugging</li>
                <li>Building re-usable packages</li>
                <li>Technical writing, documentation</li>
                <li>Technical and functional design, writing user stories and scopes</li>
                <li>Building, and working with, design systems</li>
                <li>Optimizing both percieved and Google Pagespeed performance</li>
                <li>SEO optimization</li>
                <li>Scrum / Scrum master</li>
                <li>Jira</li>
                <li>Defining technical roadmaps</li>
                <li>Working in multidisciplinairy teams</li>
                <li>Excellent Dutch and English language skills, written and spoken</li>
            </ul>
        </section>

        <section>
            <hgroup>
                <h3>Tech stack</h3>
                <p>I've worked with other tech over the years, but these are my current specalizations.</p>
            </hgroup>
            <ul class="twocol">
                <li>The "basics"
                    <ul>
                        <li>HTML</li>
                        <li>CSS, Less, PostCSS</li>
                    </ul>
                </li>
                <li>Java- & Typescript
                    <ul>
                        <li>"Vanilla" JS</li>
                        <li>Vue.js (v2 and 3)</li>
                        <li>Nuxt.js (v2 and 3)</li>
                        <li>GraphQL</li>
                    </ul>
                </li>
                <li>PHP
                    <ul>
                        <li>"Vanilla" PHP</li>
                        <li>Laravel</li>
                        <li>GraphQL</li>
                    </ul>
                </li>
                <li>Devops
                    <ul>
                        <li>PNPM, Yarn, npm</li>
                        <li>Gitlab CI/CD</li>
                        <li>Vercel</li>
                        <li>Linux servers</li>
                        <li>Composer</li>
                        <li>Eslint, Stylelint, Prettier</li>
                    </ul>
                </li>
            </ul>
        </section>
    </article>
</template>

<script setup lang="ts">
import WorkExperience from '../components/WorkExperience.vue';
</script>

<style scoped>
.a4 {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: auto auto 1fr;
    column-gap: 20px;
    row-gap: 40px;
}
.intro {
    display: flex;
    flex-direction: column;
    gap: 8px;
}

.a4 > * {
    grid-column: 1;
}

.a4 > aside {
    grid-row: 1/4;
    grid-column: 2;
}

.intro h1,
.intro h2,
.intro h3 {
    margin: 0;
    padding: 0;
    line-height: 1;
}

ul {
    margin: 20px 0 0 1em;
    padding: 0;
    list-style-type: disc;
    list-style-position: outside;
}

.twocol {
    display: flex;
    flex-wrap: wrap;
    row-gap: 20px;
}

.twocol ul {
    margin: 0;
}

.twocol > li {
    flex: 1 0 50%;
}

.twocol li {
    white-space: nowrap;
}

li > ul {
    margin-top: 0;
    margin-left: 15px !important;
    list-style-type: circle;
}

h3 + ul {
    margin-top: 0;
}

hgroup p {
    color: var(--color--primary-light);
}

section h3:before {
  content: '';
  display: inline-block;
  width: 4px;
  height: 1.2em;
  margin-right: 10px;
  background-color: var(--color--primary-light);
}

</style>
