# mega2
Shaping up to be a big project. It's to become a souped up blog designed to get high traffic from expats and travelers going to and living in Chiang Mai Thailand...just to start
<!DOCTYPE html>
<html lang="en">
<head>

<title>Project Mega Site</title>
    <meta http-equiv="content-type" content="text/html"; charset="utf-8">
    <meta name="description" content="#">
    <meta name="robots" content="index,follow">
    <meta name="keywords" content="#">
    <meta http-equiv="X-UA-COMPATIBLE" content="IE=edge, chrome=1"><!---makes the site animated-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"><!--makes site responsive-->


    <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css"><!--link to bootstrap-->
    <link rel="stylesheet" href="http://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.6.3/css/font-awesome.min.css"><!--font awsome icons-->
    <link href='http://fonts.googleapis.com/css?family=Source+Sans+Pro:300' rel="stylesheet" type="text/css"><!--google fonts-->
    <link href="https://fonts.googleapis.com/css?family=Dosis|Suez+One|Trirong:500" rel="stylesheet">
    <link href='https://fonts.googleapis.com/css?family=Orbitron:400,900,700,500|Acme' rel='stylesheet' type='text/css'>
    <link href="https://fonts.googleapis.com/css?family=Dosis" rel="stylesheet">
    <link href='https://fonts.googleapis.com/css?family=Slabo+27px' rel='stylesheet' type='text/css'>
    <link rel="stylesheet" href="1140.css"><!--might want to take out-->
    <link rel="stylesheet" href="css/mega.css" type="text/css">
    <link rel="stylesheet" href="css/#.css" type="text/css">
    <link rel="stylesheet" href="css/#.css" type="text/css">


    <!--jquery link-->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script><!--links jquery find other options-->


    <!--js sliding effect for menu-->
    <script>
    $(function() {
      $('.nav-toggle, #nav-toggle').on('click', function(){
        $('.main-navigation, .page-wrap').toggleClass('open');
      });
    });
    </script>


    <!--sliding searchbox-->
    <script>
      jQuery(function($){
        $('#search-trigger').click(function(){
          $('#search-input').toggleClass('search-input-open');
        });

        $(document).click(function(e){
          if(!$(e.target).closest('.ngen-search-form').length){
            $('#search-input').removeClass('search-input-open');
          }
        })
      })
    </script>


    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script><!--links jquery find other options-->

<!--js pushing effect for menu-->
<script>
$(function() {
  $('.nav-toggle').on('click', function(){
    $('.wrapper').toggleClass('open');
  });
});


</script>
  </head>



<body class="body-wrap">
 <div class="page-wrap">
 <div class="outer-wrapper">
 <div class="wrapper">
  <!--top header section-->

  <!--toggle menu-->


<!-- toggle slide menu responsive-->
 <div class="slide-nav">
    <i class="fa fa-bars nav-toggle"></i>
       <nav class="main-navigation" role="navigation">
         <span class="nav-toggle" id="nav-toggle"><i class="fa fa-times"></i></span>



      <!--searchbox inside the responsive sliding menu-->
                 <div class="toggle_searchbox">
                   <div class="inside_toggle_searchbox">
                     <form method="get" class="searchform" action="#">
                       <fieldset id="fieldset">
                         <input type="text" name="s" class="s" value placeholder="Search">
                         <button class="fa fa-search search-button" type="submit" value="Search"></button>
                       </fieldset>
                     </form>
                   </div>
                 </div>
      <!--end of searchbox inside the responsive sliding menu--> 




  <!--dropdown menu in the sliding side menu-->
    <ul class="slide-menu">
      <li><a href="#"><i class="fa fa-home"></i>Home</a></li>
      <li><a href="#">Post Formats</a>
                   <ul>
                    <li><a href="#">Format 1</a></li>
                    <li><a href="#">Format 2</a></li>
                    <li><a href="#">Format 3</a></li>
                    <li><a href="#">Format 4</a></li>
                   </ul>
      </li>


      <li><a href="#">Locations</a>
                   <ul>
                    <li><a href="#">South East Asia</a></li>
                    <li><a href="#">Thailand</a>
                           <ul>
                            <li><a href="#">Bangkok</a></li>
                            <li><a href="#">Koh Samui</a></li>
                            <li><a href="#">Chiang Mai</a></li>
                            <li><a href="#">The Shopping</a></li>
                            <li><a href="#">The City</a></li>
                            <li><a href="#">The Food</a></li>
                           </ul> 
                    </li>
                    <li><a href="#">Cambodia</a></li>
                    <li><a href="#">Malaysia</a></li>
                    <li><a href="#">Indonesia</a></li>
                   </ul> 
      </li>


      <li><a href="#">Blog</a></li>
      <li><a href="#">About Us</a></li>
      <li><a href="#">Contact</a>
                   <ul>
                    <li><a href="#">Email</a></li>
                    <li><a href="#">Call</a></li>
                    <li><a href="#">Facebook</a></li>
                   </ul>
      </li>
    </ul>
   </nav>
  </div><!--for slide-nav-->
  <!--end of dropdown inside sliding side menu-->
       
  <!--end of toggle menu hidden on full screen-->



  <!--topbar nav header-->

  <header class="top-header">
    <nav class="top-menu" id="menu-1">


  <!--topbar links on the left side-->
       <div class="top-left-menu">
         <ul class="left-side">
           <li class="current" id="current"><a href="#" class="">Home</a></li>
           <li id="archive"><a href="#" class=""><i class="fa fa-archive"></i>Archive</a></li>
           <li class="right-border" id="right-border"><a href="#" class=""><i class="fa fa-user"></i>Author Page</a></li>
         </ul>
       </div>
  <!--end of left side topbar links-->
       


  <!--topbar social media icon links-->
        <div class="top-social-form">
        <div class="top-social">
          <ul id="top-social">
            <li><a href="#" class="facebook"><i class="fa fa-facebook"></i></a></li>
            <li><a href="#" class="twitter"><i class="fa fa-twitter"></i></a></li>
            <li><a href="#" class="google-plus"><i class="fa fa-google-plus"></i></a></li>
          </ul>
        </div>
  <!--end of topbar social media icon links-->
        


  <!--topbar searchbox-->
          <div class="form">
            <form action="#" class="form-search ngen-search-form" method="get">
              <input type="text" name="q" id="search-input" class="form-search-input" placeholder="Search Now" dir="rtl">
              <span id="search-trigger" class="form-search-submit"><i class="fa fa-search" aria-hidden="true"></i>
              </span>
            </form>
          </div>
  <!--end of topbar searchbox-->        


        </div>
     </nav>
   </header>
  <!--end of top header-->




  <!--bottom-header logo-->
    <div class="header clearfix">
      <div class="container">
        <div class="logo-wrap">
          <div id="logo" class="uppercase">
            <a href="#">
              <img src="images/logo3.png" alt="" width="470" height="auto">
            </a>
          </div>
        </div>
              <hr style="width: 100%;">
      </div>
    </div>
  <!--end of logo-->    




  <!--full screen dropdown menu-->

	<nav class="menu">
    <ul>
      <li class="active"><a href="#">Home</a></li>
      <li><a href="#">Post Formats</a>
            	<ul>
                	<li><a href="#">Format 1</a></li>
                  <li><a href="#">Format 1</a></li>
                  <li><a href="#">Format 2</a></li>
                  <li><a href="#">Format 3</a></li>
              </ul>
      </li>


      <li><a href="#">Locations</a>
            	<ul class="no-decoration">
                <li><a href="#">South East Asia</a></li>
                <li><a href="#">Thailand<span>+</span></a>
                    	<ul>
                        	<li><a href="#">Bangkok</a></li>
                          <li><a href="#">Koh Samui</a></li>
                          <li><a href="#">Chiang Mai<span>+</span></a>
                            	  <ul>
                                    <li><a href="#">The Shopping</a></li>
                            		    <li><a href="#">The City</a></li>
                            		    <li><a href="#">The Food</a></li>
                                </ul>
                          </li>
                          <li><a href="#">Koa Lok</a></li>
                      </ul>
                </li>
                <li><a href="#">Cambodia</a></li>
                <li><a href="#">Malaysia</a>
                      <ul>
                          <li><a href="#">Kuala Lumpar</a></li>
                      </ul>
                </li>
                <li><a href="#">Indonedia</a>
                      <ul>
                          <li><a href="#">Bali, Ubud</a></li>
                      </ul>
                </li>
              </ul>
      </li>


      <li><a href="#">Blog</a></li>
      <li><a href="#">About us</a></li>
      <li><a href="#">Contact</a>
          <ul>
              <li><a href="#">Email</a></li>
              <li><a href="#">Call</a></li>
              <li><a href="#">Facebook</a></li>
          </ul>
      </li>
    </ul>
  </nav>
  <!--end of full screen dropdown menu-->




  </div>
  </div>
  </div><!--page-wrap-->
 </body>
</html>
