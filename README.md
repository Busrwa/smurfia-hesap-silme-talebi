# Smurfia – Hata Defteri | Hesap Silme Talebi

Bu doküman, Smurfia – Hata Defteri uygulamasında hesabın ve ilişkili verilerin nasıl silineceğini açıklar.

## 1. Hesap Silme Adımları
Hesabınızı ve ilişkili verilerinizi silmek için aşağıdaki adımları izleyin:

1. Smurfia – Hata Defteri uygulamasını açın.
2. Hesabınıza giriş yapın.
3. Ana ekranda sağ üst köşede bulunan Profil bölümüne girin.
4. Profil sayfasında “Hesabı Sil” butonuna tıklayın.
5. Açılan onay penceresinde “Hesabı Sil” seçeneğini onaylayın.

## 2. Silinen Veriler
Hesabınız silindiğinde aşağıdaki veriler kalıcı olarak silinir:

- Firebase Authentication’da kayıtlı kullanıcı hesabı
- Firestore’daki kullanıcıya ait tüm “mistakes” (hata) kayıtları
- Firestore’daki kullanıcıya ait tüm “vocabulary” (kelime) kayıtları
- Firestore’daki “users” koleksiyonundaki kullanıcı bilgileri

## 3. Veri Saklama Süresi
Hesap silme işlemi tamamlandığında veriler kalıcı olarak silinir ve geri getirilemez.

Veriler, kullanıcı tarafından silinene kadar saklanır. Hesap silme talebi sonrası ek bir saklama süresi uygulanmaz.

## 4. Ek Bilgi
- Hesabınızı silmek geri alınamaz.
- Hesap silme işlemi sırasında cihazınızdan tekrar giriş istenebilir.
- Eğer “Hesabı Sil” işlemi sırasında hata alırsanız, lütfen uygulama içindeki e-posta adresinden bize ulaşın.

## 5. İletişim
Herhangi bir sorun veya talep için:
- E-posta: staysunst@gmail.com
