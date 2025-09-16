<script>
    export let title;
    export let titleDetail;
    export let company;
    export let years;
    export let description;
    export let titleList;
    export let descriptionList; // TODO: gestisci come un array ed inserisci il for each a monte
</script>

<article class="resume-timeline-item position-relative">
    
    <div class="resume-timeline-item-header mb-2">
        <div class="d-flex flex-column flex-md-row">
            <h3 class="resume-position-title font-weight-bold mb-1">{title}<small class="text-muted">{titleDetail}</small></h3>
            <div class="resume-company-name ms-auto">{company}</div>
        </div><!--//row-->
        <div class="resume-position-time">{years}</div>
    </div><!--//resume-timeline-item-header-->
    <div class="resume-timeline-item-desc">
        <p>{description}</p>
        <h4 class="resume-timeline-item-desc-heading font-weight-bold">{titleList}</h4>
        <ul class="list-inline">
            <li class="list-inline-item"><span class="badge bg-secondary badge-pill">{descriptionList}</span></li>
            <!--
            <li class="list-inline-item"><span class="badge bg-secondary badge-pill">jQuery</span></li>
            <li class="list-inline-item"><span class="badge bg-secondary badge-pill">HTML/LESS</span></li>
            <li class="list-inline-item"><span class="badge bg-secondary badge-pill">MongoDB</span></li>
            -->
        </ul>
    </div><!--//resume-timeline-item-desc-->

</article><!--//resume-timeline-item-->