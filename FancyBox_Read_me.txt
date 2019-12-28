HOW TO USE FancyBOX
>>>>>>>>>Nitesh<<<<<<<<<<<<<<<

1)First download the fancybox from link:-
	  https://fancyapps.com/fancybox/3/
    
    Extract it, And open dist folder 

2)Copy following files from dist folder to your working dir:-
	 i)  jquery.fancybox.min.css -> (css)
	ii) jquery.fancybox.min.js  -> (js)
  
3) download:- Jquerry (latest)
	  https://code.jquery.com/jquery-3.4.1.js
    //devloper or compressed any   >>> copy the code to new js file in my case it is
    iii) "jQ.js" -> (jquery)

3) link these i)css , ii)js and iii)jquery file to your html page like shown:-

	<!DOCTYPE html>
	<html lang="en">

	<head>
  		<meta charset="UTF-8">
  		<meta name="viewport" content="width=device-width, initial-scale=1.0">
 	 	<link rel="stylesheet" href="CSS/jquery.fancybox.min.css">     //  i) fancyBox file 
  		<meta http-equiv="X-UA-Compatible" content="ie=edge">
  		<title>Fancy Box</title>
	</head>

	<body>

 		 <a data-fancybox="gallery" href="This_image_will_pop_up.jpg"><img src="this _image_will_show.jpg"></a>



  		<script src="Js/jQ.js"></script>  //jquery lattest version
  		<script src="Js/jquery.fancybox.min.js"></script> //  ii) fancyBox file 
	</body>
</html>
