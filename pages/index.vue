<template>
<main>
  <Hero/>
  </main>
</template>

<script>
import Hero from '@/components/hero'
export default {}
</script>

<style>
*,
*::after,
*::before {
	box-sizing: border-box;
}

:root {
	font-size: 16px;
}

body {
	margin: 0;
	font-family: Ivy Mode;
	-webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
main{
  max-width: 100%;
}

@media (max-width: 768px){
	html, body {
		height: 100vh;
		overflow: hidden;
    }
    :root {
      font-size: 12px;
    }
    
}
</style>
