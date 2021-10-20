- Create a layout according to the design shown below.

![Backgrounds and gradient Assignment level 1](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/adding-media/ex-1.png)

- Video link: https://www.youtube.com/watch?v=AqcjdkPMPJA#action=share

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>adding media</title>
    <script src="https://kit.fontawesome.com/df2423167d.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="assets/style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com"> 
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> 
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;500&display=swap" rel="stylesheet">
</head>
<body>
    <section class="contianer section-one">
        <nav class="nav flex " >
            <p class="hydro"><b>Hydro</b></p>
            <ol class="flex nav-list">
                <li><a href="#">Home</a> </li>
                <li> <a href="#">About</a> </li>
                <li> <a href="#">Blog</a></li>
                <li> <a href="#">Our Work </a> </li>
                <li> <a href="#">Contact </a> </li>
            </ol>
            <ol class="icons flex">
                <a href="#"><i class="fab fa-facebook-square"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><button>Sign in/Join</button></a>

            </ol>

        </nav>
        <div class="flex">
            <h1>We make beautiful website for all people</h1>
            <button>start a project</button>
            <p>call us 834780038</p>
            <p>for any inquiry</p>

        </div>
        <figure class="flex">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/AqcjdkPMPJA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </figure>

    </section>
    <section class="section-two">
        <img src="/TA-STYLE-adding-media-THaaai-block-BHaacc/block-BHaacc/assets/about-image.jpg" alt="man">
    </section>
</body>
</html>





html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
} 

/* customised code  */
body{
    font-size: 16px;
    line-height: 1.5;
    font-family: 'Roboto', sans-serif;
    background-size: cover;
}
*,
*::before,
*::after{
    box-sizing: border-box;
}
.container{ 
    max-width: 1370px;
    margin: 0 auto;
    padding: 0 auto; 

} 

.flex{
    display: flex;
    justify-content: center;
    align-items: center;

}

.section-one{
   height: 900px;
    width: 100%;
    background: 
    linear-gradient(to left,aquamarine,rgb(37, 62, 146)),
    url(/TA-STYLE-adding-media-THaaai-block-BHaacc/block-BHaacc/assets/home-bg.jpg) center center no-repeat ;
}
.nav{
    margin: 0px ;
    justify-content: space-evenly;
    
}
a{
    text-decoration: none;
    margin: 11px;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: bold;
    font-size: 17px;
    color: white;
}
.hydro{
    font-size: 25px;
    color: white;
    margin: 26px 109px 25px 26px;
    font-weight: 1000;
}


