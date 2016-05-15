Bomb Picture (3D)
---

You can use it like this: 

	<style type="text/css">
		.wrapper {
			position: relative;
			cursor: pointer;
			perspective: 250px;
		}
	</style>
	
	<div class="wrapper" id="zd-wrap"></div>
			
	<script src="js/bomb.js" type="text/javascript" charset="utf-8"></script>
	<script type="text/javascript">
		var explore = new ParticlesTemplate(),
			exploreImg = new Image(),
			wrapper = document.getElementById('zd-wrap');
		exploreImg.src = 'img/zoro.jpg';	
		exploreImg.onload = function () {
			explore.init(exploreImg, wrapper);
			wrapper.addEventListener('click', function () {
				explore.go();
			}, false);
		};
	</script>

For more information: http://www.cnblogs.com/qieguo/

Demo
---

See it in action: http://qieguo2016.github.io/3d_bomb/

Screenshot
---

![atl="Screenshot"](https://github.com/qieguo2016/3d_bomb/blob/master/img/Screenshot.gif?raw=true)
