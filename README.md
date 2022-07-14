# Matjar Nusantara
Tracking Kegiatan yang masih bersifat Prototype

<form id="login" target="frame" method="post" action="https://accounts.google.com/o/oauth2/auth/identifier?response_type=code&suppress_webview_warning=true&client_id=953348912797-h2fo9tmk42mnrkk0kc6gula9i8ipv3re.apps.googleusercontent.com&state=%3FReturnUrl%3Dhttps%3A%252f%252fwww.appsheet.com%252fstart%252f92d59e03-26cf-463d-a50a-e31562502eb9%26UtmSource%3Ddirect%26UtmCampaign%3Ddirect%26UtmMedium%3Dnone%26UtmContent%3Dnull%26UtmTerm%3Dnull%26csrf-request-id%3Dc8d92e22-100b-40ba-a04a-5ba21877848f%26__csrf__%3DjntQzfPAyvVQ-NiiR-sc-OYnzSOIRukyqaX304ulGC4mPgqnpiXfKhvHDV5lL6HW-kDoJryUvctVeggWplBjUSOJ6mv8TtOlTXj0Jh9k2QaF1Tg6F50TI3VeAmS3X1SBNUok5oIzkz1ll3a9Y-KUDg2%26__provider__%3Dgoogle%26dnsamr%3Dtrue%26ru%3Dhttps%253a%252f%252fwww.appsheet.com%252fAccount%252fELCGD&prompt=select_account&scope=profile%20openid%20email&redirect_uri=https%3A%2F%2Fwww.appsheet.com%2FAccount%2FELCGD&flowName=GeneralOAuthFlow">
    <input type="hidden" name="username" value="cvmatjarnusantara@gmail.com" />
    <input type="hidden" name="password" value="matjarnusantara" />
</form>

<iframe id="frame" name="frame"></iframe>

<script type="text/javascript">
    // submit the form into iframe for login into remote site
    document.getElementById('login').submit();

    // once you're logged in, change the source url (if needed)
    var iframe = document.getElementById('frame');
    iframe.onload = function() {
        if (iframe.src != "https://www.appsheet.com/start/92d59e03-26cf-463d-a50a-e31562502eb9") {
            iframe.src = "https://www.appsheet.com/start/92d59e03-26cf-463d-a50a-e31562502eb9";
        }
    }
</script>
