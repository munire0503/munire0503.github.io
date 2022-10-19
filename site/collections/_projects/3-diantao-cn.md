---
date: 2022-08-05 05:23:00 +0800
title: 点淘体验优化
subtitle: UX 设计
image: '/images/project-diantao-preview'
---

<script>
    function populateContent() {
        const a = document.getElementById("project-diantao-cn-a");
        a.src="/images/project-diantao-cn-a.webp";

        const b = document.getElementById("project-diantao-cn-b");
        b.src="/images/project-diantao-cn-b.webp";

        const c = document.getElementById("project-diantao-cn-c");
        c.src="/images/project-diantao-cn-c.webp";
    }

    if (document.readyState != 'loading') {
        populateContent();
    } else {
        document.addEventListener('DOMContentLoaded', populateContent);
    }
</script>

<img id="project-diantao-cn-a" loading="lazy" style="pointer-events:none; display:block; margin-left:auto; margin-right:auto;" src="/images/loading.gif" alt="Loading...">
<img id="project-diantao-cn-b" loading="lazy" style="pointer-events:none; display:block; margin-left:auto; margin-right:auto;" src="/images/loading.gif" alt="Loading...">
<img id="project-diantao-cn-c" loading="lazy" style="pointer-events:none; display:block; margin-left:auto; margin-right:auto;" src="/images/loading.gif" alt="Loading...">
