# Simple-ai-chatbot
#A chat bot you can run in the browser. It uses Open AI's API to generate responses.
#html chat box Ui

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AI Chatbot</title>
  <style>
    body { font-family: Arial; background: #fce4ec; padding: 2em; }
    .chat-box { max-width: 500px; margin: auto; border: 1px solid #ccc; border-radius: 8px; padding: 1em; background: white; }
    .messages { max-height: 300px; overflow-y: auto; margin-bottom: 1em; }
    .message { margin: 0.5em 0; }
    .user { text-align: right; color: hotpink; }
    .bot { text-align: left; color: #555; }
  </style>
</head>
<body>
  <div class="chat-box">
    <div class="messages" id="messages"></div>
    <input type="text" id="userInput" placeholder="Say something..." style="width: 80%;" />
    <button onclick="sendMessage()">Send</button>
  </div>

  <script src="chatbot.js"></script>
</body>
</html>
