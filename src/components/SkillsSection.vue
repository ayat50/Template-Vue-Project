<script setup>

const Professional={
  skill:'Professional Skills',
  cros:'SEO/SEM Marketing',
  anal:'Statistical Analysis',
  group:'Web Development',
  net:'Network Security',
  adob:'Adobe Software Suite',
  user:'User Interface Design',
  lrg:'Languages',
  ht:'HTML',
  cs:'CSS',
  js:'JavaScript',
  pt:'Python',
  ru:'Ruby',
  no:'Node.js',

}

</script>
<template>
  <div class="pb-5"></div>
  <!-- Skills Section-->
  <section>
    <!-- Skillset Card-->
    <div class="card shadow border-0 rounded-4 mb-5">
      <div class="card-body p-5">
        <!-- Professional skills list-->
        <div class="mb-5">
          <div class="d-flex align-items-center mb-4">
            <div
              class="feature bg-primary bg-gradient-primary-to-secondary text-white rounded-3 me-3">
              <i class="bi bi-tools"></i>
            </div>
            <h3 class="fw-bolder mb-0">
              <span class="text-gradient d-inline">{{ Professional.skill }}</span>
            </h3>
          </div>
          <div class="row row-cols-1 row-cols-md-3 mb-4">
            <div class="col mb-4 mb-md-0">
              <div
                class="d-flex align-items-center bg-light rounded-4 p-3 h-100">
                {{ Professional.cros }}
              </div>
            </div>
            <div class="col mb-4 mb-md-0">
              <div
                class="d-flex align-items-center bg-light rounded-4 p-3 h-100">
                {{ Professional.anal }}
              </div>
            </div>
            <div class="col">
              <div
                class="d-flex align-items-center bg-light rounded-4 p-3 h-100">
                {{ Professional.group }}
              </div>
            </div>
          </div>
          <div class="row row-cols-1 row-cols-md-3">
            <div class="col mb-4 mb-md-0">
              <div
                class="d-flex align-items-center bg-light rounded-4 p-3 h-100">
                {{ Professional.net }}
              </div>
            </div>
            <div class="col mb-4 mb-md-0">
              <div
                class="d-flex align-items-center bg-light rounded-4 p-3 h-100">
                {{ Professional.adob }}
              </div>
            </div>
            <div class="col">
              <div
                class="d-flex align-items-center bg-light rounded-4 p-3 h-100">
                {{ Professional.user }}
              </div>
            </div>
          </div>
        </div>
        <!-- Languages list-->
        <div class="mb-0">
          <div class="d-flex align-items-center mb-4">
            <div
              class="feature bg-primary bg-gradient-primary-to-secondary text-white rounded-3 me-3">
              <i class="bi bi-code-slash"></i>
            </div>
            <h3 class="fw-bolder mb-0">
              <span class="text-gradient d-inline">{{Professional.lrg }}</span>
            </h3>
          </div>
          <div class="row row-cols-1 row-cols-md-3 mb-4">
            <div class="col mb-4 mb-md-0">
              <div
                class="d-flex align-items-center bg-light rounded-4 p-3 h-100">
                {{ Professional.ht }}
              </div>
            </div>
            <div class="col mb-4 mb-md-0">
              <div
                class="d-flex align-items-center bg-light rounded-4 p-3 h-100">
                {{ Professional.cs }}
              </div>
            </div>
            <div class="col">
              <div
                class="d-flex align-items-center bg-light rounded-4 p-3 h-100">
                {{ Professional.js }}
              </div>
            </div>
          </div>
          <div class="row row-cols-1 row-cols-md-3">
            <div class="col mb-4 mb-md-0">
              <div
                class="d-flex align-items-center bg-light rounded-4 p-3 h-100">
                {{ Professional.pt }}
              </div>
            </div>
            <div class="col mb-4 mb-md-0">
              <div
                class="d-flex align-items-center bg-light rounded-4 p-3 h-100">
                {{ Professional.ru }}
              </div>
            </div>
            <div class="col">
              <div
                class="d-flex align-items-center bg-light rounded-4 p-3 h-100">
                {{ Professional.no }}
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

