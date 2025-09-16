<script>
    import BodyResumeSectionSummaryWrapper from "./section/Summary.svelte";
    import ExperienceSectionWrapper from "./section/Experience.svelte";
    import Skills from "./section/Skills.svelte";
    import Education from "./section/Education.svelte";
    import Reference from "./section/Reference.svelte";
    import Language from "./section/Language.svelte";
    import Interests from "./section/Interests.svelte";
</script>

<div class="resume-body p-5">
    <BodyResumeSectionSummaryWrapper/>
    <div class="row">
        <div class="col-lg-9">
            <ExperienceSectionWrapper/>
        </div>
        <div class="col-lg-3">
            <Skills/>

            <Education/>
            
            <Reference/>

            <Language/>
            
            <Interests/>
        </div>
    </div><!--//row-->
</div><!--//resume-body-->