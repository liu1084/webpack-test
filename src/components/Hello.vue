<template>
	<div class="hello">
		{{msg}}
	</div>
</template>

<script>
	require('../assets/sass/hello.scss');
	export default {
		name: 'hello',
		data: function(){
			return {
				msg: 'hello'
			}
		}
	}
</script>