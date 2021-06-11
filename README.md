# whatsapp-chat-floating


# requirement
 - jQuery

# example setup
<script>
var url = "link/to/whatsapp.js'";
var s = document.createElement('script');
s.type = 'text/javascript';
s.async = true;
s.src = url;
var options = {
    "enabled":true,
    "chat":{
        "backgroundColor":"#3699ff",
        "ctaText":"Butuh Bantuan ?",
        "borderRadius":"25",
        "marginLeft":"0",
        "marginBottom":"50",
        "marginRight":"50",
        "position":"right"
    },
    "brand":{
        "brandName":'Codeinaja',
        "brandSubTitle":'Ada yang bisa dibantu?',
        "brandImg":"link/to/logo.png",
        "welcomeText":"Hai ,\nAda yang bisa kami bantu ?",
        "messageText":"",
    }
};
s.onload = function() {
    CreateWhatsappChatWidget(options);
};
var x = document.getElementsByTagName('script')[0];
x.parentNode.insertBefore(s, x);
</script>
