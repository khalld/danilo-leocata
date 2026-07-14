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
                description="Fintech Consultant for major banking clients, delivering end-to-end solutions across back-office, and customer-facing platforms from initial requirements and architecture to final production release. Collaborate on the modernization of the bank's core sales platform — which processes 250,000--300,000 daily transactions — helping boost system performance by 50% during a full-scale migration to AWS. Optimize system reliability through rigorous load testing and monitoring, while managing release pipelines, deployment workflows, and enablement ticketing. By integrating AI agents into daily development workflows, cut delivery time by 30% and accelerate bug detection by 40%, strategic time savings reinvested into anticipating future development needs, mastering new frameworks, and pursuing technical certifications."
                tech="Java, Spring Boot, Maven, Oracle DB, Kibana, RedHat, JPA, JDBC"/>

            <ExperienceItem
                title="Backend Developer"
                company="Mongibello Tech · Catania"
                years="Jul 2022 – Mar 2024"
                description="Owned and maintained microservices for game management across national and international gaming platforms operating in 3 markets, processing over 10,000 daily transactions. Delivering end-to-end solutions across multiple concurrent projects, coordinating with cross-country teams to consistently hit tight release deadlines while cutting the defect rate by 50%."
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
