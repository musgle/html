<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>

    <head>

        <title>Free Music Search powered by Google = Musgle</title>

		<meta http-equiv="content-type" content="text/html; charset=UTF-8">

		<meta name="description" content="Search freely and directly downladable music e.g. mp3, wma, wav, etc.. Give it a try!">
		<meta name="keywords" content="mp3, wma, wav, search+mp3, search+music">

		<script type="text/javascript" src="util/helper.js"></script>
			<script type="text/javascript">

			  var _gaq = _gaq || [];
			  _gaq.push(['_setAccount', 'UA-1806166-3']);
			  _gaq.push(['_trackPageview']);

			  (function() {
				var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
				ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
				var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
			  })();

			</script>
		<link rel="stylesheet" title="compact" href="style/musgle.css" type="text/css">

    </head>

	<body onload="setFocus();">
        <center>
            <div id="theboss">            	
	            <a href="http://www.musgle.com">
					<img alt="Musgle" src="img/musgle-logo.png" height=148 width=342>
	            </a>
				<br>
					<form name="mform" method="post" action="util/callgoogle.php">
						<table>
							<tr valign="top">
								<td align="center" nowrap>
									<input maxlength="2048" name="musearch" size="55">
									<br>
									<input type="submit" value="Search Music">
								</td>
							</tr>
						</table>
					</form>
	            <br>
	            <br>
                <div id="showaboutlink">                                       
                    <font size=-1>                                             
                        <a href="#"                                            
                           onClick="showAbout();">                             
                            About Musgle                                       
                        </a>                                                   
                    </font>                                                    
                </div>                                                         
                <div id="hideaboutlink">                                       
                    <font size=-1>                                             
                        <a href="#"                                            
                           onClick="hideAbout();">                             
                            Hide About Musgle                                  
                        </a>                                                   
                    </font>                                                    
                </div>                  
	            <p>
	                <font size=-2>
	                    &copy;2011 Musgle
	                </font>
	            </p>
			</div>
			<div id="about">
				<p>
					&nbsp;&nbsp;Musgle originates from the idea of combining words 
					<b>Mus</b>ic and <a href="http://www.google.com">Goo<b>gle</b></a>.
					The idea is simple yet very powerful. To see Musgle in action just type a song title, or the artist name, or both 
                    in a search bar and hit 'Enter' - you will be redirected to the Google page with relevant search results.
                    Click on one of those results, and you will have a chance to directly download the song you are searching for
                    - very smooth! <br><br>
					&nbsp;&nbsp;Although Musgle is not affiliated with Google, ALL its strength comes from it :)
                    When searching for any kind of music (mp3, wma, wav, etc), Musgle calls Google for help by submitting a special 
                    search query to it, which is based on 
						<a href="http://www.google.com/help/operators.html">Advanced Google Search Operators</a>.
					After Google does its hard work, it returns results with direct links to mp3, wma, wav, etc.. music files 
                    that can be downloaded directly with no hassle!<br><br>
                    Good Luck!
				</p>
			</div>
        </center>
		
	<!--   -->
	<div style="display:none">
			</div>
	<!--   -->
    </body>
</html>

