<template>
	<div class="container">
		<form action="" role="form">
			<div class="form-group">
				<label for="fname">First Name</label>
				<input type="text" name="fname" id="" class="form-control" v-model="fname">		
			</div>

			<div class="form-group">
				<label for="lname">Last Name</label>
				<input type="text" name="lname" id="" class="form-control" v-model="lname">		
			</div>

			<div class="form-group">
				<label for="password">Password</label>
				<input type="Password" name="password" id="" class="form-control" v-model="password">		
			</div>
			
			<button type="submit" class="btn btn-primary">Send</button>
		</form>
	</div>
</template>

<script>
export default {
	data () {
		return {
			fname: null,
			lname: null,
			password: null
		}
	}
}
</script>