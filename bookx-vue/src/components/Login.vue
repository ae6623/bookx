<template>
	这是登录组件
	 <div class="popup_login">
      <x-input title="用户名" placeholder="6~12位" :min="6" :max="12" :value.sync="username"></x-input>
      <x-input title="密&nbsp;&nbsp;&nbsp;&nbsp;码" placeholder="6~12位" type="password" :min="6" :max="12" class="password" :value.sync="pwd"></x-input>
    </div>
	<x-button type="primary" @click="login">登录</x-button>
</template>

<script>
	import {XButton,XInput} from 'vux'

	export default {
	  components: {
		XButton,XInput
	  },
	  data () {
	    return {
		  	username: '',
		    pwd:''
		  }
	  },
	  methods: {
		login (){
			alert(this.username + " : " + this.pwd)
			console.log('ahahahah');
		}
	  }
	}
</script>