<script>
    import BodyResumeSectionSummaryWrapper from "./section/Summary.svelte";
    import ExperienceSectionWrapper from "./section/Experience.svelte";
    import Skills from "./section/Skills.svelte";
    import Education from "./section/Education.svelte";
    import Reference from "./section/Reference.svelte";
    import Language from "./section/Language.svelte";
    import Interests from "./section/Interests.svelte";
    import Certifications from "./section/Certifications.svelte";
</script>

<div class="resume-body p-5">
    <BodyResumeSectionSummaryWrapper/>
    <div class="row">
        <div class="col-lg-9">
            <ExperienceSectionWrapper/>
            <section class="resume-section projects-section mb-5">
                <h2 class="resume-section-title text-uppercase font-weight-bold pb-3 mb-3">Selected Projects</h2>
                <div class="resume-section-content">
                    <p class="mb-3" style="font-size:0.85rem; color:#8d9aad;">Full list on <a href="https://github.com/khalld" target="_blank" rel="noopener" style="color:#142D5F;">GitHub</a>.</p>
                    <div class="row g-3">
                        <div class="col-md-6">
                            <div class="p-3 h-100" style="border:1px solid #dde3ec; border-radius:5px; border-left:3px solid #142D5F;">
                                <div class="d-flex justify-content-between align-items-start mb-1">
                                    <strong style="color:#142D5F; font-size:0.9rem;">CrowdSim Real</strong>
                                    <span class="text-muted" style="font-size:0.75rem;">2023</span>
                                </div>
                                <p class="mb-2" style="font-size:0.82rem; color:#58677c;">Deep RL simulator for LiDAR-based robot navigation in complex, crowded environments.</p>
                                <span class="badge badge-light">Python</span>
                                <span class="badge badge-light">PyTorch</span>
                                <span class="badge badge-light">Deep RL</span>
                            </div>
                        </div>
                        <div class="col-md-6">
                            <div class="p-3 h-100" style="border:1px solid #dde3ec; border-radius:5px; border-left:3px solid #142D5F;">
                                <div class="d-flex justify-content-between align-items-start mb-1">
                                    <a href="https://github.com/ingegneria-sistemi-distribuiti-2023" target="_blank" rel="noopener" style="color:#142D5F; font-size:0.9rem; font-weight:600; text-decoration:none;">Gamble Platform</a>
                                    <span class="text-muted" style="font-size:0.75rem;">2023</span>
                                </div>
                                <p class="mb-2" style="font-size:0.82rem; color:#58677c;">Microservices-based online football betting platform following distributed systems best practices.</p>
                                <span class="badge badge-light">Java</span>
                                <span class="badge badge-light">Spring Boot</span>
                            </div>
                        </div>
                        <div class="col-md-6">
                            <div class="p-3 h-100" style="border:1px solid #dde3ec; border-radius:5px; border-left:3px solid #142D5F;">
                                <div class="d-flex justify-content-between align-items-start mb-1">
                                    <a href="https://github.com/sistemi-cloud-2022/main" target="_blank" rel="noopener" style="color:#142D5F; font-size:0.9rem; font-weight:600; text-decoration:none;">Biobanksprec</a>
                                    <span class="text-muted" style="font-size:0.75rem;">2022</span>
                                </div>
                                <p class="mb-2" style="font-size:0.82rem; color:#58677c;">Monolith-to-microservices migration with CI/CD (GitHub Actions), Keycloak auth, and AWS deploy.</p>
                                <span class="badge badge-light">Java</span>
                                <span class="badge badge-light">Kubernetes</span>
                                <span class="badge badge-light">AWS</span>
                            </div>
                        </div>
                        <div class="col-md-6">
                            <div class="p-3 h-100" style="border:1px solid #dde3ec; border-radius:5px; border-left:3px solid #142D5F;">
                                <div class="d-flex justify-content-between align-items-start mb-1">
                                    <a href="https://github.com/khalld/triplet-trashbin-classifier" target="_blank" rel="noopener" style="color:#142D5F; font-size:0.9rem; font-weight:600; text-decoration:none;">Triplet Trashbin Classifier</a>
                                    <span class="text-muted" style="font-size:0.75rem;">2022</span>
                                </div>
                                <p class="mb-2" style="font-size:0.82rem; color:#58677c;">Triplet Neural Network for image classification using PyTorch Lightning.</p>
                                <span class="badge badge-light">Python</span>
                                <span class="badge badge-light">PyTorch</span>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </div>
        <div class="col-lg-3">
            <Skills/>
            <Education/>
            <Certifications/>
            <Reference/>
            <Language/>
            <Interests/>
        </div>
    </div>
</div>
