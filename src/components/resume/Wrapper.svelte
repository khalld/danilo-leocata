<script>
    import BodyResumeWrapper from "./Body.svelte";
    import HeaderResumeWrapper from "./Header.svelte";

</script>

<style>
    article {
        font-family: 'Source Sans 3', sans-serif;
        font-size: 13px;
    }
</style>

<article class="resume-wrapper text-center position-relative">
	<div class="resume-wrapper-inner mx-auto text-start bg-white shadow-lg">
		<HeaderResumeWrapper/>
		<BodyResumeWrapper/>
	</div>
</article> 