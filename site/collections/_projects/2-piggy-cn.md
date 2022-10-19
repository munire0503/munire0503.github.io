---
date: 2022-08-05 05:21:00 +0800
title: 小猪民宿再设计
subtitle: Unsolicited Redesign
image: '/images/project-piggy-preview'
---

<script>
    function populateContent() {
        const a = document.getElementById("project-piggy-cn-a");
        a.src="/images/project-piggy-cn-a.webp";

        const b = document.getElementById("project-piggy-cn-b");
        b.src="/images/project-piggy-cn-b.webp";

        const c = document.getElementById("project-piggy-cn-c");
        c.src="/images/project-piggy-cn-c.webp";

        const d = document.getElementById("project-piggy-cn-d");
        d.src="/images/project-piggy-cn-d.webp";
    }

    if (document.readyState != 'loading') {
        populateContent();
    } else {
        document.addEventListener('DOMContentLoaded', populateContent);
    }
</script>

<img id="project-piggy-cn-a" loading="lazy" style="pointer-events:none; display:block; margin-left:auto; margin-right:auto;" src="/images/loading.gif" alt="Loading...">
<img id="project-piggy-cn-b" loading="lazy" style="pointer-events:none; display:block; margin-left:auto; margin-right:auto;" src="/images/loading.gif" alt="Loading...">
<img id="project-piggy-cn-c" loading="lazy" style="pointer-events:none; display:block; margin-left:auto; margin-right:auto;" src="/images/loading.gif" alt="Loading...">
<img id="project-piggy-cn-d" loading="lazy" style="pointer-events:none; display:block; margin-left:auto; margin-right:auto;" src="/images/loading.gif" alt="Loading...">
