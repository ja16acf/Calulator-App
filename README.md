<!doctype html>
<html>
<head>
	<title>jQuery Mobile Page</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<meta name="apple-mobile-web-app-capable" content="yes" />

	<link rel="stylesheet" href="http://code.jquery.com/mobile/1.0.1/jquery.mobile-1.0.1.min.css" />
	<style> .dragimg {width:50px;height:50px}></style>
	<script src="http://code.jquery.com/jquery-1.6.4.min.js"></script>
	<script src="http://code.jquery.com/mobile/1.0.1/jquery.mobile-1.0.1.min.js"></script>
	<script src="http://code.jquery.com/ui/1.8.24/jquery-ui.min.js"></script>

  	<!-- (Start) Add jQuery UI Touch Punch -->
  	<script src="jquery.ui.touch-punch.min.js"></script>
  	<!-- (End) Add jQuery UI Touch Punch -->

</head>
<body>
<section data-role="page">
	<header data-role="header">
		<h4>Page header</h4>
	</header><!-- /header -->
	<div data-role="controlgroup" data-type="horizontal" style="text-align:center">
			<a class="num" data-role="button">0</a>
		        <a class="num" data-role="button">1</a>
			<a class="num" data-role="button">2</a>
                        <a class="num" data-role="button">3</a>
                        <a class="num" data-role="button">4</a>
                        <a class="num" data-role="button">5</a>
                        <a class="num" data-role="button">6</a>
                        <a class="num" data-role="button">7</a>
                        <a class="num" data-role="button">8</a>
                        <a class="num" data-role="button">9</a>
		</div>
		<div>
		<img class="dragimg" src="apple.png" alt="apple"/>
		<img class="dragimg" src="apple.png" alt="apple"/>
		<img class="dragimg" src="apple.png" alt="apple"/>
		<img class="dragimg" src="apple.png" alt="apple"/>
		<img class="dragimg" src="apple.png" alt="apple"/>
		<img class="dragimg" src="apple.png" alt="apple"/>
		<img class="dragimg" src="apple.png" alt="apple"/> 
		<img class="dragimg" src="apple.png" alt="apple"/>
                <img class="dragimg" src="apple.png" alt="apple"/>
		</div>
		<div id="plate">
		plate</br></br>
		</div>
	<footer data-role="footer">
		<h4>Page footer</h4>
	</footer><!-- /footer -->
</section><!-- /page -->
<script>


$(".num").click(function() {
            alert($(this).text());
        });

$(document).ready(function() {
$(".dragimg").draggable();
});

</script>
</body>
</html>
