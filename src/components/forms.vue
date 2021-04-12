<template>
<form id="form">
 	<div class="field">
 		<div class="control is-expanded">
 			<input type="text" class="input" name="name" placeholder="Your name">
 		</div>
 	</div>
 	<div class="field">
 		<div class="control is-expanded">
 			<input type="email" class="input" name="name" placeholder="Your email">
 		</div>
 	</div>
 	<div class="field">
 		<div class="control is-expanded">
 			<textarea name="" id="" cols="30" rows="5" class="textarea has-fixed-size"  placeholder="Your message"></textarea>
 		</div>
 	</div>
 	<div class="field">
 		<div class="control">
 			<input type="submit" value="Send message" class="button">
 		</div>
 	</div>
</form>
</template>

<script>
export default {
  name: 'forms',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
#form .input{
	padding-left:1rem;
	height: 8vh;
	box-shadow: none;
	font-family: raleway;
	font-weight: bold;
	letter-spacing: 1px;
	/*border-radius: 0;*/
}
#form .textarea{
	box-shadow: none;
	font-family: raleway;
	font-weight: bold;
	letter-spacing: 2px;
}
/*button*/
#form .button{
	/*padding: 1rem;*/
	font-family: Raleway;
	font-weight: bolder;
	color:white;
	height: 4rem;
	/*padding: 1rem;*/
	border:none;
	background-color: #69c1a3;
}
@media screen and (max-width: 720px) {
	html{
		font-size: 13px
	}
}
</style>
