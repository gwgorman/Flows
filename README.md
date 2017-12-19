# Flows
Collections of node-RED flows that I use during demos and other goodies

 	ChatbotWithTranslation.json - This flow wrappers Watson Conversation, using the sample Car chatbot. It illustrates how to locate an entity and what action it needs done on it. It also detects your input language and translates the output on-the-fly to match your input language. You can use a different language each time you type and Watson will reply to you in that language. 
 
	TakePhotoOnCommandFromWIoT.json - This flow illustrates how to react to a command from IBM Cloud via Watsion IoT Platform and send a reply. This is meant to be runninng on a Raspberry Pi with a camera that is already registered with IoT Platform. It looks for a 'take photo' command, grabs a picture from the Pi camera, formats it and sends it via MQTT back to the IBM Cloud. 
  
	TalkingTJBot.json - This is my implementation of a fun talking TJBot. It uses multiple services for speech and text, weather and image processing to respond to various voice commands. Key component is the use of Snowboy for 'wake word' detection. A simple Switch statement looking for key words is used to determine which desired command to run. 
