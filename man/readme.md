<script>
    if (navigator.appName == "Netscape") {
        var language = navigator.language;
    } else {
        var language = navigator.browserLanguage;
    }
    if (language.indexOf("en") > -1) {
        document.location.href = "en-us";
    } else if (language.indexOf("zh") > -1) {
        document.location.href = "zh-cn";
    } else {
        document.location.href = "en-us";
    }
</script>
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-111463289-1"></script>
<script>
    window.dataLayer = window.dataLayer || [];

    function gtag() {
        dataLayer.push(arguments);
    }
    gtag('js', new Date());

    gtag('config', 'UA-111463289-1');
</script>
