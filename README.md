# Matjar Nusantara
Tracking Kegiatan yang masih bersifat Prototype

<form id="login" target="frame" method="post" action="https://accounts.google.com/signin/v2/identifier?">
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
