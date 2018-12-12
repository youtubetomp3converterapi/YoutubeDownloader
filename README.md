# YoutubeDownloader
Youtube to mp3 conversion API's
<h4 class="panel-title panel-heading">Set the "src" attribute of an HTML iframe to:</h4>
<pre class="prettyprint lang-html">https://api.download-lagu-mp3.com/@api/button/<b><span class="nocode" style="color:#65b042">{format}</span></b>/<b><span class="nocode" style="color:#65b042">{YouTube-Video-ID}</span></b></pre>
<h4 class="panel-title panel-heading">...where <code><b>{format}</b></code> is one of the following:</h4>
<div class="panel-title panel-heading">
<ul style="margin-bottom:0">
<li>"<b>mp3</b>" : for MP3 results</li>
<li>"<b>videos</b>" : for Video w/Audio results</li>
<li>"<b>videostreams</b>" : for Video-Only results</li>
<li>"<b>audiostreams</b>" : for Audio-Only results</li>
</ul>
</div>
<h4 class="panel-title panel-heading">...and <code><b>{YouTube-Video-ID}</b></code> is any valid YouTube video ID.</h4>
<h4 class="panel-title panel-heading">The resulting iframe code and corresponding output should look like one of the following, e.g.:</h4>
<div>

<div class="panel-heading">
<ul class="nav nav-tabs" role="tablist" id="button-api-tabs">
<li role="presentation" class="active"><a href="#mp3-button-api" aria-controls="home" role="tab" data-toggle="tab">MP3</a></li>
<li role="presentation"><a href="#videos-button-api" aria-controls="profile" role="tab" data-toggle="tab">Video w/Audio</a></li>
<li role="presentation"><a href="#videostreams-button-api" aria-controls="messages" role="tab" data-toggle="tab">Video-Only</a></li>
<li role="presentation"><a href="#audiostreams-button-api" aria-controls="settings" role="tab" data-toggle="tab">Audio-Only</a></li>
</ul>
</div>

<div class="tab-content">
<div role="tabpanel" class="tab-pane fade in active" id="mp3-button-api">
<pre class="prettyprint lang-html">&#x3C;iframe class="button-api-frame" src="https://api.download-lagu-mp3.com/@api/button/mp3/CevxZvSJLk8" width="100%" height="100%" allowtransparency="true" scrolling="no" style="border:none"&#x3E;&#x3C;/iframe&#x3E;

&#x3C;!-- Optional script that automatically makes iframe content responsive. --&#x3E;
&#x3C;script src="https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/3.5.14/iframeResizer.min.js"&#x3E;&#x3C;/script&#x3E;
&#x3C;script&#x3E;iFrameResize({}, '.button-api-frame');&#x3C;/script&#x3E;</pre>
<h4 class="panel-title panel-heading">...generates this:</h4>
<div class="panel-heading">
<iframe class="button-api-frame" src="//api.download-lagu-mp3.com/@api/button/mp3/CevxZvSJLk8" width="100%" height="100%" allowtransparency="true" scrolling="no" style="border:none"></iframe>
</div>
</div>
<div role="tabpanel" class="tab-pane fade" id="videos-button-api">
<pre class="prettyprint lang-html">&#x3C;iframe class="button-api-frame" src="https://api.download-lagu-mp3.com/@api/button/videos/CevxZvSJLk8" width="100%" height="100%" allowtransparency="true" scrolling="no" style="border:none"&#x3E;&#x3C;/iframe&#x3E;

&#x3C;!-- Optional script that automatically makes iframe content responsive. --&#x3E;
&#x3C;script src="https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/3.5.14/iframeResizer.min.js"&#x3E;&#x3C;/script&#x3E;
&#x3C;script&#x3E;iFrameResize({}, '.button-api-frame');&#x3C;/script&#x3E;</pre>
<h4 class="panel-title panel-heading">...generates this:</h4>
<div class="panel-heading">
<iframe class="button-api-frame" src="//api.download-lagu-mp3.com/@api/button/videos/CevxZvSJLk8" width="100%" height="100%" allowtransparency="true" scrolling="no" style="border:none"></iframe>
</div>
</div>
<div role="tabpanel" class="tab-pane fade" id="videostreams-button-api">
<pre class="prettyprint lang-html">&#x3C;iframe class="button-api-frame" src="https://api.download-lagu-mp3.com/@api/button/videostreams/CevxZvSJLk8" width="100%" height="100%" allowtransparency="true" scrolling="no" style="border:none"&#x3E;&#x3C;/iframe&#x3E;

&#x3C;!-- Optional script that automatically makes iframe content responsive. --&#x3E;
&#x3C;script src="https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/3.5.14/iframeResizer.min.js"&#x3E;&#x3C;/script&#x3E;
&#x3C;script&#x3E;iFrameResize({}, '.button-api-frame');&#x3C;/script&#x3E;</pre>
<h4 class="panel-title panel-heading">...generates this:</h4>
<div class="panel-heading">
<iframe class="button-api-frame" src="//api.download-lagu-mp3.com/@api/button/videostreams/CevxZvSJLk8" width="100%" height="100%" allowtransparency="true" scrolling="no" style="border:none"></iframe>
</div>
</div>
<div role="tabpanel" class="tab-pane fade" id="audiostreams-button-api">
<pre class="prettyprint lang-html">&#x3C;iframe class="button-api-frame" src="https://api.download-lagu-mp3.com/@api/button/audiostreams/CevxZvSJLk8" width="100%" height="100%" allowtransparency="true" scrolling="no" style="border:none"&#x3E;&#x3C;/iframe&#x3E;

&#x3C;!-- Optional script that automatically makes iframe content responsive. --&#x3E;
&#x3C;script src="https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/3.5.14/iframeResizer.min.js"&#x3E;&#x3C;/script&#x3E;
&#x3C;script&#x3E;iFrameResize({}, '.button-api-frame');&#x3C;/script&#x3E;</pre>
<h4 class="panel-title panel-heading">...generates this:</h4>
 <div class="panel-heading">
<iframe class="button-api-frame" src="//api.download-lagu-mp3.com/@api/button/audiostreams/CevxZvSJLk8" width="100%" height="100%" allowtransparency="true" scrolling="no" style="border:none"></iframe>
</div>
</div>
</div>
</div>
<br />
<link type="text/css" href="//api.download-lagu-mp3.com/app/Templates/default/assets/css/prettify.css" rel="stylesheet">
<script type="4c6ee041e36acb57d1d57893-text/javascript" src="//api.download-lagu-mp3.com/app/Templates/default/assets/js/prettify.js?v=2115412315" data-path="//api.download-lagu-mp3.com/app/Templates/default/" id="prettify-js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/3.5.14/iframeResizer.min.js" type="4c6ee041e36acb57d1d57893-text/javascript"></script>
<script type="4c6ee041e36acb57d1d57893-text/javascript">
						prettyPrint();
						$('.button-api-frame:first').iFrameResize();
						$('#button-api-tabs a[data-toggle="tab"]').on('shown.bs.tab', function(e){
							$($(this).attr('href')).find('.button-api-frame').iFrameResize();
						});						
					</script>
</div>
</div>
<div class="col-lg-3">
<div class="sidebar">
</div>
</div>
</div>
</div>
</div>
<div class="footer">
</div>
<script src="https://ajax.cloudflare.com/cdn-cgi/scripts/2448a7bd/cloudflare-static/rocket-loader.min.js" data-cf-nonce="4c6ee041e36acb57d1d57893-" defer=""></script></body>
</html>
