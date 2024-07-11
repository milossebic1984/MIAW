<html>
	"AAAAAAA"
<head>	<link rel="shortcut icon" href="#">
<meta http-equiv="Content-Security-Policy" content="default-src 'self'">
</head>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DQy000009kEil',
				'HSE_Chat',
				'https://mindful-otter-lvxcmc-dev-ed.trailblaze.my.site.com/ESWHSEChat1720437267411',
				{
					scrt2URL: 'https://mindful-otter-lvxcmc-dev-ed.trailblaze.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://mindful-otter-lvxcmc-dev-ed.trailblaze.my.site.com/ESWHSEChat1720437267411/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
