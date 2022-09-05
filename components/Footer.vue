<template>
  <div>
    <footer class="bg-link text-center ">
      <div class="container p-4">
        <section class="">
          <div class="row">
            <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
              <img src="../static/logo.png" alt="The Rant"><br>
              <a href="/">The Rant</a>
            </div>
            <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
              <h5 class="text-uppercase">About The Rant</h5>

              <ul class="list-unstyled mb-0">
                <li>
                  <a href="/about">About The Rant</a>
                </li>
                <li>
                  <a href="https://help.meeovi.com/sites/therant">Help Center</a>
                </li>
                <li>
                  <a href="/blog/tips">Mental and Stress Tips</a>
                </li>
              </ul>
            </div>

            <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
              <h5 class="text-uppercase">Legal</h5>

              <ul class="list-unstyled mb-0">
                <li>
                  <a href="/legal/terms">Terms and Conditions</a>
                </li>
                <li>
                  <a href="/legal/policies">Privacy Policies</a>
                </li>
              </ul>
            </div>
            <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
              <h5 class="text-uppercase">Here2Mingle Company</h5>

              <ul class="list-unstyled mb-0">
                <li>
                  <a href="https://www.thesoundcage.com">The Soundcage</a>
                </li>
                <li>
                  <a href="https://www.therant.xyz">The Rant</a>
                </li>
                <li>
                  <a href="https://www.showyourweird.com">Show Your Weird</a>
                </li>
                <li>
                  <a href="https://www.thementalhealthawareness.com">Mental Health Awareness</a>
                </li>
              </ul>
            </div>
          </div>
        </section>
      </div>

      <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2)">
        © {{ new Date().getFullYear() }} Copyright: <a href="/" target="_blank">The Here2Mingle Company</a>
      </div>

    </footer>
  </div>
</template>

<script>
  export default {

  }

</script>
