# hello_world
my first repository
first one
<!DOCTYPE html>
<!-- include aframe -->

<script src="vendor/aframe/build/aframe.js"></script>
<!-- include aframe-ar.js -->

<script src="../build/aframe-ar.js"></script>

<body style='margin : 0px; overflow: hidden; font-family: Monospace;'><div style='position: fixed; top: 10px; width:100%; text-align: center; z-index: 1;'>
	<a href="https://github.com/jeromeetienne/AR.js/" target="_blank">AR.js</a> - mobile performance in a-frame
	<br/>
	
</div>
	
	<a-scene stats embedded arjs='sourceType: webcam; detectionMode: mono; maxDetectionRate: 30; canvasWidth: 240; canvasHeight: 180'>

		

		<a-box position='0 0.5 0' material='opacity: 0.5; side: double'>
			<a-torus-knot radius='0.26' radius-tubular='0.05'
			animation="property: rotation; to:360 0 0; dur: 5000; easing: linear; loop: true">
			</a-torus-knot>
		</a-box>

		<a-marker-camera type='pattern' patternUrl=''></a-marker-camera>
	</a-scene>
</body>
</html>
