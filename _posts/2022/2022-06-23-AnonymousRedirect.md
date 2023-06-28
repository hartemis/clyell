---
layout: post
title: Anonymous Redirect / Referrer
date: 2022-06-23 12:10:00 +0200
categories: project
tags: javascript security privacy
image: 
---

Anonim linkler oluşturmak için basit HTML + JS kodu.

🔥 Repo: [HuzunluArtemis/AnonymousRedirect](https://gitlab.com/HuzunluArtemis/AnonymousRedirect)

Orijinal olarak [AdGuard](https://github.com/HuzunluArtemis/AnonymousRedirect) tarafından yazıldı. Ben biraz düzenledim.

Internet Explorer 11'de çalışmayabilir.

## Link Oluşturma

Linki öncelikle encode [etmelisiniz](https://www.urlencoder.org/). Sonra encode ettiğiniz linki şu şekilde düzenlemelisiniz:

`https://artemis.pages.dev/redirect?url=[Buraya Linkin Gelecek]`

Örnek:

`https://hartemis.github.io/redirect/?url=https%3A%2F%2Fwww.urlencoder.org%2F`

## Lisans

### GPL-v3 Lisansı

You can use, study share and improve it at your will. Specifically you can redistribute and/or modify it under the terms of the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.html) as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.