---
title: Let's Encrypt
localeTitle: Давайте зашифровать
---
## Давайте зашифровать

Let's Encrypt - это бесплатный для использования Центр сертификации. Большинство браузеров поддерживают и доверяют. Давайте зашифруем сертификаты. Сертификат CA необходим для обслуживания вашего сайта через HTTPS и получения браузеров, чтобы доверять сайту.

Самый простой способ начать работу с Let's Encrypt - это использовать [certbot](https://certbot.eff.org/) , популярный клиент Let's Encrypt, который поможет вам легко развертывать и поддерживать ваш SSL-сертификат. Сертификат Let's Encrypt истекает через 90 дней и может быть обновлен каждый раз. 90 дней могут показаться короткими, но клиенты, такие как certbot, могут помочь вам автоматизировать обновление сертификата.

Есть множество Let's Encrypt [клиентов,](https://letsencrypt.org/docs/client-options/) кроме certbot, поэтому вы можете ожидать, что Let's Encrypt будет легко реализован на вашем сервере.

Если вы размещаете сервер VPS / выделенный сервер, вам не нужно беспокоиться о поддержке Let Encrypt. Однако, если вы находитесь на виртуальный хостинг план ваш хост будет иметь Давайте Encrypt [конкретно](https://community.letsencrypt.org/t/web-hosting-who-support-lets-encrypt/6920) прямо предусмотрено.

#### Дополнительная информация:

https://letsencrypt.org/ Let's Encrypt - это бесплатный, автоматизированный и открытый центр сертификации. https://community.letsencrypt.org/t/web-hosting-who-support-lets-encrypt/6920 Список общего хоста, который поддерживает Let's Encrypt. https://letsencrypt.org/docs/client-options/ Список шифрованных клиентов.