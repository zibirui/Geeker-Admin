<template>
	<div class="content-box">
		<el-alert
			title="SVG 图标目前使用 vite-plugin-svg-icons 插件完成，官方文档请查看 ：https://github.com/vbenjs/vite-plugin-svg-icons"
			type="warning"
			:closable="false"
		/>
		<br />
		<div class="icon-list">
			<SvgIcon name="xianxingdaoyu"></SvgIcon>
			<SvgIcon name="xianxingdiqiu"></SvgIcon>
			<SvgIcon name="xianxingditu"></SvgIcon>
			<SvgIcon name="xianxingfanchuan"></SvgIcon>
			<SvgIcon name="xianxingfeiji"></SvgIcon>
			<SvgIcon name="xianxinglvhangriji"></SvgIcon>
			<SvgIcon name="xianxingtianqiyubao"></SvgIcon>
			<SvgIcon name="xianxingxiangjipaizhao"></SvgIcon>
			<SvgIcon name="xianxingxiarilengyin"></SvgIcon>
			<SvgIcon name="xianxingyoulun"></SvgIcon>
			<SvgIcon name="xianxingxiarilengyin"></SvgIcon>
		</div>
		<el-descriptions title="配置项 📚" :column="1" border>
			<el-descriptions-item label="name"> 图标的名称，svg 图标必须存储在 src/assets/icons 目录下 </el-descriptions-item>
			<el-descriptions-item label="prefix"> 图标的前缀，默认为 "icon" </el-descriptions-item>
			<el-descriptions-item label="iconStyle"> 图标的样式，默认样式为 { width: "100px", height: "100px" } </el-descriptions-item>
		</el-descriptions>
	</div>
</template>

<script setup lang="ts" name="svgIcon">
import SvgIcon from "@/components/SvgIcon/index.vue";
</script>

<style scoped lang="scss">
@import "./index.scss";
</style>
