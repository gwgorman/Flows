# Flows
Collections of node-RED flows that I use during demos and other goodies
<p>
<b>ChatbotWithTranslation.json</b> - This Node-RED flow is an example of how to use IBM Watson Conversation, using the sample Car chatbot. It illustrates how to locate an entity and what action it needs done on it. There is a Node-RED Dashboard that lets you interact with the chatbot, and an indicator to show if the Windshield Wipers are "on" or "off". 
</p>
<p>
The flow also detects your input language and translates the output on-the-fly to match your input language using the IBM Watson Translation Services. You can use a different language each time you type and Watson will reply to you in that language. This is very much just an example and will fail if you use a non-supported language (supported ones are listed in the Documentation on the IBM Cloud site).
</p>
<p> 
<b>TakePhotoOnCommandFromWIoT.json</b> - This flow illustrates how to react to a command from IBM Cloud via Watsion IoT Platform and send a reply. This is meant to be runninng on a Raspberry Pi with a camera that is already registered with IoT Platform. It looks for a 'take photo' command, grabs a picture from the Pi camera, formats it and sends it via MQTT back to the IBM Cloud. 
</p>
<p>
<b>TalkingTJBot.json</b> - This is my implementation of a fun talking TJBot. It uses multiple IBM Watson services for speech and text, IBM Weather Company interfaces and IBM Watson image analytics to respond to various voice commands. Key component is the use of Snowboy for 'wake word' detection. A simple Switch statement looking for key words is used to determine which desired command to run. Future versions will use IBM Watson Conversation services. 
</p>
<p>
  <b>LewisvileLakeInfo.json</b> - This flow connects to USGS real time data and displays information about Lewisville Lake, TX on a Node-RED dashboard. I also show how to store and retrieve history for the Chart widget, as well as process an array. I also show how to change a Button's color and icon (h/t @dceejay) to show 3-value data and collect a trend for the lake level. Even put in a little JSONata trick to calculate the line slope.... 
  </p>
  
