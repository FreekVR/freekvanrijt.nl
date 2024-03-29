<template>
    <article class="a4">
        <header class="intro">
            <div class="headings">
                <h1>Curiculum Vitae</h1>
                <h2>Freek van Rijt</h2>
                <h3>Full-stack webdeveloper</h3>
            </div>
            <img src="/img/freek.webp" alt="" width="125" height="125">
        </header>

        <section>
            <p class="lead">
                Hey, I'm Freek, a full-stack webdeveloper specialized in Laravel, Vue.js and Nuxt.js.
            </p>

            <p>
                I love coding because I want to build beautiful and smooth user experiences that make the end-users happy.
            </p>
            
            <p>
                I enjoy building re-usable components and packages that can benefit other developers and projects. I would love to work on meaningful and impactful projects within diverse and talented teams.
            </p>
        </section>

        <section>
            <h3>About me</h3>
            <ul>
                <li>Age: 33</li>
                <li>Location: <br>Amstelveen, The Netherlands</li>
                <li>Education: <br>HBO Bachelor, Communication and multimedia design, Hogeschool van Amsterdam</li>
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
                            Lead Full-stack developer (PHP/Javascript/NodeJS)
                        </template>
                        <template #description>
                            <p>
                                At Digital Natives I've worked on a wide range of projects, from small to large, from simple to complex.

                                We initially worked with Laravel/Blade and Wordpress, but have since moved to headless Vue.js and Nuxt.js on the frontend, the introduction of which I championed.
                                I've worked on both back-end projects with Laravel and Craft CMS / Yii, and on front-end projects with Vue.js and Nuxt.js.
                                I've also worked on building, maintaining and designing internal systems, like Gitlab CI/CD, documentation tools and various shared components and packages.
                            </p>
                            <ul>
                                <li>Transitioned into a technical lead role.</li>
                                <li>Defining and maintaining (coding) standards for the company (~10 developers)</li>
                                <li>Responsible for technical quality of projects, refining Scrum backlog, and guiding a team of 4 developers.</li>
                                <li>Works with clients to discuss technical impediments and ensure team efficiency.</li>
                                <li>Helping to set-up and optimize team operations, both in the technical sense, including hosting, CI/CD pipelines and code sharing, but also in the operational sense, with Jira, Slack and automations.</li>
                                <li>Following and guarding Scrum principles.</li>
                                <li>Skilled in using software like Jira, Confluence, and Gitlab.</li>
                                <li>Tech stack includes Vue.JS 1-3, Nuxt 2-3, Laravel 5-11, Craft CMS 3-4, LESS, CSS, Javascript, Git, Gitlab, jQuery, Jira.</li>
                            </ul>
                        </template>
                    </WorkExperience>
                </li>

                <li>
                    <WorkExperience from="september 2010" to="october 2015" >
                        <template #location>
                            Utrecht, The Netherlands
                        </template>
                        <template #company>
                            One Shoe
                        </template>
                        <template #position>
                            Full-stack (Drupal) developer
                        </template>
                        <template #description>
                            <p>
                                One Shoe was my first full-time job as a developer. I worked with Drupal 6 and 7, and was responsible for building and maintaining various Drupal websites.
                            </p>
                            <ul>
                                <li>Working with Scrum and Waterfall projects in a team of 5-10 developers.</li>
                                <li>Responsible for the technical quality of the projects.</li>
                                <li>Worked on many Drupal (e-)health projects, such as <a href="https://thuisarts.nl">Thuisarts.nl</a>, <a href="https://lhv.nl">LHV.nl</a>, and <a href="https://haweb.nl">HAweb.nl</a>, a social online platform for general practitioners.</li>
                                <li>Tech stack includes Drupal 5-7, SASS, Compass, CSS, Javascript, Git, SVN, jQuery.</li>
                            </ul>
                        </template>
                    </WorkExperience>
                    <div class="print-only"><br><br><br></div>
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
                        <template #description>
                            <p>At Endemol, I worked first as an intern, then as a part-time employee during my studies at the Hogeschool van Amsterdam.</p>
                            <ul>
                                <li>Worked with Flash, then also learned the PHP Zend Framework and worked with its template system to craft various web projects.</li>
                                <li>Built a completely custom PHP-based CMS for one of the projects, allowing the client to manage the daily program schedule for a thematic TV station and to publish it on the website.</li>
                                <li>Tech stack includes Flash/Actionscript 3, PHP Zend Framework, Javascript, CSS, jQuery, SVN.</li>
                            </ul>
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
    justify-content: space-between;

    .headings {
        display: flex;
        flex-direction: column;
        gap: 8px;
    }
    img {
        border-radius: 5px;
        overflow: hidden;
    }
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

.lead,
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
