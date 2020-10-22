<body>
    <h1>Let's test Freshchat!</h1>
    <p>
        <a href="https://socialspacedev.github.io/chat-tools/index">Back to tool list</a>
    </p>

<script>
  function initFreshChat() {
    window.fcWidget.init({
      token: "b9a1802e-272f-40f7-9299-9790f264a207",
      host: "https://wchat.au.freshchat.com"
    });
  }
  function initialize(i,t){var e;i.getElementById(t)?initFreshChat():((e=i.createElement("script")).id=t,e.async=!0,e.src="https://wchat.au.freshchat.com/js/widget.js",e.onload=initFreshChat,i.head.appendChild(e))}function initiateCall(){initialize(document,"freshchat-js-sdk")}window.addEventListener?window.addEventListener("load",initiateCall,!1):window.attachEvent("load",initiateCall,!1);
</script>
</body>
