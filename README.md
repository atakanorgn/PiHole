🚀 PiOrbit
Raspberry Pi için Modern DNS Reklam Engelleyici & Gizlilik Kalkanı

PiOrbit, ağınızdaki reklamları kökten temizleyen ve sorgularınızı kimseye sızdırmadan çözen kişisel bir DNS çözümüdür.

✨ Özellikler
* 🛡️ Pi-hole Entegrasyonu:** 70.000+ reklam domainini anında engeller.
* 🕵️ Unbound (Recursive DNS):** Sorguları Google/Cloudflare yerine doğrudan kök sunuculara sorar (Tam Gizlilik).
* ⚡ Ultra Hızlı: Önbellekleme (Caching) sayesinde milisaniyelik yanıt süreleri.
* 📊 Tailscale Desteği:** Dışarıdayken bile güvenli ve reklamsız bağlantı.

🛠️ Kurulum
Bu proje /opt/piorbit dizini altında çalışacak şekilde tasarlanmıştır.

git clone [https://github.com/atakanorgn/PiHole.git](https://github.com/atakanorgn/PiHole.git)
cd PiHole/backend
npm install
npm start
