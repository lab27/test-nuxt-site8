<template lang="pug">
ContentDoc(v-slot="{ doc }")
  ContentRenderer(:value="doc")
</template>