<template>
	这是登录组件
	<x-button type="primary" @click="login">登录</x-button>
</template>

<script>
	import {XButton} from 'vux'

	export default {
	  components: {
		XButton
	  },
	  data () {
	    return {
		  username: '',
		    pwd:''
		  }
	  },
	  methods: {
		login (){
			console.log('ahahahah');
		}
	  }
	}
</script>