<template>
  <div class="container">
    <nuxt/>
    <CookieControl :locale="$store.state.lang"/>
  </div>
</template>