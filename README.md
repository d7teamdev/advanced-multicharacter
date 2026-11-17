<p align="center"><img src="https://d7team.com/icon-512.png" width="88" alt="Delta Seven"></p>
<h1 align="center">Advanced Multicharacter</h1>
<p align="center"><b>FiveM Multicharacter for QBCore, QBox, ESX & CFW</b></p>
<p align="center"><a href="#english">English</a> · <a href="#arabic">العربية</a></p>

<p align="center"><a href="https://d7team.com/products/advanced-multicharacter"><img src="https://img.youtube.com/vi/zn1b0kOnXYc/maxresdefault.jpg" alt="Advanced Multicharacter" width="860"></a></p>

<a id="english"></a>

## Advanced Multicharacter — FiveM Multicharacter for QBCore, QBox, ESX & CFW

FiveM multicharacter for QBCore, QBox, ESX & CFW: each character in the city with its own car, customizable slots, nationality from every country.

Advanced Multicharacter shows every character standing in the city in its own outfit, beside one of its own cars, under a cinematic camera. You set how many characters each player gets, nationalities come from every country in the world, and every character spawns where it last was.

> This repository is documentation only. The resource is sold on our store and downloaded from the Client Area after you redeem your code.

[Website](https://d7team.com/products/advanced-multicharacter) · [Installation guide](https://d7team.com/guides/advanced-multicharacter) · [Store](https://store.d7team.com/advanced-multicharacter/p321432359) · [Discord](https://discord.gg/d-7)

### At a glance

| | |
|---|---|
| **Works with** | QBCore, QBox and ESX servers, CFW included |
| **Clothing** | Most clothing resources, on every framework |
| **Characters** | As many as you set, more for chosen players or groups |
| **Nationality** | Every country in the world |
| **Spawn** | The character's last location |
| **Language** | Arabic and English |

### Features

#### The scene

- Every character stands in the city in its own outfit, beside one of its own cars with its paint and parts.
- Switch between the character's cars, and its choice is remembered.
- Eight poses to switch between.
- A cinematic camera with depth of field, under your server's own time and weather.
- Hide the menu for a clean shot of the character.

#### Characters

- A card for each character: face, name, age, nationality, job, cash, bank, phone, citizen ID, play time and last played.
- Set the number of characters, with more for chosen players or for groups such as VIP.
- Safe delete by typing the character's full name, or turn deleting off.
- Streamer mode hides the phone number and the money.

#### A new character

- A new identity: name, date of birth, gender and nationality.
- Nationality from every country in the world, or typed freely.
- Set the allowed age range.
- Set where new characters start.

#### Spawn

- Spawns at the character's last location, with no spawn menu.
- A character that left dead or down comes back the same way, so nobody escapes by leaving.

#### Configuration and logs

- /logout for admins, and an event and an export to send a player back to the menu from your own scripts.
- Discord logs for created, loaded and deleted characters.
- Customizable menu colours, and the scene's place anywhere on the map.
- Replaces qb-multicharacter and esx_multicharacter, so resources that call them keep working.

### Video

[![Advanced Multicharacter](https://img.youtube.com/vi/zn1b0kOnXYc/hqdefault.jpg)](https://www.youtube.com/watch?v=zn1b0kOnXYc)

### Requirements

- **QBCore:** A QBCore server, CFW included
- **QBox:** A QBox server with qbx_core and ox_lib
- **ESX:** An ESX server with es_extended
- oxmysql
- **QBCore, QBox:** illenium-appearance, fivem-appearance, rcore_clothing or qb-clothing
- **ESX:** illenium-appearance, fivem-appearance, rcore_clothing or skinchanger with esx_skin
- An Advanced Multicharacter licence

### Installation

1. Buy Advanced Multicharacter on our store.
2. Sign in at panel.d7team.com with Discord.
3. Client Area → Redeem Code: enter the code and your server's public IP.
4. Download d7-multicharacter from the Client Area and put it in resources.
5. Remove qb-multicharacter from your resources.

   **QBCore:** Remove qb-multicharacter from your resources.

   **ESX:** Remove esx_multicharacter from your resources.

   **QBox:** In qbx_core's config/client.lua, set useExternalCharacters = true.

   **QBCore:** In server.cfg, start it after your database and framework:

   ```cfg
   ensure oxmysql
   ensure qb-core
   ensure illenium-appearance
   ensure d7-multicharacter
   ```


   **QBox:** In server.cfg, start it after your database and framework:

   ```cfg
   ensure oxmysql
   ensure ox_lib
   ensure qbx_core
   ensure illenium-appearance
   ensure d7-multicharacter
   ```


   **ESX:** In server.cfg, start it after your database and framework:

   ```cfg
   ensure oxmysql
   ensure es_extended
   ensure skinchanger
   ensure esx_skin
   ensure d7-multicharacter
   ```

6. Put your own clothing resource in the block above.
7. Restart the server.

Configuration, first start, updates and every console message explained: [Installation guide](https://d7team.com/guides/advanced-multicharacter)

### Pricing

- **$27.99** — [One-time purchase of this script](https://store.d7team.com/advanced-multicharacter/p321432359)
- **$7.99 / month** — [Scripts subscription (Advanced MDT, Advanced BossMenu and Advanced Multicharacter)](https://store.d7team.com/scripts-monthly-subscription/p1713646054): every script, free IP change during the subscription, and free updates
- **$13.99 / month** — [Premium Plan (Delta Panel, Advanced MDT, Advanced BossMenu and Advanced Multicharacter)](https://store.d7team.com/premium-bundle-30-days/p387462061)
- **$34.99 / quarter** — [Premium Plan, quarterly](https://store.d7team.com/premium-bundle-90-days/p645358899)

[Store](https://store.d7team.com/advanced-multicharacter/p321432359)

### FAQ

<details>
<summary><b>Which servers does Advanced Multicharacter work on?</b></summary>

QBCore, QBox and ESX servers, CFW included, and most clothing resources are supported on every framework.

</details>

<details>
<summary><b>Can some players have more characters?</b></summary>

Yes. You set how many characters everyone gets, and you can give more to one player, or to an ACE group such as VIP. A Discord role gets them too when your server gives its roles ACE groups.

</details>

<details>
<summary><b>Do resources made for qb-multicharacter still work?</b></summary>

Yes. It answers to qb-multicharacter's and esx_multicharacter's names and events, so resources that call them keep working.

</details>

<details>
<summary><b>Can players switch characters without the admin command?</b></summary>

Yes. /logout is for the top permission, and one event in any of your server scripts sends a player back to the menu, so you can make a command, a menu or a place for it.

</details>

<details>
<summary><b>How much does Advanced Multicharacter cost?</b></summary>

It comes with several options: buy it once for $27.99, get it in the scripts subscription with Advanced MDT and Advanced BossMenu for $7.99 a month, or in the Premium Plan with Delta Panel, Advanced MDT and Advanced BossMenu from $13.99 a month.

</details>

### Support

Support is on our Discord: [discord.gg/d-7](https://discord.gg/d-7). Issues are closed on this repository so no request waits unread.

### More from Delta Seven

- [Delta Panel](https://github.com/d7teamdev/delta-panel) — FiveM Admin Panel for QBCore, QBox, ESX, vRP & CFW Servers
- [Advanced MDT](https://github.com/d7teamdev/advanced-mdt) — FiveM Police MDT for QBCore, QBox, ESX & CFW
- [Advanced BossMenu](https://github.com/d7teamdev/advanced-bossmenu) — FiveM Boss Menu for QBCore, QBox, ESX & CFW
- [Add-on FiveM cars](https://d7team.com/cars)

---

<a id="arabic"></a>

<div dir="rtl">

## ملتي كركتر متطور — سكربت ملتي كركتر فايف ام لـ QBCore و QBox و ESX و CFW

سكربت ملتي كركتر فايف ام لـ QBCore و QBox و ESX و CFW: كل شخصية بالمدينة مع سيارتها، عدد شخصيات تتحكم فيه، وجنسيات من كل دول العالم.

ملتي كركتر متطور يعرض كل شخصية واقفة بالمدينة بلبسها، وجنبها وحدة من سياراتها، بكاميرا سينمائية. تحدد عدد الشخصيات لكل لاعب، والجنسيات من كل دول العالم، وكل شخصية ترسبن بآخر مكان كانت فيه.

> هذا المستودع للتعريف والشرح فقط. الريسورس يُباع في متجرنا، وتحمّله من منطقة العميل بعد ما تفعّل الكود

[الموقع](https://d7team.com/ar/products/advanced-multicharacter) · [شرح التثبيت](https://d7team.com/ar/guides/advanced-multicharacter) · [المتجر](https://store.d7team.com/advanced-multicharacter/p321432359) · [الدسكورد](https://discord.gg/d-7)

### نظرة سريعة

| | |
|---|---|
| **يشتغل مع** | سيرفرات QBCore و QBox و ESX، ومعها CFW |
| **الملابس** | أغلب ريسورسات الملابس مدعومة، لكل أنواع الفريم وورك |
| **الشخصيات** | العدد اللي تحدده، وأكثر للاعبين أو قروبات تختارها |
| **الجنسية** | كل دول العالم |
| **الرسبن** | آخر مكان كانت فيه الشخصية |
| **اللغة** | العربي والإنجليزي |

### المميزات

#### المشهد

- كل شخصية واقفة بالمدينة بلبسها، وجنبها وحدة من سياراتها بلونها وقطعها
- تبديل سيارات الشخصية، ويتحفظ اختيارها
- ثمان وضعيات تتنقل بينها
- كاميرا سينمائية مع عمق الصورة، على وقت سيرفرك وجوه
- إخفاء المنيو عشان تاخذ لقطة نظيفة للشخصية

#### الشخصيات

- بطاقة لكل شخصية: الوجه، الاسم، العمر، الجنسية، الوظيفة، الكاش، البنك، الجوال، رقم المواطن، وقت اللعب، وآخر دخول
- تحدد عدد الشخصيات، وتعطي أكثر للاعبين تختارهم أو لقروبات مثل VIP
- حذف آمن بكتابة اسم الشخصية كامل، أو تقفل الحذف
- وضع الستريمر يخفي رقم الجوال والفلوس

#### شخصية جديدة

- هوية جديدة: الاسم، تاريخ الميلاد، الجنس، والجنسية
- الجنسية من كل دول العالم، أو تنكتب بحرية
- تحدد العمر المسموح
- تحدد مكان بداية الشخصيات الجديدة

#### الرسبن

- الرسبن بآخر مكان كانت فيه الشخصية، بدون منيو رسبن
- الشخصية اللي طلعت وهي ميتة أو طايحة ترجع بنفس حالتها، فما أحد يهرب بالخروج

#### الإعداد واللوقات

- أمر ⁦/logout⁩ للإدارة، وإيفنت و export ترجّع فيهم اللاعب للمنيو من سكربتاتك
- لوقات دسكورد لإنشاء الشخصيات ودخولها وحذفها
- ألوان المنيو قابلة للتخصيص، ومكان المشهد بأي مكان بالخريطة
- يحل مكان qb-multicharacter و esx_multicharacter، فالريسورسات اللي تناديهم تكمل شغلها

### الفيديو

[![Advanced Multicharacter](https://img.youtube.com/vi/zn1b0kOnXYc/hqdefault.jpg)](https://www.youtube.com/watch?v=zn1b0kOnXYc)

### المتطلبات

- **QBCore:** سيرفر QBCore، ومعها CFW
- **QBox:** سيرفر QBox مع qbx_core و ox_lib
- **ESX:** سيرفر ESX مع es_extended
- oxmysql
- **QBCore, QBox:** illenium-appearance أو fivem-appearance أو rcore_clothing أو qb-clothing
- **ESX:** illenium-appearance أو fivem-appearance أو rcore_clothing أو skinchanger مع esx_skin
- ترخيص ملتي كركتر متطور

### التثبيت

1. اشترِ ملتي كركتر متطور من متجرنا.
2. سجّل دخولك في panel.d7team.com عن طريق دسكورد.
3. منطقة العميل ← تفعيل كود: اكتب الكود وآيبي سيرفرك.
4. حمّل d7-multicharacter من منطقة العميل وحطه في مجلد resources بسيرفرك.
5. شيل qb-multicharacter من الريسورسات.

**QBCore:** شيل qb-multicharacter من الريسورسات.

**ESX:** شيل esx_multicharacter من الريسورسات.

**QBox:** في ملف config/client.lua حق qbx_core، خلّ useExternalCharacters = true عشان تنقفل شاشته

**QBCore:** في server.cfg، شغّله بعد قاعدة البيانات والفريم وورك:

</div>

```cfg
ensure oxmysql
ensure qb-core
ensure illenium-appearance
ensure d7-multicharacter
```

<div dir="rtl">


**QBox:** في server.cfg، شغّله بعد قاعدة البيانات والفريم وورك:

</div>

```cfg
ensure oxmysql
ensure ox_lib
ensure qbx_core
ensure illenium-appearance
ensure d7-multicharacter
```

<div dir="rtl">


**ESX:** في server.cfg، شغّله بعد قاعدة البيانات والفريم وورك:

</div>

```cfg
ensure oxmysql
ensure es_extended
ensure skinchanger
ensure esx_skin
ensure d7-multicharacter
```

<div dir="rtl">

6. حط ريسورس الملابس حقك مكان اللي بالبلوك فوق.
7. سوّ ريستارت للسيرفر.

الإعدادات، أول تشغيل، التحديثات، وشرح كل رسالة بالكونسول: [شرح التثبيت](https://d7team.com/ar/guides/advanced-multicharacter)

### الأسعار

- **⁦$27.99⁩** — [شراء هذا السكربت مرة وحدة](https://store.d7team.com/advanced-multicharacter/p321432359)
- **⁦$7.99⁩ بالشهر** — [اشتراك السكربتات (ام دي تي متطور و بوس منيو متطور و ملتي كركتر متطور)](https://store.d7team.com/scripts-monthly-subscription/p1713646054): كل السكربتات، تغيير الآيبي مجاناً خلال مدة الاشتراك، وتحديثات مجانية
- **⁦$13.99⁩ بالشهر** — [باقة بريميوم (لوحة دلتا و ام دي تي متطور و بوس منيو متطور و ملتي كركتر متطور)](https://store.d7team.com/premium-bundle-30-days/p387462061)
- **⁦$34.99⁩ ربع سنوي** — [باقة بريميوم، ربع سنوي](https://store.d7team.com/premium-bundle-90-days/p645358899)

[المتجر](https://store.d7team.com/advanced-multicharacter/p321432359)

### الأسئلة الشائعة

<details>
<summary><b>على أي سيرفرات يشتغل ملتي كركتر متطور؟</b></summary>

سيرفرات QBCore و QBox و ESX، ومعها CFW، وأغلب ريسورسات الملابس مدعومة لكل أنواع الفريم وورك.

</details>

<details>
<summary><b>هل أقدر أعطي بعض اللاعبين شخصيات أكثر؟</b></summary>

نعم. تحدد عدد الشخصيات للكل، وتقدر تعطي أكثر للاعب معيّن، أو لقروب ACE مثل VIP. ورتبة الدسكورد تاخذها بعد إذا سيرفرك يعطي رتب الدسكورد قروبات ACE

</details>

<details>
<summary><b>هل الريسورسات المسوّاة لـ qb-multicharacter تكمل تشتغل؟</b></summary>

نعم. يرد بأسماء وإيفنتات qb-multicharacter و esx_multicharacter، فالريسورسات اللي تناديهم تكمل شغلها.

</details>

<details>
<summary><b>هل يقدر اللاعب يبدّل شخصيته بدون أمر الإدارة؟</b></summary>

نعم. أمر ⁦/logout⁩ لأعلى صلاحية، وإيفنت واحد بأي سكربت سيرفر عندك يرجّع اللاعب للمنيو، فتقدر تسوي له أمر أو منيو أو مكان.

</details>

<details>
<summary><b>كم سعر ملتي كركتر متطور؟</b></summary>

متوفر بأكثر من خيار: شراء مرة وحدة بـ ⁦$27.99⁩، أو ضمن اشتراك السكربتات مع ام دي تي متطور و بوس منيو متطور بـ ⁦$7.99⁩ بالشهر، أو ضمن باقة بريميوم مع لوحة دلتا و ام دي تي متطور و بوس منيو متطور تبدأ من ⁦$13.99⁩ بالشهر.

</details>

### الدعم

الدعم على الدسكورد حقنا: [discord.gg/d-7](https://discord.gg/d-7). الـ Issues مقفلة بهذا المستودع عشان ما يضيع أي طلب بدون رد

### منتجات ثانية من دلتا سفن

- [لوحة دلتا](https://github.com/d7teamdev/delta-panel) — لوحة تحكم سيرفرات فايف ام لـ QBCore و QBox و ESX و vRP
- [ام دي تي متطور](https://github.com/d7teamdev/advanced-mdt) — سكربت MDT للشرطة في فايف ام لـ QBCore و QBox و ESX و CFW
- [بوس منيو متطور](https://github.com/d7teamdev/advanced-bossmenu) — سكربت بوس منيو فايف ام لـ QBCore و QBox و ESX و CFW
- [سيارات فايف ام مضافة](https://d7team.com/ar/cars)

</div>

---

<p align="center">© Delta Seven (D7 Team) · <a href="https://d7team.com">d7team.com</a></p>
