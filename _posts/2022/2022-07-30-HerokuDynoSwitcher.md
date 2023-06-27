---
layout: post
title: Heroku Dyno Switcher
date: 2022-07-30 03:20:00 +0200
categories: project
tags: telegram heroku python
image: 
---

🇹🇷 Heroku uygulamanızı dyno saatlerinden endişe duymadan sonsuza kadar canlı hale getirmek için küçük bir python projesi. Daha fazla dino saati almak için kredi kartı ekleme zahmetine girmenize gerek yok.

🇬🇧 A little python project to make your heroku app alive forever without being concerned about dyno hours. You do not need to bother adding a credit card to get more dyno hours.

## Features

- Unlimited app switch
- No need to enter app type (auto detecting web, worker)
- Stops / starts all processes

## Setting Config Link

- Go to [gist.github.com](https://gist.github.com) and create a secret gist
- Filename: HerokuDynoSwitcher, Gist description: HerokuDynoSwitcher
- Your config will be like:
  - Line 1: First heroku app name
  - Line 2: First heroku account api
  - Line 3: Second heroku app name
  - Line 4: Second heroku account api
  - Line 5: Newline
- You can enter unlimited apps like that:
- ![](https://i.ibb.co/FBHbW5H/181908371-3e89ced0-c639-418a-8507-5a5e5fcfafe7.png)
- Now click `Create Secret Gist` button
- Click `Raw`:
- ![](https://i.ibb.co/m4xbSFx/181908458-b1870588-b7d4-4a3a-8289-f7f5bada3824.png)
- Copy your link. Mine is here:
- `https://gist.githubusercontent.com/HuzunluArtemis/48cf681365d3d27509b2d1daa19d/raw/c46e28fd5ac8bbf4945eea0abad6a0ffce4c13ae/HerokuDynoSwitcher`
- Edit this like that:
- `https://gist.githubusercontent.com/HuzunluArtemis/48cf681365d3d27509b2d1daa19d/raw/HerokuDynoSwitcher`
- Example, i deleted: `c46e28fd5ac8bbf4945eea0abad6a0ffce4c13ae` You will delete yours.
- This step is important! Make you sure edited your config url! If you dont do that, changes you make in the config will not take effect.
- We got config file link. Keep in safe and dont share anyone!

## Deploy

- Go to repo: [HuzunluArtemis/HerokuDynoSwitcher](https://github.com/HuzunluArtemis/HerokuDynoSwitcher)
- Fork with this button:
- ![](https://i.ibb.co/pbMhpcZ/181908627-a099a958-5841-4fc5-bf70-87cfd1b7665b.png)
- Go to your Settings:
- ![](https://i.ibb.co/ZYbSf24/181908664-ae1fc2cb-6c05-4141-b903-9883a28d3529.png)
- Go to your Secrets > Actions (Can be shown as Secrets) > New Repository Secret
- ![](https://i.ibb.co/n187wTS/181908800-f134353b-7072-4f46-9b37-acc7ba03ca4a.png)
- Paste your config like this. Name: `CONFIG_FILE_URL` Value: Your edited config link:
- ![](https://i.ibb.co/0Y36gGC/181908866-e59276d0-3ca1-4478-aea2-5aa365a40f46.png)
- Now go to your `Actions` tab:
- ![](https://i.ibb.co/hRhYGvj/181909231-11eb6260-9141-4adf-8dcf-94112b87e42d.png)
- Accept this warning:
- ![](https://i.ibb.co/qBfP4YN/181909363-4e51e944-87b1-4144-991c-088de393681b.png)
- Go to `HuzunluArtemis HerokuDynoSwitcher` > `Enable workflow`:
- ![](https://i.ibb.co/GMLw6wR/181909559-d3e83259-8a9f-41c9-b8c3-25bcfc1932d2.png)
- Done. Your apps will automatically change on the 1st and 15th of each month.
- If you want to add new bot(s) edit your config file from gist.github.com. Dont edit anything from github.

## Inspiration

- [tiararosebiezetta/HerokuDynoSwitcher](https://github.com/tiararosebiezetta/HerokuDynoSwitcher)
- [heroku.viperadnan.gq/duo](https://heroku.viperadnan.gq/duo)

## Lisans

![](https://www.gnu.org/graphics/gplv3-127x51.png)

You can use, study share and improve it at your will. Specifically you can redistribute and/or modify it under the terms of the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.html) as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
