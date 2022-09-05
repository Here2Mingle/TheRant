<template>
  <div>
    <div class="container my-5">

      <!--Section: Design Block-->
      <section class="mb-10">

        <div class="d-flex justify-content-between align-items-center align-items-xl-end border-bottom pb-4 mb-5"
          style="border-bottom: 2px solid #f5f5f5 !important;">
          <h2 class="fw-bold mb-0">What's on your mind</h2>
          <h6 class="mb-0"><a href="/channel/">Have A Debate <i class="fas fa-angle-right fa-xs ms-1"></i></a></h6>
        </div>
        <div class="row gx-lg-5">
          <div class="col-lg-8">
            <feedPost />
            <!--Section: Design Block-->
            <section class="mb-8">
              <div class="container custom-height py-5 rantfeed" style="background-color: #efeff2;">
                <div class="row g-0 align-items-center">
                  <div class="col-lg-7 mb-4 mb-lg-0">
                    <img src="https://mdbootstrap.com/img/new/blog/42.jpg" class="w-100 rounded-6" alt="Italian city" />
                  </div>
                  <div class="col-lg-5">
                    <div class="card cascading-left rounded-6 shadow-5">
                      <div class="card-body px-4 p-4 p-md-5 p-lg-4 p-xl-5">
                        <h3 class="mb-4">What places to visit during your first trip to Italy? 5 suggestions for
                          backpackers.</h3>
                        <p class="text-muted mb-4">Amet consectetur adipisicing elit quam, natus eum repellendus harum
                          dolore dolorum impedit quas blanditiis amet temporibus assumenda iusto. <span
                            class="d-none d-xl-inline">Fugiat voluptatum provident porro tempore corporis minus vero
                            sint occaecat cupidatat.</span></p>
                        <button class="btn btn-warning">Comment <i class="fas fa-angle-right ms-1"></i></button>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </section>
            <!--Section: Design Block-->
          </div>
          <div class="col-lg-4">
            <!-- Container for demo purpose -->
            <div class="container my-5 py-5 shadow-5">

              <!--Section: Design Block-->
              <section class="text-center">

                <h3 class="mb-5">Latest Rants</h3>
                <!-- Container for demo purpose -->
                <div class="container my-5">

                  <!--Section: Design Block-->
                  <section class="mb-5">
                    <div class="row">
                      <div class="col">
                        <div class="border-lg-end pe-md-3 pe-lg-4">
                          <div class="d-flex flex-row small text-muted">
                            <p class="text-uppercase"><a href="#!" class="text-reset">Economy</a></p>
                            <p class="mx-2">•</p>
                            <p>06/27/2022</p>
                          </div>
                          <h5 class="fw-bold pb-1">
                            The stock exchange is struggling to rebound after considerable declines. There
                            is a chance for a good session.
                          </h5>
                          <p class="small text-muted">
                            By <a href="#!" class="text-reset">Alex Johnson</a>
                          </p>
                        </div>
                      </div>
                      <div class="col">
                        <div class="d-flex flex-row small text-muted">
                          <p class="text-uppercase"><a href="#!" class="text-reset">World</a></p>
                          <p class="mx-2">•</p>
                          <p>06/26/2022</p>
                        </div>
                        <h5 class="fw-bold pb-1">
                          Pride events took place on June 25 all over the world - their course in selected
                          cities.
                        </h5>
                        <p class="small text-muted">
                          By <a href="#!" class="text-reset">Emily Steward</a>
                        </p>
                      </div>
                    </div>
                  </section>
                  <!--Section: Design Block-->

                  <hr class="divider-horizontal" style="margin-bottom: 3.5rem;">

                </div>
                <!-- Container for demo purpose -->

              </section>
              <!--Section: Design Block-->

            </div>
            <!-- Container for demo purpose -->
          </div>
        </div>

      </section>
      <!--Section: Design Block-->

    </div>
  </div>
</template>

<script>
  import feedPost from '~/components/social/feedPost'

  export default {
    components: {
      feedPost
    },
    head: {
      title: 'Rant Feed'
    }
  }

</script>

<style>
  .cascading-left {
    margin-left: -50px;
  }

  @media (max-width: 991.98px) {
    .cascading-left {
      margin-left: 0;
    }
  }

  .custom-height {
    height: 500px;
  }

  @media (max-width: 500px) {
    .custom-height {
      height: 650px;
    }
  }

  .custom-mt {
    margin-top: -240px;
  }

  @media (max-width: 500px) {
    .custom-mt {
      margin-top: -420px;
    }
  }

  @media (min-width: 768px) {
    .border-lg-end {
      border-right: 2px solid #f5f5f5;
    }
  }

</style>
