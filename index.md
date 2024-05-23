<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DHp000005Zqgm',
				'Connexus_Github_Bot',
				'https://ph1716378320381.my.site.com/ESWConnexusGithubBot1716492710252',
				{
					scrt2URL: 'https://ph1716378320381.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://ph1716378320381.my.site.com/ESWConnexusGithubBot1716492710252/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
