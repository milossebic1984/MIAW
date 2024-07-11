<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00Dao00000RAenx',
				'HSE_Test_Chat',
				'https://ag1720511005272.my.site.com/ESWHSETestChat1720679993301',
				{
					scrt2URL: 'https://ag1720511005272.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://ag1720511005272.my.site.com/ESWHSETestChat1720679993301/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>


</body>
</html>
