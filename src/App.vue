<template>
  <div class="cover-container d-flex w-100 h-100 p-3 mx-auto flex-column">
    <header class="masthead mb-auto">
      <div class="inner">
        <h3 class="masthead-brand">Onizuka.dev</h3>
        <nav class="nav nav-masthead justify-content-center">
          <router-link to="/" class="nav-link active">Home</router-link>
          <router-link to="/about" class="nav-link active">About</router-link>
        </nav>
      </div>
    </header>

    <main role="main" class="inner cover">
      <router-view/>
    </main>

    <footer class="mastfoot mt-auto">
      <div class="inner">
        <p>Copyright &copy; 2019 • Ricardo Hernández</p>
      </div>
    </footer>

  </div>
</template>
