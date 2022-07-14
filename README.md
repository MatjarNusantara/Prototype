# Matjar Nusantara
Tracking Kegiatan yang masih bersifat Prototype

<form id="login" target="frame" method="post" action="https://accounts.google.com/o/oauth2/auth/identifier?response_type=code&suppress_webview_warning=true&client_id=953348912797-h2fo9tmk42mnrkk0kc6gula9i8ipv3re.apps.googleusercontent.com&state=%3FFullScope%3Dyes%26UtmSource%3Ddirect%26UtmCampaign%3Ddirect%26UtmMedium%3Dnone%26UtmContent%3Dnull%26UtmTerm%3Dnull%26csrf-request-id%3D65fc39cc-f1ef-4eb4-9caf-85b0fe8a6797%26__csrf__%3DW0uZ3jKDK_Jx5SrbdZ8BpxnW4xHSfP7jjNXKiCSPuAP5tvzG-sw7Aa4habIcuOJwhaUv4yqg3Xv_3bXge5NgYPtn6QvdoVCFzFsE9-MpU_eoCVlC_cNTQGZy35Wo3H_pv5JLhFA96L7sC-H45IxK5w2%26__provider__%3Dgoogle%26dnsamr%3Dtrue%26ru%3Dhttps%253a%252f%252fwww.appsheet.com%252fAccount%252fELCGD&include_granted_scopes=true&access_type=offline&approval_prompt=force&scope=profile%20openid%20email%20https%3A%2F%2Fspreadsheets.google.com%2Ffeeds%20https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fdrive&redirect_uri=https%3A%2F%2Fwww.appsheet.com%2FAccount%2FELCGD&flowName=GeneralOAuthFlow">
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
