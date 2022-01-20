<template>
	<div class="home">
		<b-container fluid class="content">
			<b-row no-gutters>
				<b-col>
					<p>Hi! My name is</p>
					<h1>Daria Gonsalves</h1>
				</b-col>
			</b-row>
			<b-row no-gutters>
				<b-col>
					<p>I'm a web developer specializing in backend architecture for cloud based applications for the last 3 years.</p>
					<p>In my free time I'm also a hobbyist game designer 🕹️</p>
				</b-col>
			</b-row>
			<b-row>
				<b-col><p>© dariagonsalves.com</p></b-col>
				<b-col> </b-col>
			</b-row>
		</b-container>
	</div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
// import Sidebar from "@/components/Sidebar.vue";
// import About from "@/components/About.vue";
import awsbadge from "@/assets/aws-certified-developer-associate.png";

export default {
	name: "Home",
	components: {},
	data() {
		return {
			awsbadge,
			mainProps: { width: 75, height: 75, class: "m1" },
		};
	},
};
</script>

<style scoped>
.about {
	border-radius: 25px;
	border: none;
	box-shadow: 5px 5px 5px lightgray;
	color: 20303c;
	font-family: "Cambria";
	background: #fff8f6;
	float: right;
	height: 20rem;
	width: 70%;
	margin-top: 10rem;
	font-size: 1.2em;
}

.title {
	width: 100%;
	height: 15em;
	/* text-align: center; */
	vertical-align: text-bottom;
	border: none;
	margin-top: 15rem;
	font-size: 2em;
	font-family: "Cambria";
	color: #20303c;
}
.title h1 {
	font-size: 2em;
	font-weight: bold;
}
.home {
	background-color: #fff0ee;
	height: 100vh;
	width: 100%;
	font-family: "Cambria";
}
.home h1 {
	font-weight: bold;
}
.content {
	height: 100%;
}
</style>
