ChatGPT Mini Asistan - Server

Bu klasör, React tabanlı ChatGPT Mini Asistan projesinin backend (Node.js & Express) kısmını içerir. Kullanıcının gönderdiği soruları OpenAI API'ye iletir ve cevapları frontend'e döner.

Kurulum

Gerekli bağımlılıkları yükleyin:

npm install

.env dosyası oluşturun ve OpenAI API anahtarınızı ekleyin:

OPENAI_API_KEY=sk-...

Sunucuyu başlatın:

npm start

Sunucu başladığında http://localhost:5000 adresinde yayın yapar.

Kullanılan Teknolojiler

Node.js

Express

Axios

dotenv

cors
Endpoint

POST /api/chat

Body:

{
  "prompt": "Merhaba!"
}

OpenAI API'sinden gelen yanıt, frontend'e JSON formatında dönüer.
