<template>
  <div>
    Some default layout shared across all pages
      <NuxtLink to="/">
        Home page
      </NuxtLink>
      <NuxtLink to="/aboutUs">
        About page
      </NuxtLink>
    <slot />
  </div>
</template>