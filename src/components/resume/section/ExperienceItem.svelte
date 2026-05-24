<script>
    export let title;
    export let titleDetail = '';
    export let company;
    export let years;
    export let description = '';
    export let tech = '';

    const techList = tech ? tech.split(',').map(t => t.trim()).filter(Boolean) : [];
</script>

<article class="resume-timeline-item position-relative pb-5">
    <div class="resume-timeline-item-header mb-2">
        <div class="d-flex flex-column flex-md-row">
            <h3 class="resume-position-title font-weight-bold mb-1">
                {title}{#if titleDetail}<small class="text-muted fw-normal">{titleDetail}</small>{/if}
            </h3>
            <div class="resume-company-name ms-auto">{company}</div>
        </div>
        <div class="resume-position-time">{years}</div>
    </div>
    {#if description || techList.length > 0}
    <div class="resume-timeline-item-desc">
        {#if description}
        <p class="mb-2">{description}</p>
        {/if}
        {#if techList.length > 0}
        <ul class="list-inline mb-0 mt-2">
            {#each techList as t}
            <li class="list-inline-item mb-1"><span class="badge bg-secondary badge-pill">{t}</span></li>
            {/each}
        </ul>
        {/if}
    </div>
    {/if}
</article>
