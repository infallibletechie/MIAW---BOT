<html>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00Dau000002ItPt',
				'MIAW_BOT',
				'https://infallibletechiemiaworg.my.site.com/ESWMIAWBOT1720541829743',
				{
					scrt2URL: 'https://infallibletechiemiaworg.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://infallibletechiemiaworg.my.site.com/ESWMIAWBOT1720541829743/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</html>
