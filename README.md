
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title> X Player </title>
	 <meta property="og:url" content="https://player.xtsmm.com/" />  
	 <meta property="og:type" content="website" />  
	 <meta property="og:title" content="X Player" />  
	 <meta property="og:description" content="X Player Documentation" />  
	 <meta property="og:image" content="https://player.xtsmm.com/cover.png" />  
	<link rel="icon" type="image/png" href="https://cdn.xtsmm.com/admin_images%2Ffavicon.png"/>
   <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/uikit/3.5.9/css/uikit.min.css" crossorigin="anonymous" />
   
   
   <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>   
   <script src="https://cdnjs.cloudflare.com/ajax/libs/uikit/3.5.9/js/uikit.min.js" crossorigin="anonymous"></script>
   <script src="https://cdnjs.cloudflare.com/ajax/libs/uikit/3.5.9/js/uikit-icons.min.js" crossorigin="anonymous"></script>
   <style>
   dt{color:orange!important}
   .uk-modal-dialog{background:#222!important}
   </style>
</head>
<body class='uk-section-secondary' style='padding-bottom:100px'>

  <div class="uk-section uk-section-secondary uk-light">
    <div class="uk-container">

        <h3><img src='https://player.xtsmm.com/play.svg' style='height:40px;width:40px'/> X Player</h3>
        

    </div>
	<div class="uk-cover-container uk-height-large" style="margin:50px 0 50px 0">
    <video src="https://cdn.xtsmm.com/uploads/video/sample.mp4" autoplay loop muted playsinline uk-cover></video>
	
	</div>
	<div class="uk-container">

        <h3>X Player for Android - Documentation</h3>

        <div class="uk-grid-match uk-child-width-1-2@s" uk-grid>
            <div>
				<h2><span class="uk-label uk-primary">For Business</span></h2>
				<p>X Player offers Player Monetization by Google Ads.</p>
				<p>A simple process can make you revenue, a button in your app - open xPlayer with your Ads.</p>
                <table class="uk-table uk-table-divider">					
					<tbody>
						<tr>
							<td>Ad Impression %</td>
							<td>You get 80%</td>
						</tr>		
						<tr>
							<td>Ad Network</td>
							<td>Google Admob</td>
						</tr>
						<tr>
							<td>Ad Type</td>
							<td>Interstitial</td>
						</tr>
						<tr>
							<td>Any hidden % ?</td>
							<td>No, 80% is hardCoded in app.</td>
						</tr>
					</tbody>
				</table>
            </div>
            <div>
				<h2><span class="uk-label">For Developers</span></h2>
                <p>There is only one step to open your video on xPlayer.</p>
				<p>We also support user-Agent, 1 header key and 1 header value.</p>
<pre>
Intent intent = new Intent(Intent.ACTION_VIEW);
intent.setData(Uri.parse("xplayer://play?url=https://content.jwplatform.com/manifests/yp34SRmf.m3u8"));
intent.putExtra("userAgent","myAppUserAgentSecret");
intent.putExtra("headerKey","auth");
intent.putExtra("headerValue","authKey0001");
intent.putExtra("admobINT","ca-app-pub-3940256099942544/1033173712");
startActivity(intent);		
</pre>
<p>If your video is public, you can ignore extra intents. The most important line is <br/>'intent.setData(Uri.parse("xplayer://play?url=https://content.jwplatform.com/manifests/yp34SRmf.m3u8"));'</p>
<p>Set your video URL as parameter of url via xPlayer scheme.<br/>'xplayer://play?url='</p>
            </div>
            
        </div>

    </div>
</div>
<div class="privacy" uk-modal>
    <div class="uk-modal-dialog uk-modal-body">
        <h2 class="uk-modal-title">Privacy Policy</h2>        
		 <ul uk-accordion>
			<li>
				<a class="uk-accordion-title" href="#" style='color:greenyellow'>What we do not collect </a>
				<div class="uk-accordion-content">
					<dl class="uk-description-list">
						<dt>Your Private Information</dt>
						<dd>GPS , Locations , Gender , Interests , etc.</dd>
						<dt>Your Passwords</dt>						
						<dt>Clicks and Behaviours</dt>
						<dd>We do not detect your behaviors on our web/app .</dd>						
					</dl>
				</div>
			</li>
			
			<li>
				<a class="uk-accordion-title" href="#" style='color:greenyellow'>What we collect </a>
				<div class="uk-accordion-content">
					<dl class="uk-description-list">
						<dt>We use Google Analytics</dt>										
						<dt>We only collect app open events</dt>
					</dl>
				</div>
			</li>
			
			<li>
				<a class="uk-accordion-title" href="#" style='color:greenyellow'>Data Security </a>
				<div class="uk-accordion-content">
					<dl class="uk-description-list">
						<dt>Your Data are safe on our App</dt>										
						<dt>Our app is natural Player App and do not collect any information from your device </dt>
					</dl>
				</div>
			</li>
        <p class="uk-text-right">
            <button class="uk-button uk-button-default uk-modal-close" type="button">Cancel</button>
            <button class="uk-button uk-button-primary uk-modal-close" type="button">Continue</button>
        </p>
    </div>
</div>
<div class="uk-align-center" style='margin-bottom:5px;margin-top:100px' align=center>		
		<a href="https://www.facebook.com/xtsmm" target=_blank class="uk-icon-button  uk-margin-small-right" uk-icon="server" uk-tooltip="title:Technical Provider"></a>
		<a href="#" class="uk-icon-button  uk-margin-small-right" uk-icon="lock" uk-toggle="target: .privacy" uk-tooltip="title:Privacy Policy"></a>
		<a href="https://m.me/xtsmm" target=_blank class="uk-icon-button  uk-margin-small-right" uk-icon="question" uk-tooltip="title:Contact Us"></a>		
</div>	
</body>
