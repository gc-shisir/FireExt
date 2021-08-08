<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <NuxtLink class="navbar-brand" to="#">FireExt</NuxtLink>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="ml-auto">
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item active">
              <NuxtLink class="nav-link" to="/">
                Home
                <span class="sr-only">(current)</span>
              </NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink class="nav-link" to="/products">Products</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink class="nav-link" to="/my-items">My Items</NuxtLink>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {}
</script>

<style></style>
