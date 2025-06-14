# LINE Chatbot x Gemini Multimodal
Building a LINE Chatbot for user chatting with a PDF, Image, Video, and Audio files by Gemini and Cloud Functions for Firebase 

## Prerequisites
* [Node.js v20](https://nodejs.org) or higher
* Create a channel and copy the channel access token from [LINE Developers console](https://developers.line.biz/en/docs/messaging-api/getting-started/)
* Create a Firebase project using the [Firebase Console](https://console.firebase.google.com) and select <b>Blaze plan</b>
* Create an API key from [Google AI Studio](https://aistudio.google.com/app/apikey)

## Environment variables
Copy credentials and set them in a `.env` file in the `functions` directory
```
CHANNEL_ACCESS_TOKEN=CHANNEL-ACCESS-TOKEN-OF-LINE-MESSAGING-API
API_KEY=API-KEY-FROM-GOOGLE-AI-STUDIO
```

## Documentation
* [LINE Messaging API](https://developers.line.biz/en/docs/messaging-api/overview)
* [Cloud Functions for Firebase](https://firebase.google.com/docs/functions/get-started)
* [Gemini Developer API](https://ai.google.dev/gemini-api/docs/quickstart)

## Blog (Thai Language)
[สร้าง LINE Chatbot ให้เข้าใจ PDF, Image, Video และ Audio ที่ผู้ใช้ส่งเข้ามา ด้วย Gemini และ Cloud Functions](https://medium.com/linedevth/b4e4f31fa9bc)

## Example
![สร้าง LINE Chatbot ให้เข้าใจ PDF, Image, Video และ Audio ที่ผู้ใช้ส่งเข้ามา ด้วย Gemini และ Cloud Functions](https://github.com/user-attachments/assets/e22bde0e-4517-4955-b041-085d1ab7ba4f)
