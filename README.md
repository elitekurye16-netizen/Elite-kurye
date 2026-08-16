# ELİTE KURYE Courier v4

Expo/React Native kurye uygulaması.
- JWT login
- İş listesi
- Paket durumları
- 30 sn GPS güncelleme
- Navigasyon açma
- Hakediş gösterimi

Production:
1. `npm install`
2. `App.js` içindeki `API` adresini gerçek HTTPS API'ye değiştir.
3. Expo/EAS ile Android APK/AAB ve iOS build al.
4. Background GPS için `expo-location` background task + native permissions ekle.
5. Push için Firebase/APNs ve `expo-notifications` yapılandır.
