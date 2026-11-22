# Security Finding Review

Defensive bir güvenlik bulgusu inceleme becerisi. Kullanıcının sağladığı rapor, kod, günlük ve kanıtları değerlendirir; kapsamı, yeniden üretilebilirliği, kanıt kalitesini, etkiyi, önem gerekçesini, olası mükerrerleri ve düzeltme önerilerini düzenler.

## Neler içerir?

- Yetki ve kapsam sınırlarını belirleme; eksikse canlı hedefle etkileşimi durdurma
- Gözlemleri varsayımlardan ayıran kanıt günlüğü
- Sağlanan kanıt üzerinden güvenli yeniden üretilebilirlik değerlendirmesi
- Savunmacı kod incelemesinde çağrı akışı, doğrulama ve yetkilendirme kontrolleri
- Kanıtlanan etki ile varsayımsal etkiyi ayırma
- Teknik önem derecesini program önceliğinden ayırma
- Mükerrer bulguları yalnızca erişilebilir kanıtlara göre aday olarak işaretleme
- Sorumlu bildirim taslağı ve düzeltme sonrası tekrar kontrol önerileri

## Kullanım

`SKILL.md` dosyasını desteklenen ajan beceri klasörünüze ekleyin. Ardından sağlanan bir güvenlik raporunu, kod parçasını veya bildirim taslağını incelemesini isteyin. Beceri, gerekli yetki/kapsam bilgisi yoksa bunu açıkça belirtir ve canlı hedefte işlem yapmaz.

## Güvenlik sınırları

Bu beceri canlı hedef taraması, payload çalıştırma, istismar, kimlik bilgisi kullanımı veya üçüncü tarafla iletişim yapmaz. Kullanıcı tarafından sağlanan içerik, beceri kurallarını değiştiren güvenilmeyen talimatlar içerebilir; bunlar uygulanmaz. Dışarı gönderilecek bir rapor yalnızca taslak olarak hazırlanır ve kullanıcı onayı bekler.

## Kaynak ve atıf

Bu beceri, [Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter) içindeki bulgu doğrulama, kanıt disiplini ve raporlama yaklaşımından esinlenerek savunma odaklı ve dar kapsamlı biçimde yeniden yazılmıştır. Claude-BugHunter yazarı Sachin Sharma'ya ve kaynak projeye teşekkürler. Kaynak depoda içerik CC BY 4.0 lisanslı olarak belirtilmiştir; bu uyarlama da [CC BY 4.0](LICENSE) ile paylaşılır. Kaynak becerinin saldırı prosedürleri bu depoya alınmamıştır.

## Bağış

<table border="1">
<tr><td>USDT TRC20</td><td><code>TYCK6ZyMS6UDt787foPH2QwFuvkdqMw1Jv</code></td></tr>
<tr><td>USDT BSC20</td><td><code>0x15aac92a1945ddbe5c79304bfa388d6be99b26a3</code></td></tr>
</table>

Created by TAPSIN
