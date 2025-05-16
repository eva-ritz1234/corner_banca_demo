#Cornèr Banca Demo
<html lang="en-US">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <img src = "webpage2.png"
    	width="auto" height="auto"
         alt = "New Watson Assistant Bank" />

</head>

<script>
  window.watsonAssistantChatOptions = {
    integrationID: "5282c5dc-0605-429e-90d5-3dc84005fc29", // The ID of this integration.
    region: "aws-us-east-1", // The region your integration is hosted in.
    serviceInstanceID: "20240201-1635-4978-90fa-ee7eb719d913", // The ID of your service instance.
    onLoad: async (instance) => { await instance.render(); }
  };
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js";
    document.head.appendChild(t);
  });
</script>

<body></body>

</html>
