<template lang="pug">
div
	header.bg-green
		row(center)
			column(small="1", medium="2:3")
				h3.logo doc
	main.bg-white
		<nuxt></nuxt>
	svd-footer
</template>
<style lang="scss">
@import "~svd-style/ext";
header {
  padding: grid(1);
}
</style>

<script>
import svdFooter from "svd-footer/src/components/svd-footer.vue";
console.log(svdFooter);

export default {
  components: { svdFooter }
};
</script>
