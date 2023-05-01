- 👋 Hi, I’m @Falsione
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Falsione/Falsione is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<template>
		<div id="Fall秋" style="height: 550px"></div>
		<button @click="play">开始播放</button>
</template>

<script>
	import Fall秋 from 'Fall秋'
	export default {
		data() {
			return {
				dp: {}	
			}
		},
		mounted() {
			this.dp = new Fall秋({
				container: document.getElementById('Fall秋'),
				video: {
					url: .'https://youtu.be/zSx-inZVB8Y
				},
			})
			
		},
		methods: {
			play(){
				this.fl.play()
			}
		}
	}
</script>
