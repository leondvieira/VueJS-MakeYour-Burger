
<template>
	
	<div class="message-container">
		<p>{{ msg }}</p>
	</div>
</template>

<script>
import { stringifyQuery } from 'vue-router';

export default {
	name: "Message",
	props: {
		msg: String,
	}
}
</script>


<style scoped>
.message-container {
	color: #004085;
	background-color: #CCE5FF;
	border: 2 px solid #B8DAFF;
	border-radius: 5px;
	padding: 10px;
	max-width: 400px;
	margin: 30px auto;
}
    
</style>