<template>
    <main class="flex-shrink-0">
        <div class="container px-5 my-5">
            <div class="text-center mb-5">
                <h1 class="display-5 fw-bolder mb-0"><span class="text-gradient d-inline">Resume</span></h1>
            </div>
            <div class="row gx-5 justify-content-center">
                <div class="col-lg-11 col-xl-9 col-xxl-8">
                    <ExperienceSection></ExperienceSection>
                    <EducationSection></EducationSection>
                    <SkillsSection></SkillsSection>
                </div>
            </div>
        </div>
    </main>
</template>

<script setup>
import ExperienceSection from './ExperienceSection.vue';
import EducationSection from './EducationSection.vue';
import SkillsSection from './SkillsSection.vue';
</script>