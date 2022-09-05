<template>
  <!--Main Navigation-->
  <header>
    <!-- Sidebar -->
    <nav id="sidenav-1" class="sidenav" data-mdb-hidden="true">
      <ul class="sidenav-menu">
        <li class="sidenav-item">
          <a class="navbar-brand" href="#">
            Browse the Community
          </a>
        </li>
        <li class="sidenav-item">
          <a class="sidenav-link" href="/">
            <i class="far fa-smile fa-fw me-3"></i><span>Home</span></a>
        </li>
        <li class="sidenav-item">
          <a class="sidenav-link" href="/social/rantfeed">
            <i class="far fa-smile fa-fw me-3"></i><span>Rant Feed</span></a>
        </li>
        <li class="sidenav-item">
          <a class="sidenav-link" href="/channel/">
            <i class="far fa-smile fa-fw me-3"></i><span>Debate Channels</span></a>
        </li>
      </ul>
    </nav>
    <!-- Sidebar -->

    <!-- Navbar -->
    <nav id="main-navbar" class="navbar navbar-expand-lg navbar-light bg-white fixed-top">
      <!-- Container wrapper -->
      <div class="container-fluid">
        <!-- Toggle button -->
        <button data-mdb-toggle="sidenav" data-mdb-target="#sidenav-1" class="btn btn-primary"
          aria-controls="#sidenav-1" aria-haspopup="true">
          <i class="fas fa-bars"> Menu</i>
        </button>

        <!-- Brand -->

        <!-- Search form -->
        <div class="collapse navbar-collapse justify-content-center" id="navbarCenteredExample">
          <a class="navbar-brand" href="#">
            <img src="../static/logo.png" alt="The Rant"> The Rant
          </a>
        </div>
        <!-- Right links -->
        <ul class="navbar-nav ms-auto d-flex flex-row">
          <li class="nav-item">
            <a class="nav-link me-3 me-lg-0" role="button" aria-expanded="false" href="/social/rantfeed"><i
                class="fas fa-comment-alt"></i></a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link me-3 me-lg-0 dropdown-toggle hidden-arrow" href="#" id="navbarDropdownMenuLink"
              role="button" data-mdb-toggle="dropdown" aria-expanded="false">
              <i class="fas fa-user-circle"></i>
            </a>
            <ul class="dropdown-menu dropdown-menu-end" aria-labelledby="navbarDropdownMenuLink">
              <li>
                <a class="dropdown-item" href="/user/">My profile</a>
              </li>
              <li>
                <a class="dropdown-item" href="/user/my-rants">My Rants</a>
              </li>
              <li>
                <a class="dropdown-item" href="#">Logout</a>
              </li>
            </ul>
          </li>
        </ul>
      </div>
      <!-- Container wrapper -->
    </nav>
    <!-- Navbar -->
  </header>
</template>

<style>

</style>
