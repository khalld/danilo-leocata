<script>
    import ExperienceItem from "./ExperienceItem.svelte";
</script>

<section class="resume-section experience-section mb-5">
    <h2 class="resume-section-title text-uppercase font-weight-bold pb-3 mb-3">Work Experience</h2>
    <div class="resume-section-content">
        <div class="resume-timeline position-relative">

            <ExperienceItem
                title="IT Consultant"
                company="Reply Technology Financial Services · Milano"
                years="Mar 2024 – Present"
                description="Fintech consultant for major banking clients across backoffice, trading, and customer-facing platforms. Fully autonomous in planning and delivering projects end-to-end — from requirements analysis and architectural design to implementation and production release. Led legacy modernization and microservices migration initiatives. Drove performance optimization through load testing and monitoring. Comfortable working independently as well as coordinating with colleagues and managing team activities, including the full delivery lifecycle: release management, testing pipelines, and enablement ticketing. Currently exploring and applying AI agents to streamline and accelerate daily development workflows."
                tech="Java, Spring Boot, Maven, Oracle DB, Kibana, RedHat, JPA, JDBC"/>

            <ExperienceItem
                title="Backend Developer"
                company="Mongibello Tech · Catania"
                years="Jul 2022 – Mar 2024"
                description="Owned all microservices for game management on national and international gaming platforms. Operated autonomously across multiple concurrent projects, coordinating with international teams and delivering within tight deadlines."
                tech="Spring Boot, Gradle, Java, Groovy, MySQL, Bash"/>

            <ExperienceItem
                title="FullStack Developer"
                company="Synapses · Catania"
                years="Sep 2021 – Jul 2022"
                description="Bug fixing and feature development on the proprietary product; built an internal estimation tool from scratch."
                tech="Flutter, Java Spring Boot, Maven, Docker, Kubernetes"/>

            <ExperienceItem
                title="FullStack Developer"
                company="Bizmate · Catania"
                years="Dec 2019 – Jun 2021"
                description="Developed multiple products from scratch: restaurant reservation web-app, License Manager, and Account Manager. Started with front-end maintenance, then took full ownership of new builds."
                tech="Svelte, NodeJS, Docker, MongoDB, Keycloak, Redis, Bootstrap"/>

            <ExperienceItem
                title="FullStack Developer"
                titleDetail=" · Training Programme"
                company="Adecco · Bologna"
                years="Oct 2019 – Dec 2019"
                description="Adecco partner training programme focused on enterprise Java development."
                tech="Java, MySQL, Spring Boot, JPA, JDBC, JSP"/>

        </div>
    </div>
</section>
