<script>
import Section from './Second.svelte';
const elem = document.querySelector('.square');
let color;

function colorPicker(event) {
	color = event.target.value;
	console.log(color);
	elem.style.backgroundColor = color;
}

</script>

<style>

div{
	width: 100px;
	height: 100px;
	background: purple;
}
input{
	margin-right: 20px;
	width: 30px;
	height: 30px;
	border-radius: 50%;
	}
</style>

<div class="square"></div>
<h1>Choose color</h1>
<input on:input={colorPicker} type="color" value={color}>

<Section/>