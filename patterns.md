# Patterns

<!-- Back to top button -->
<a id="button"></a>

<p><a class= 'bookMark' id='hoverttl' href="#ttl-color">Headline</a> <a class= 'bookMark' id='hoverlead' href="#lead-color">News lead</a> <a class= 'bookMark' id='hoverdataSrc' href="#dataSrc-color">Data Source</a> <a class= 'bookMark' id='hovernarrDvc' href="#narrDvc-color">Narrative</a> <a class= 'bookMark' id='hoverim' href="#im-color">Image</a> <a class= 'bookMark' id='hovervisTtl' href="#visTtl-color">Visualization Title</a> <a class= 'bookMark' id='hovervisTech' href="#visTech-color">Visualization Technique</a> <a class= 'bookMark' id='hovervisCap' href="#visCap-color">Visualization Caption</a> <a class= 'bookMark' id='hovervisAnno' href="#visAnno-color">Visualization Annotation</a> <a class= 'bookMark' id='hoverinter' href="#inter-color">Visualization Interaction</a> <a class= 'bookMark' id='hovervi' href="#vi-color">Video</a></p>

  
<h2 class='secTitleBanner' id='ttl-color'>Headline</h2>

<table id="ttl" class="designpatterns">
</table>


<h2 class='secTitleBanner' id='lead-color'>News lead</h2>

<table id="lead" class="designpatterns">
</table>


<h2 class='secTitleBanner' id='dataSrc-color'>Data Source</h2>

<table id="dataSource" class="designpatterns">
</table>

<h2 class='secTitleBanner' id='narrDvc-color'>Narrative</h2>

<table id="narrativeDevice" class="designpatterns">
</table>

<h2 class='secTitleBanner' id='im-color'>Image</h2>

<table id="image" class="designpatterns">
</table>

<h2 class='secTitleBanner' id='visTtl-color'>Visualization Title</h2>

<table id="visTitle" class="designpatterns">
</table>



<h2 class='secTitleBanner' id='visTech-color'>Visualization Technique</h2>

<table id="visTech" class="designpatterns">
</table>



<h2 class='secTitleBanner' id='visCap-color'>Visualization Caption</h2>

<table id="visCaption" class="designpatterns">
</table>


<h2 class='secTitleBanner' id='visAnno-color'>Visualization Annotation</h2>

<table id="visAnnotation" class="designpatterns">
</table>



<h2 class='secTitleBanner' id='inter-color'>Visualization Interaction</h2>

<table id="inter" class="designpatterns">
</table>


<h2 class='secTitleBanner' id='vi-color'>Video</h2>

<table id="video" class="designpatterns">
</table>


## Download Pattern Cards

[(CC BY-NC-ND)](https://creativecommons.org/licenses/by-nc-nd/4.0/)


<script>
  var btn = $('#button');

$(window).scroll(function() {
  if ($(window).scrollTop() > 300) {
    btn.addClass('show');
  } else {
    btn.removeClass('show');
  }
});

btn.on('click', function(e) {
  e.preventDefault();
  $('html, body').animate({scrollTop:0}, '300');
});

  </script>
