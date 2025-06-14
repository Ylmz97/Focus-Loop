# Focus Loop

Focus Loop, odaklanma problemleri yaşayan bireyler için geliştirilmiş bir mobil odak uygulamasıdır.
Canlı Pomodoro odaları, görev takibi, hedef belirleme ve başarı ödülleri sistemi içerir.

## Teknolojiler
- Backend: Node.js, Express.js, PostgreSQL, Knex.js, Socket.IO
- Mobil: React Native (Expo)

## Kurulum

### Backend
```bash
cd server
npm install
npx knex migrate:latest
npx knex seed:run
npm run dev
```

### Mobil
```bash
cd mobile
npm install
npx expo start
```
