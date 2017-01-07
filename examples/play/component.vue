<template>
	<div>
		<div class="block">
			<span class="demonstration">默认</span>
			<el-slider v-model="value1"></el-slider>
		</div>
		<div class="block">
			<span class="demonstration">自定义初始值</span>
			<el-slider v-model="value2"></el-slider>
		</div>
		<div class="block">
			<span class="demonstration">禁用</span>
			<el-slider v-model="value3" disabled></el-slider>
		</div>
	</div>
</template>

<script type="text/ecmascript-6">
	export default {
		data() {
			return {
				value1: 0,
				value2: 50,
				value3: 42
			}
		}
	};
</script>