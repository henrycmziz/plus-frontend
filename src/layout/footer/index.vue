<template>
	<div class="layout-footer pb15">
		<div class="layout-footer-warp">
			<div>
				Based on <a href="https://github.com/lyt-Top/vue-next-admin" target="_blank" rel="noreferrer noopener">vue-next-admin</a> &
				<a href="https://github.com/dromara/RuoYi-Vue-Plus" target="_blank" rel="noreferrer noopener">RuoYi-Vue-Plus</a> 🙂
			</div>
			<div class="mt5">©2023 henrycmziz</div>
		</div>
	</div>
</template>

<script setup lang="ts" name="layoutFooter">
// 此处需有内容（注释也得），否则缓存将失败
</script>

<style scoped lang="scss">
.layout-footer {
	width: 100%;
	display: flex;
	&-warp {
		margin: auto;
		color: var(--el-text-color-secondary);
		text-align: center;
		animation: error-num 0.3s ease;
	}

	a {
		color: inherit;
		text-decoration: underline;
	}
}
</style>
