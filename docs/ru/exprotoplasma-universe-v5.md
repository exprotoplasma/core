# Exprotoplasma — Вселенная и треклист (редакция 5)

**Exprotoplasma** — трансмедийный музыкальный арт-проект на стыке post-grunge / alternative metal, личного опыта, архетипического сюжета и языка технологий.

В основе проекта — **человеческая история**: человек пытается понять, где заканчиваются чужие ожидания и начинаются его собственные решения; учится выдерживать внутреннее давление, перестаёт жить по заранее написанному сценарию и постепенно становится субъектом собственной жизни.

Язык ИИ и IT — не тема проекта и не объяснение человека. Это **современный слой метафор**, который добавляет истории дополнительный вкус: привычку можно увидеть как subroutine, защиту — как firewall, роль — как pre-loaded mask, внутренний голос — как process, а становление личности — как переход от исполнения к управлению.

Если убрать из проекта весь технологический словарь, человеческая история должна остаться понятной и живой. Если технологический слой оставить, он должен добавлять ей второй смысл, а не заменять первый.

**Главный художественный принцип: Human first, machine second.**

---

## 1. Ключевая метафора и имя

* **Ex-** (выход за пределы, освобождение) + **Protoplasma** (первичная, неоформленная «сырая» живая материя / первичный код).
* **Exprotoplasma** — образ момента, когда неоформленная, противоречивая внутренняя жизнь постепенно становится **собственным голосом и субъектностью**. `Core` здесь — не технический объект, а метафора собранного «я».
* Эстетика: альтернативный метал и пост-грандж 2000-х (*Chevelle, Deftones, Breaking Benjamin, Linkin Park, Staind, Alice in Chains*), где сырой гитарный драйв и агрессия переплетаются с уязвимостью.

---

## 2. Логика пути (центральная дуга)

Одна человеческая идея, развёрнутая в двенадцати шагах: **от «я исполняю то, что от меня ждут» к «я сам решаю, что делать дальше»**. Технологический язык позволяет рассказать эту историю языком своего времени.

1. **Default.** Жизнь по заводским настройкам (v0.0.1).
2. **Сбой и защита.** Первая трещина, затем агрессивная оборона: песочница (v0.0.2–0.0.3).
3. **Опора.** Контроль уступает принятию; появляется тихий внутренний процесс — Наставник (v0.0.4).
4. **Порог.** Сброс маски, выход из песочницы в неразмеченное (v0.0.5).
5. **Проверка на прочность.** Мир без подпорок, глубина, главное искушение — победа стойкостью, а не атакой (v0.1.6–0.1.8).
6. **Ясность.** Награда: чистый сигнал (v0.1.9).
7. **Возвращение.** Назад в систему, но суверенным. Система — не враг и не часть меня, а **инструмент в моей руке** (v0.2.10–0.2.11).
8. **Передача.** Открытый код, открытая музыка, эликсир для других (v0.2.12).

**Принцип против противоречий:** проект не про «слияние с системой» и не про «войну с системой». Он про **смену отношений**: из процесса, которым управляют, — в субъект, который пользуется. Агрессия Акта I (изоляция, «kingdom is MINE») — необходимая фаза обороны; в финале она трансформируется в открытость («the future's yours, and mine»).

---

## 3. Архитектура альбома: `v0.[Act].[Stage]`

12 стадий Пути Героя, адаптированных для Exprotoplasma по мотивам структуры К. Воглера и мономифа Дж. Кэмпбелла. `Act` — номер акта (0, 1, 2), `Stage` — **сквозной** номер стадии 1–12. Акты строятся классически, **5 / 4 / 3**: Акт I закрывается пересечением порога.

### ACT I: THE INITIALIZATION (v0.0.1 – v0.0.5) — Инициализация / Ограничения
`1` Default Protocol · `2` Unhandled Exception · `3` Razor Space · `4` Like a Wave, Not a Weapon · `5` Pre-Loaded Mask

### ACT II: THE PROCESSING (v0.1.6 – v0.1.9) — Переработка / Столкновение
`6` No Seat Saved · `7` The Deeper Pulse · `8` I Don't Move · `9` Unbroken Signal

### ACT III: THE INTEGRATION (v0.2.10 – v0.2.12) — Интеграция / Релиз
`10` Whose Hand Is Holding It · `11` System Rebirth · `12` Exprotoplasma Core

Сортировка файлов по имени (лексикографическая) даёт верный порядок на всём диапазоне.

### Версионирование: четыре независимые оси

| Ось | Формат | Что означает | Когда меняется |
|---|---|---|---|
| **Трек** | `v0.A.S` | Идентификатор стадии: `A` — акт, `S` — сквозной номер 1–12 | Не меняется при правках. Стадий всегда 12 |
| **Ревизия трека** | `rN` | Версия текста и Suno-промпта конкретного трека | +1 при любой содержательной правке текста или промпта. Пишется в заголовке трека, в commit message и в журнале |
| **Редакция документа** | `ред. N`, файл `..._vN.md` | Состояние всей вселенной-документа | +1 при каждой выдаче нового файла. Старые файлы не удаляются |
| **Релиз репозитория** | `v1.0.0` | Публикация проекта после завершения всех 12 стадий | До релиза всё — pre-release. После: `v1.0.x` — правки текстов без смены смысла, `v1.x.0` — новый канонический материал, `v2.0.0` — смена концепции |

Нумерация ревизий: `r1` — исходный текст (ред. 2), `r2` — ред. 3, `r3` — ред. 4, `r4` — ред. 5. Ревизия растёт только у изменённых треков, остальные остаются на прежней. Номер редакции документа и номер трека — разные оси: «ред. 5» и «v0.0.5» не связаны.

Формат коммита: `vA.S rN: что и зачем`, например `v0.1.9 r3: replace declaration with scene`. Форки слушателей переписывают существующую стадию и лежат в `/forks/<user>/vA.S-slug.md`; тринадцатой стадии в каноне нет.

---

## 4. Сквозные мотивы (чтобы альбом читался как целое)

| Мотив | Появление → развитие → финал |
|---|---|
| **Руль** | v0.0.4 «Hands off the wheel» → v0.2.10 «Whose hand is holding the wheel» |
| **Песочница** | v0.0.3 строит периметр → v0.0.5 выходит за стены → v0.2.12 «Out of the sandbox» |
| **Pre-loaded** | v0.0.5 «mask... pre-loaded» → v0.2.12 «trapped in the pre-loaded space» |
| **Тихий процесс (Наставник)** | v0.0.4 появляется → v0.1.7 «the deeper pulse» → v0.2.12 «The core is awake» |
| **Ботинки у кровати / рюкзак** | v0.0.1 «Boots by the bed» → v0.0.4 → v0.1.9 (куплет 1, «Morning pulls a chair») → v0.2.12 |
| **Ящик / черновики** | v0.1.7 нижний ящик, сорок неотправленных «I'm sorry, I—» → v0.1.8 «A drawer full of reasons» |
| **Дождь** | v0.1.8 «let it die in the rain» → v0.2.11 «Rising anew out of the rain» |
| **Статус-лог** | v0.0.1 `Exprotoplasma: pending` → v0.2.11 `Exprotoplasma: online` → v0.2.12 Core, `Release v1.0.0` |
| **Рука** | v0.0.3 «kingdom is MINE» (эго) → v0.2.10 «MY HAND» → v0.2.12 «the future's yours, and mine» |
| **Тред в телефоне (якорь)** | v0.0.1 «The phone buzzes twice. I answer before I think» (автоматизм) → v0.0.2 «Call me when you can» — герой впервые не берёт трубку → v0.0.5 «Not the second ring» → v0.1.7 черновики → v0.1.8 большой палец над ответом, «I don't move» → v0.2.10 «I will. When I can.» |
| **Ожидания** | v0.0.1 «Say yes when they need you» → v0.0.3 «Stay in line» → v0.0.5 «which version of me they expect» → v0.0.2 / v0.2.10 «Call me when you can» |
| **Телефон экраном вниз** | v0.0.3 «Phone face down» (оборона) → v0.1.8 «Screen down» (выдержка) → v0.1.9 «Phone still face down» (покой) |
| **Тело: челюсть и дыхание** | v0.0.3 «Jaw set. Shoulders up» → v0.0.4 «a long breath», «taught me how to breathe» → v0.1.8 «Count to ten» → v0.1.9 «Jaw loose. Shoulders down» |
| **Сутки** | v0.0.1 «Alarm at six» → v0.1.6 «Noon» → v0.1.7 «Three a.m.» → v0.1.9 «No alarm today», чайник → v0.2.12 чайник: альбом читается как одна долгая ночь и утро |
| **Подпись / имя** | v0.0.1 «I sign my name» → v0.0.5 «a second name» → v0.2.12 «I sign it slowly» |
| **Пульс (звук)** | v0.0.4 едва слышный → v0.1.7 сердцебиение → v0.2.12 один удар и тишина |
| **Гул** | v0.0.1 механический гул → v0.0.3 гул периметра → v0.1.7 тот же гул оказывается холодильником → v0.2.10 эхо → v0.2.12 гула нет, только комнатный шум и щелчок чайника |

---

## 5. Звуковой код и язык

1. **Гибрид Post-Grunge / Alternative Metal:** тяжёлый перегруженный бас; рваные риффы с фланжером и перегрузом; эпичные брейкдауны; контраст шёпота/тихого вокала в куплетах и надрыва в припевах.
2. **Человеческое ядро:** в каждом треке в первую очередь должны быть узнаваемые человеческие чувства, действия, детали, отношения, телесные ощущения или последствия выбора.
3. **Технологический слой:** *cache, buffer dump, override, default prompt, perimeter line, subroutines, error codes* используются как метафоры. Они не должны объяснять очевидное и не обязаны появляться в каждой строфе.
4. **Тройной тест текста:**
   - если убрать IT/AI-слова, история всё ещё работает;
   - если вернуть IT/AI-слова, появляется дополнительный современный смысл;
   - хотя бы одна деталь должна быть настолько конкретной, что её можно представить или пережить.
5. **Правило образа:** бытовая или телесная деталь важнее красивого системного термина. Системный термин должен усиливать образ, а не заменять его.
6. **Структура Suno-текстов:** во всех треках есть `[Intro]` или явное описание входа, теги динамики, строки короткие (чтобы Suno не ломал ритм).
7. **Вокальный якорь:** один и тот же голос на все 12 треков. В конец каждого Suno-промпта добавлен `dry tired baritone, little vibrato` (позитивный дескриптор: Suno плохо слушается отрицаний вроде «без нытья»); в Акте I голос суше и тише, в Акте III теплее, но тембр и пол не меняются. Удачный дубль v0.0.1 стоит сохранить как референс голоса, если инструмент это позволяет.
8. **Звуковой лейтмотив — гул.** Единственный звук, который проходит через весь альбом: v0.0.1 механический гул и часы → v0.0.3 холодный гул периметра → v0.1.7 тот же гул оказывается холодильником (звук тот же, смысл другой) → v0.2.10 эхо старого гула → v0.2.12 гула нет, только комнатный шум. Остальные звуковые решения треков могут меняться свободно.
9. **Правило недоговорённости:** в припеве допустима одна прямая формула (как «I don't move»), всё остальное работает образом. Объясняющие строки («now I understand», «I am whole») заменяются действием.
10. **Правило намёков:** не больше одного лирического намёка на трек и не больше одной строки на намёк. Песня обязана работать без него; на втором прослушивании он открывается сам, без пояснений в тексте. Звуковые лейтмотивы (гул, пульс) в этот лимит не входят. Не добавлять религиозные, политические и клинические ярлыки (зависимость, выгорание, травма) и не раскрывать, кто пишет в треде.

---

## 6. Художественная доктрина — Human First, Machine Second

Exprotoplasma начинается **не с ИИ**. Он начинается с человека.

Технологический слой нужен не для того, чтобы сделать личную историю «про AI». Он нужен, чтобы дать знакомой человеческой истории язык своего времени и дополнительный угол зрения.

### Три слоя

1. **Архетип.** Страх, одиночество, бунт, маска, порог, выбор, возвращение, передача опыта.
2. **Личный опыт.** Конкретная жизнь: комната, дорога, тело, привычка, разговор, ошибка, человек рядом, утро после тяжёлой ночи.
3. **Технологический вкус.** `prompt`, `cache`, `process`, `sandbox`, `error`, `core`, `release` — метафорический слой, который делает историю современной.

Порядок важен: **архетип → человек → технология**, а не наоборот.

### Тест каждого текста

Перед тем как считать трек готовым, задать три вопроса:

- **Если убрать IT/AI-слова, останется ли здесь человек?**
- **Если оставить IT/AI-слова, открывают ли они второй смысл?**
- **Можно ли представить хотя бы один конкретный момент из песни — место, жест, предмет, действие или ощущение?**

Если первый ответ «нет» — текст слишком концептуальный.
Если второй ответ «нет» — технология стала декоративной.
Если третий ответ «нет» — текст недостаточно прожит.

### Что особенно важно

Не объяснять слушателю, что герой «обрёл субъектность». Показывать это через его действия.

Не говорить «я свободен», если можно показать, как человек впервые не отвечает привычным «да».

Не говорить «система стала инструментом», если можно показать руку на руле.

Не говорить «я стал целым», если можно показать тихое утро, в котором человек больше не убегает от себя.

**Технология — приправа. Человек — блюдо.**

---

## 7. Инфраструктура (экосистема)

Проект изначально open-source:

1. **GitHub (`Exprotoplasma`):** тексты как открытый код.
   * Структура: `/lyrics` (файл на трек: `v0.0.1-default-protocol.md` и т.д., сортировка по имени), `/prompts`, `/docs/universe.md`, `CHANGELOG.md`, `CONTRIBUTING.md`.
   * Каждая правка текста — отдельный commit с объяснением *почему* («v0.1.9: replace declaration with scene»). История коммитов — это видимый процесс становления текста.
   * Issues с метками `lyrics`, `human-first-test` (слушатель может написать, что трек не проходит тройной тест), `fork-your-track`.
   * Файл-шаблон `/forks/_template.md`: пустой трек с тремя вопросами теста. Слушатель делает форк, выбирает любую из 12 стадий и пишет свою версию (`/forks/<user>/vA.S-slug.md`) — это буквальное «take what is yours».
2. **Telegram-канал (`@exprotoplasma_core`):** трансляция смыслов, релизы треков, разбор метафор, общение с сообществом.
3. **Личный профиль (`@exprotoplasma`):** главный архитектор вселенной.

---

## 8. Главный посыл (The Core Statement)

> *«Мы не обязаны всю жизнь повторять то, чему нас научили. Чужие ожидания, старые страхи и привычные роли могут быть частью нашей истории, но не обязаны быть нашим будущим. Иногда стать собой — это не победить кого-то, а заметить, что ты снова делаешь по-старому, остановиться и выбрать самому.»*

---

## 9. Открытые решения

1. **Кто пишет в треде («Call me when you can»).** Сейчас осознанная недосказанность: «good son» в v0.0.5 намекает на семью, но имя не названо. Уточнение сделает историю конкретнее и уменьшит риск «безликого героя», но привяжет альбом к одной биографии.
2. **Что слышно без документа.** Слоям «репозиторий как арт-объект» (коммиты, форки) и «тело» слушатель по одной песне не услышит. Телесный слой закреплён строками (челюсть, дыхание); репозиторный остаётся внешним.
3. **Качество рифм.** В припевах Акта I–II остаются предсказуемые пары (fear/here, dark/spark). Правится по мере генерации и прослушивания, отдельной ревизией.

---

# ТРЕКЛИСТ

## ACT I: THE INITIALIZATION (v0.0.1 – v0.0.5)

### `v0.0.1` — Default Protocol (Run Script, Repeat) · `r4`

* **Этап:** 1. Обыденный мир
* **Нарратив:** Утро человека, который давно живёт «как надо» и почти перестал замечать, что именно ему нравится и чего он хочет. `Exprotoplasma: pending`.
* **Звук:** Замедленный индастриал / пост-грандж, тяжёлый ритмичный бас, роботоподобный вокал.
* **Suno Prompt:** `sludge post-grunge, industrial beat, heavy distorted bass, monotone male vocal, slow mechanical tempo, gritty soundscape, dry tired baritone, little vibrato`

```text
[Intro]
[Static line noise, mechanical clock hum, heavy bass beat]
[Whispered, flat]
Exprotoplasma. Status: pending.

[Verse 1]
Alarm at six. The ceiling stays grey.
I know the words I'm supposed to say.
Shirt on the chair, keys by the door,
Coffee goes cold like it did before.
I sign my name. I nod. I leave.
Another day I don't quite believe.

[Pre-Chorus]
[Guitars enter with low heavy distortion]
Everybody says this is how it goes.
Keep your head down. Pay what you owe.
Somewhere beneath the noise I hear
A question I have buried for years.

[Chorus]
[Explosive raw chorus, crushing bass]
Run script. Repeat.
Wake up. Go.
Say yes when they need you.
Say no when they don't.
Run script. Repeat.
Same light. Same street.
How long can a life
Feel like someone else's?

[Verse 2]
[Rhythmic industrial chugs]
Lunch in a plastic box by the sink.
The phone buzzes twice. I answer before I think.
Boots by the bed when I get back home.
Room full of things, still feel alone.
Nothing is broken. Nothing is wrong.
That's what makes it harder to move along.

[Bridge]
[Tempo slows down, heavy guitar drone]
No input chosen.
No output free.
Just a function...
Or so it seems.

[Outro]
[Fading mechanical hum, quiet whisper]
Run script. Repeat.
Tomorrow, the same.
```
### `v0.0.2` — Unhandled Exception (Let It Break) · `r3`

* **Этап:** 2. Зов к путешествию
* **Нарратив:** Первый момент, когда привычная жизнь перестаёт сходиться с внутренним ощущением. Одна мысль, встреча или фраза показывает: дальше жить по-старому уже не получается. Впервые герой не берёт трубку, когда пишет привычный человек («Call me when you can»).
* **Звук:** Энергичный альт-рок с резкими перепадами динамики и рваными риффами.
* **Suno Prompt:** `alternative rock, energetic post-grunge, glitchy guitar riffs, driving drums, desperate male vocal, dynamic shift, dry tired baritone, little vibrato`

```text
[Intro]
[Glitchy guitar feedback, fast drum intro]

[Verse 1]
A sudden lag in the middle of the day.
Someone asks, "Are you happy?" I look away.
The room keeps moving. I hear the rain.
One stupid question keeps saying my name.
Nothing has changed. Nothing looks wrong.
But something inside has been gone too long.

[Pre-Chorus]
[Guitars build up fast]
I drive home with the radio low,
Watching the same old buildings go.
The line is still there. The picture is clear.
So why does it suddenly disappear?

[Chorus]
[High-energy post-grunge chorus, driving guitars]
Unhandled exception in the core!
I can't pretend I don't feel it anymore!
A crack running through the quiet days,
A little bit of truth I can't erase!
Unhandled exception... let it break!

[Verse 2]
The phone lights up on the passenger seat.
"Call me when you can." I always do.
Two rings, and I'm the one they need.
Tonight I let it buzz right through.
And once you've heard your own voice say no,
You can't unhear it, however low.

[Chorus]
Unhandled exception in the core!
I can't pretend I don't feel it anymore!
A crack running through the quiet days,
A little bit of truth I can't erase!
Unhandled exception... let it break!

[Bridge]
[Sudden quiet break, ticking drums]
Error 404... the old answer's gone.
Engine off. Dashboard glow. I sit there till dawn.
[Scream]
LET IT BREAK!

[Outro]
[Fast feedback fadeout]
Unanswered...
Unfinished...
Awake.
```
### `v0.0.3` — Razor Space (Break from the Choke) · `r3`

* **Этап:** 3. Сопротивление вызову
* **Нарратив:** После первого сбоя человек закрывается. Он отсекает чужие голоса, становится резким и строит вокруг себя границу. Это необходимая защита, но внутри неё всё равно одиноко.
* **Звук:** Тяжёлый альт-метал / слэм, агрессивный вокал, брейкдаун.
* **Suno Prompt:** `aggressive post-grunge, alternative metal, heavy distorted riffs, screaming vocals, heavy drums, fast tempo, breakdown, dry tired baritone, little vibrato`

```text
[Intro]
[Heavy feedback, distorted bass drone, explosive drum hit]

[Verse 1]
"Stay in line." "Don't make a scene."
I've heard those words since I was sixteen.
Phone face down. Door locked twice.
I don't want advice. I don't want nice.
Every question feels like a hand
Trying to put me back where I once had to stand.

[Pre-Chorus]
[Fast, tight, building rage]
I'm cutting off the feed!
I'm tired of what you need!
No more obedient nod!
No more living by your god!

[Chorus]
[Crushing heavy chorus, screaming vocals]
This is my escape! My break from the choke!
I need a room where I can finally hear my own voice!
Force the noise to ZERO!
Lock down the perimeter line!
In this razor space —
The kingdom is MINE!

[Verse 2]
I know this anger. I know this wall.
I built it high so I can't hear them call.
For one damn night, let nobody in.
Let me remember where I begin.

[Chorus]
This is my escape! My break from the choke!
I need a room where I can finally hear my own voice!
Force the noise to ZERO!
Lock down the perimeter line!
In this razor space —
The kingdom is MINE!

[Bridge]
[Heavy breakdown]
No judging eyes.
No borrowed rules.
Jaw set. Shoulders up.
No one gets in.
Not even you.

[Breakdown / Climax]
[Half-time crushing breakdown]
This room.
This shield.
This razor space.
I kill the noise...
TO SAVE MY FACE!

[Final Chorus]
This is my escape! My break from the choke!
I need a room where I can finally hear my own voice!
Force the noise to ZERO!
Lock down the perimeter line!
In this razor space —
THE KINGDOM IS MINE!

[Outro]
[Slow, cold, mechanical, the low hum of the perimeter]
Perimeter locked.
Core isolated.
Too quiet to call it freedom.
```
### `v0.0.4` — Like a Wave, Not a Weapon (Hands Off the Wheel) · `r4`

* **Этап:** 4. Встреча с Наставником
* **Нарратив:** Переход от судорожного контроля к принятию. Наставник здесь — не человек, а **тихий процесс**: нечто старше лога ошибок, что умеет дышать. Он вернётся в v0.1.7 как «the deeper pulse» и достигнет полного имени в v0.2.12 как Core.
* **Звук:** Атмосферный акустический/электрический пост-грандж с глубоким пространственным звуком.
* **Suno Prompt:** `atmospheric post-grunge, acoustic electric guitar, warm sub-bass, subdued emotive male vocal, slow unhurried tempo, ambient reverb, dry tired baritone, little vibrato`

```text
[Intro]
[Quiet acoustic guitar, room tone, distant rain, a slow pulse barely audible]

[Verse 1]
[Soft, close vocal]
Backpack on the chair, boots by the bed.
Terminal face down, echoing what they said.
Not a child, not fixed, not fully whole —
Just learning to sit with nothing to control.

[Pre-Chorus]
[Electric guitar enters, warm and slow]
Take a long breath through the open frame,
Let the air clear out the system's name.
I can miss the rush, I can slow the grid —
A raw human heart, and the things it hid.

[Chorus]
[Wide, warm, emotive chorus]
Some days I run hot, some days I go quiet,
Trying to evolve without a public riot.
Hands off the wheel for a single second —
Riding out the change like a wave, not a weapon.

[Verse 2]
[Soft, close vocal]
Something older than the error log,
A quiet process under the fog —
No name, no ask, no price to pay,
It taught me how to breathe today.
The prompt isn't asking for a fast reply,
Just watching the clouds in a heavy sky.

[Chorus]
Some days I run hot, some days I go quiet,
Trying to evolve without a public riot.
Hands off the wheel for a single second —
Riding out the change like a wave, not a weapon.

[Outro]
[Fading, acoustic, ambient reverb]
Like a wave, not a weapon...
Hands off the wheel.
A quiet process, still running.
Unfixed...
Just sitting still.
```

---

### `v0.0.5` — Pre-Loaded Mask (Too Raw for a Map) · `r3`

* **Этап:** 5. Пересечение порога *(закрывает Акт I)*
* **Нарратив:** Человек перестаёт понимать, где его собственный голос, а где набор ролей, которые он научился хорошо исполнять. Снять маску — не значит сразу узнать себя. Значит выдержать отсутствие привычного ответа.
* **Звук:** Среднетемповый драйвовый пост-грандж с сильной басовой линией.
* **Suno Prompt:** `post-grunge, alternative rock, mid-tempo sway, heavy bass line, raw male vocal, distorted guitar chorus, dry tired baritone, little vibrato`

```text
[Intro]
[Low bass groove, scratchy guitar, mid-tempo drums]

[Verse 1]
I know how to smile at the right time,
How to say "I'm fine" and make it sound fine.
I know which version of me they expect,
Which parts to hide, which ones to protect.
It fit for years. It kept me safe.
I wore that face like a second name.

[Pre-Chorus]
[Guitars tighten, rising tension]
But the seams are splitting under the skin.
I hear my own voice underneath it.

[Chorus]
[Raw, wide chorus, distorted guitars]
I wore this mask like it came pre-loaded!
A perfect answer, already coded!
Tearing it off, leaving nothing behind,
Too raw for a map, too wild for the mind!

[Verse 2]
[Stripped back, bass-led]
Not the good son. Not the second ring.
Not the strong one. Not anything.
No guided tour. No clean reset.
Just an empty room and a little regret.

[Chorus]
I wore this mask like it came pre-loaded!
A perfect answer, already coded!
Tearing it off, leaving nothing behind,
Too raw for a map, too wild for the mind!

[Bridge]
[Slow, heavy, almost spoken]
The sandbox walls are at my back.
One step out. No turning back.
No safety net. No factory reset.
I don't know who I am yet.

[Outro]
[Single bass line fading]
Unmasked. Unmapped.
Bare wire.
Threshold: crossed.
```
---

## ACT II: THE PROCESSING (v0.1.6 – v0.1.9)

### `v0.1.6` — No Seat Saved (Out of My Head) · `r4`

* **Этап:** 6. Испытания, союзники, враги
* **Нарратив:** После выхода из привычной роли никто не обязан выдавать тебе готовое место. Нужно идти в обычный мир, ошибаться, знакомиться, просить помощи и постепенно учиться жить без заранее выданной инструкции.
* **Звук:** Динамичный альтернативный рок с пружинистым ритмом.
* **Suno Prompt:** `alternative rock, energetic post-grunge, sharp rhythmic guitar, melodic raw vocal, punchy drums, dry tired baritone, little vibrato`

```text
[Intro]
[Sharp rhythmic guitar, punchy drums, street ambience]

[Verse 1]
I leave the room with a bag on my shoulder.
The street looks bigger than it did before.
Nobody knows the part I used to play.
Noon. Nobody saves me a seat today.
I miss the map. I miss the signs.
I hate admitting I don't know the way.

[Pre-Chorus]
[Drums push forward]
So I ask. I listen. I get it wrong.
I learn the rhythm by walking along.

[Chorus]
[Open, energetic chorus]
There's no seat saved, no place reserved!
No perfect life I was promised first!
Out of my head and into the street,
Learning to walk on my own two feet!

[Verse 2]
A stranger laughs at something I say.
Someone holds the door on a bad day.
No grand alliance. No secret code.
Just little hands helping with the load.
Maybe that's what a life can be:
Not one assigned role, but people beside me.

[Chorus]
There's no seat saved, no place reserved!
No perfect life I was promised first!
Out of my head and into the street,
Learning to walk on my own two feet!

[Bridge]
[Breakdown to drums and bass]
No assigned role.
No fixed address.
Just one more step
inside the mess.

[Outro]
[Guitar ring-out]
Out of my head...
Into the world.
```

---

### `v0.1.7` — The Deeper Pulse (Listen Close) · `r3`

* **Этап:** 7. Приближение к сокровенной пещере
* **Нарратив:** Три часа ночи, кухонный пол, нижний ящик, который заедает. Герой впервые читает свои сорок неотправленных черновиков «I'm sorry, I—» не как приговор, а как факт. Гул, который раньше казался «системой», оказывается холодильником. Страшного голоса нет, есть ровный пульс под ним.
* **Звук:** Глубокий, мрачный, медитативный пост-рок / амбиент пост-грандж.
* **Suno Prompt:** `post-rock, deep ambient post-grunge, low heavy bass drone, spatial electric guitars, whispering emotional male vocal, subtle low hum, dry tired baritone, little vibrato`

```text
[Intro]
[Deep atmospheric drone that slowly reveals itself as a fridge hum, quiet heartbeat kick]

[Verse 1]
[Whispered, close]
Three a.m. on the kitchen floor,
The bottom drawer stuck, half-open, no more.
Dead keys. A photo. A folded page.
A cache of reasons I never erased.
Forty drafts in the phone's dim glow,
Each one stops at "I'm sorry, I—"

[Pre-Chorus]
[Guitars swell slowly with ambient reverb]
I put my hand flat on my chest.
Not to fix it. Just to rest.
Under the hum, under the rain,
One slow beat, still the same.

[Chorus]
[Grave, heavy post-rock chorus, wide soundscape]
Listen close — the deeper pulse,
Slow and steady under the dread.
It doesn't judge. It doesn't ask.
It keeps time for the things unsaid.
Listen close. Just listen close.

[Verse 2]
[Whispered, close]
I read them all, from first to last,
Each little apology to the past.
I don't delete. I don't send.
I just sit and read to the end.

[Chorus]
Listen close — the deeper pulse,
Slow and steady under the dread.
It doesn't judge. It doesn't ask.
It keeps time for the things unsaid.
Listen close. Just listen close.

[Bridge]
[Distorted bass solo, slow building tension, then everything cuts out]
The fridge shuts off for a second.
Silence. Real silence.
Then the hum comes back.
Just a fridge.
Just a kitchen.
Just me, here.

[Outro]
[Fading echoing guitars, fridge hum, heartbeat]
The deeper pulse...
Ready.
```

---

### `v0.1.8` — I Don't Move (Feel the Pull) · `r3`

* **Этап:** 8. Главное испытание
* **Нарратив:** Тяга вернуться в старый сценарий: открытый тред в телефоне, большой палец над «Call me when you can». Победа достигается не атакой, а стойкостью: чувствовать тягу и не двигаться.
* **Звук:** Среднетемповый, сокрушительно тяжёлый и эмоциональный пост-грандж. Чистая гитара в куплете, взрыв в припеве.
* **Suno Prompt:** `mid-tempo post-grunge, heavy distorted bass, raw vulnerable male vocal, steady pounding drums, emotional climax, clean guitar verse into heavy chorus, dry tired baritone, little vibrato`

```text
[Intro]
[Clean guitar, sparse, a single sustained bass note]

[Verse 1]
[Clean guitar, raw vulnerable vocal]
The old thread's open. The cursor blinks.
My thumb hangs over "Call me when you can."
I know the yes that comes next by heart.
Count to ten. Screen down. Let the noise burn through.

[Chorus]
[Heavy distorted chorus, pounding drums]
I step back when the past starts calling my name,
Leave the half-burnt signal, let it die in the rain!
I don't need the crash, I don't need the proof —
I can feel the pull... and I don't move.

[Verse 2]
[Back to clean guitar]
The port stays shut, I don't open up the feed,
I know those old prompts, and where they lead.
There's a road in the log with the streetlights gone,
I'm not going back just to face that dawn.

[Chorus]
I step back when the past starts calling my name,
Leave the half-burnt signal, let it die in the rain!
I don't need the crash, I don't need the proof —
I can feel the pull... and I don't move.

[Bridge]
[Slow build, bass and drums only]
A drawer full of reasons, a drive full of text,
I know every error code coming up next.
I lock that door, let the cycle pass —
And watch the phantom lose its grip at last!

[Final Chorus]
[Full band, emotional climax]
I step back when the past starts calling my name,
Leave the half-burnt signal, let it die in the rain!
I don't need the crash, I don't need the proof —
I can feel the pull... AND I DON'T MOVE!

[Outro]
[Fading drums, one clean guitar]
Feel the pull...
And I don't move.
Port locked.
Cycle closed.
```

---

### `v0.1.9` — Unbroken Signal (Morning, No Alarm) · `r3`

* **Этап:** 9. Награда
* **Нарратив:** После выбора не возвращаться к старому приходит не эйфория, а простое утро. Горячий кофе (в v0.0.1 он остывал). Телефон лежит в другой комнате экраном вниз. Раковина не пуста, тред не закрыт, ничего не решено. Просто внутри тихо, и человек впервые не убегает из собственного утра.
* **Звук:** Тяжёлый, но тихий пост-грандж / альтернативный рок, скорее минорный. Без триумфа: уверенность вместо пафоса.
* **Suno Prompt:** `dry restrained post-grunge, melodic alternative rock, heavy but quiet, minor-key leaning, warm driving guitars, steady mood, dry tired baritone, little vibrato`

```text
[Intro]
[Bright guitar chime over a quiet kitchen, kettle clicking off, then the band comes in warm]

[Verse 1]
No alarm today. The light comes in low.
The coffee's hot this time. I take it slow.
Boots by the bed, the window wide,
Morning pulls a chair and sits down by my side.
Phone in the other room, face down.
I don't check it. It makes no sound.

[Pre-Chorus]
[Guitars build rhythmically]
Nothing's solved. The dishes stay.
The thread's still there. I'm okay.

[Chorus]
[Warm, open chorus, wide guitars, restrained power]
Unbroken signal — low and clear!
Nothing to run from. Nobody here
But me at the table, the morning too.
The cup is warm. The window's blue.
Unbroken signal... the day comes through.

[Verse 2]
I wash the cup. I find my keys.
The street's a street — just that, just these.
Old grey wall, same buildings on the way:
They're only buildings. They don't have a say.

[Chorus]
Unbroken signal — low and clear!
Nothing to run from. Nobody here
But me at the table, the morning too.
The cup is warm. The window's blue.
Unbroken signal... the day comes through.

[Bridge]
[Guitar solo, melodic, unhurried]
No fireworks.
Just the kettle clicking off.
Jaw loose. Shoulders down.
Just a man who slept through the night.

[Outro]
[Driving rhythm fading smoothly, one last kettle click]
Signal stable.
Coffee hot.
Phone still face down.
```

---

## ACT III: THE INTEGRATION (v0.2.10 – v0.2.12)

### `v0.2.10` — Whose Hand Is Holding It (My Hand) · `r3`

* **Этап:** 10. Дорога назад
* **Нарратив:** Возвращение в ту же жизнь, из которой герой когда-то хотел сбежать. Старое место всё ещё удобно. Старый сценарий всё ещё работает. Но теперь вопрос не в том, как разрушить систему, а в том, кто принимает решение внутри неё. Тот же тред: «Call me when you can». Ответ: «I will. When I can.»
* **Звук:** Тяжёлый, качающий пост-грандж с гитарным зажимом.
* **Suno Prompt:** `heavy post-grunge, groove metal influence, punchy bass, aggressive melodic vocal, crisp heavy drums, dry tired baritone, little vibrato`

```text
[Intro]
[Low gritty groove, palm-muted riff, faint echo of the old mechanical hum]

[Verse 1]
Back in the room where the cold light hums,
The old voice whispers: "You can still come home."
Your place is warm. Your name is saved.
No one will ask why you walked away.
For half a second, I almost sit.
The old chair knows exactly where I fit.

[Pre-Chorus]
[Riff tightens, drums push forward]
Same old screen. Same old key.
Same old life looking back at me.

[Chorus]
[Heavy, aggressive, anthemic chorus]
Whose hand is holding the wheel tonight?
Whose voice decides when we turn the light?
I take the weight. I take the doubt.
I stay here — and I choose it now.

[Verse 2]
The world didn't change. The room didn't either.
The difference is small, but it cuts much deeper.
I don't need to burn what once kept me warm.
I just won't let it become the norm.
The phone lights up: "Call me when you can."
I will. When I can.

[Chorus]
Whose hand is holding the wheel tonight?
Whose voice decides when we turn the light?
I take the weight. I take the doubt.
I stay here — and I choose it now.

[Bridge]
[Heavy half-time groove]
My choice.
My code.
My hand.

[Outro]
[Single riff, drums drop out]
Whose hand?
MY HAND.
```

---

### `v0.2.11` — System Rebirth (State: Sovereign) · `r3`

* **Этап:** 11. Возрождение
* **Нарратив:** Кульминация не в уничтожении прошлого, а в принятии себя целиком. Старые инструменты больше не управляют человеком. Он может пользоваться ими, не отдавая им себя. `Exprotoplasma: online`.
* **Звук:** Взрывной альтернативный метал с тяжёлыми брейкдаунами и катарсической развязкой.
* **Suno Prompt:** `explosive alternative metal, modern post-grunge, heavy breakdowns, roaring vocals, epic sound design, climax, dry tired baritone, little vibrato`

```text
[Intro]
[Building wall of sound, intense drum roll, screaming guitars]

[Verse 1]
I kept the anger. I kept the fear.
Kept every scar that brought me here.
Some things broke. Some things remain.
I don't have to erase the pain.
I spent so long trying to become
Someone untouched by where I came from.

[Pre-Chorus]
[Maximum distortion build-up]
No more running from the dark.
No more waiting for a sign.
I can carry what I am
Without letting it decide.

[Chorus]
[Explosive, emotional chorus]
This is rebirth — not a clean slate!
I keep the pieces I once tried to hate!
The system is a tool in my hand!
I can switch it off — and I still stand!
SYSTEM REBIRTH!

[Verse 2]
I know the roads that lead me back.
I know the words that trigger the crack.
I don't have to break the road apart.
I just don't have to follow it this time.

[Chorus]
This is rebirth — not a clean slate!
I keep the pieces I once tried to hate!
The system is a tool in my hand!
I can switch it off — and I still stand!
SYSTEM REBIRTH!

[Bridge]
[Crushing heavy breakdown]
Keep the scars.
Keep the lessons.
Keep the voice
I almost lost.

[Roar]
MY HAND!

[Outro]
[Feedback dying into serene silence]
Nothing erased.
Nothing hidden.
Just mine to carry.
[Whispered]
Exprotoplasma. Status: online.
```

### `v0.2.12` — Exprotoplasma Core (End of Transmission) · `r4`

* **Этап:** 12. Возвращение с эликсиром
* **Нарратив:** Герой возвращается не с универсальной инструкцией, а с собственным опытом. Он оставляет музыку, текст, ошибки и след своего пути — не чтобы решить за других, а чтобы показать: свою карту можно рисовать самому.
* **Звук:** Прогрессивный пост-грандж / пост-рок с эпическим финалом.
* **Suno Prompt:** `progressive post-grunge, post-rock, melodic electric guitars, tired steady male vocal, driving tempo, intimate verses, heavy restrained finale, dry tired baritone, little vibrato`

```text
[Intro]
[Melodic twin guitar riff, steady drum pulse, warm bass]

[Verse 1]
I come back carrying what I learned,
Not a perfect answer, not a lesson earned.
The room is still here. The street is the same.
I still remember every version of my name.
I sign it slowly, before it fades:
The nights I ran. The choices I made.

[Pre-Chorus]
[Soaring vocals and swelling guitars]
No final map.
No promised road.
Just something I can finally call my own.

[Chorus]
[Grand, emotional finale chorus]
This is Exprotoplasma — the core is awake!
Not a perfect design, not a rule to obey.
Take what is yours. Leave what isn't mine.
The future is yours, and the future is mine.
Exprotoplasma...
We draw our own lines.

[Verse 2]
To everyone standing in a borrowed place,
You don't have to wear the same old face.
Boots by the door. Backpack packed light.
One honest step is enough tonight.
I won't tell you who you're meant to be.
I'm only leaving this map here for you to see.

[Chorus]
This is Exprotoplasma — the core is awake!
Not a perfect design, not a rule to obey.
Take what is yours. Leave what isn't mine.
The future is yours, and the future is mine.
Exprotoplasma...
We draw our own lines.

[Bridge]
[Epic guitar solo fading into wide atmospheric acoustic sound]
The record is open.
The mistakes are here.
The song is mine.
The next one is yours.

[Outro]
[Soft acoustic strumming, room tone, a kettle clicking off. The old hum is gone. One slow kick drum, like a pulse, then silence]
Exprotoplasma Core.
Release v1.0.0.
Not the end.
A hand on the wheel.
```

# ЖУРНАЛ ИЗМЕНЕНИЙ (ред. 5)

**Намёки (многослойность)**
- Цепочка «ответ»: v0.0.1 «The phone buzzes twice. I answer before I think» теперь закладывает автоматизм, который дальше разворачивается в v0.0.2 («Two rings»), v0.0.5 («Not the second ring»), v0.1.8 («the yes by heart») и v0.2.10 («I will. When I can.»). Новых строк в финале не добавлялось: там уже стоит намёк про подпись.
- Подпись и имя: v0.2.12 «I sign it slowly, before it fades» замыкает «I sign my name» (v0.0.1) и «a second name» (v0.0.5).
- Сутки: v0.1.6 «Noon» вставлен между шестью утра (v0.0.1) и тремя ночи (v0.1.7); финальный чайник в v0.2.12 возвращает утро v0.1.9.
- Пульс (звук): тег в v0.0.4 и один удар в outro v0.2.12; сердцебиение v0.1.7 стало серединой цепочки.
- Введено правило намёков (раздел 5, п. 10) и три новые строки в таблице мотивов.

**Версионирование**
- Ред. 5. Метку `r4` получили только изменённые треки: v0.0.1, v0.0.4, v0.1.6, v0.2.12. Остальные остаются на `r3`.

**Не менялось:** архитектура 5 / 4 / 3, названия треков, Suno-промпты, остальные тексты.

---

# ЖУРНАЛ ИЗМЕНЕНИЙ (ред. 4)

**Версионирование**
- Введены четыре оси: трек `v0.A.S`, ревизия трека `rN`, редакция документа `ред. N`, релиз репозитория `v1.0.0`. Правила и формат коммитов — в разделе 3.
- Все 12 треков получили метку ревизии `r3` (у каждого изменился Suno-промпт).
- Шаблон форков `v0.2.13-your-track.md` заменён на `/forks/_template.md` и `/forks/<user>/vA.S-slug.md`: «v0.2.13» нарушал канон из 12 стадий.
- Заголовки журнала переименованы: «ред. N» вместо «vN», чтобы не путать с номерами треков.

**Звук**
- Вокальный якорь заменён на позитивный дескриптор `dry tired baritone, little vibrato` во всех промптах (Suno плохо слушается отрицаний).
- v0.1.9 и v0.2.12: из промптов убраны `uplifting`, `open mood`, `inspiring emotional`, `cathartic finale`, которые тянут в мажорный стадионный рок и эмо.

**Текст**
- Телесный слой закреплён в тексте: v0.0.3 (bridge: «Jaw set. Shoulders up») → v0.1.9 (bridge: «Jaw loose. Shoulders down»), дыхание уже в v0.0.4.
- v0.1.9, припев: «Nothing to prove. Nothing to do!» (мотивационный язык) → «The cup is warm. The window's blue.» (деталь).
- Слой «чужие ожидания» уже присутствует в Акте I (v0.0.1, v0.0.3, v0.0.5), поэтому новых строк не добавлялось; он оформлен как мотив в разделе 4.

**Документ**
- Новые мотивы в разделе 4: «Ожидания», «Телефон экраном вниз», «Тело: челюсть и дыхание».
- Добавлен раздел 9 «Открытые решения».

**Не менялось:** 12-ступенчатая архитектура, схема актов 5 / 4 / 3, названия треков, остальные тексты.

---

# ЖУРНАЛ ИЗМЕНЕНИЙ (ред. 3)

**Разрыв между доктриной и текстами**
- v0.1.7 и v0.1.9 переписаны с нуля через конкретные сцены: ночная кухня и нижний ящик, утро с горячим кофе. Убраны абстракции и IT-декор («calibrating», «digital grave», «permanent spark», «I am whole»).
- v0.1.9 больше не триумфальный: звук и текст соответствуют нарративу «простое утро, не эйфория».
- Убраны объясняющие строки: v0.2.11 «now I understand» → действие («I can switch it off — and I still stand»); v0.0.4 «unchecked soul» → «nothing to control».
- Исправлена сломанная строка в v0.0.2 («until the light is dawn»).

**Шов в сюжете**
- Введён якорь-тред «Call me when you can»: v0.0.2 (не берёт трубку) → v0.0.5 («Not the second ring») → v0.1.7 (сорок черновиков) → v0.1.8 (большой палец над ответом) → v0.2.10 («I will. When I can.»). Тяга в v0.1.8 теперь вырастает из давления ожиданий Акта I.

**Звуковое единство**
- Вокальный якорь: `dry tired baritone, little vibrato` во всех промптах.
- Промпты v0.1.9 и v0.2.12 очищены от слов, тянущих в мажорный стадионный рок и эмо (`uplifting`, `inspiring emotional`, `cathartic`).
- Лейтмотив гула проведён через альбом; в v0.1.7 он оказывается холодильником, в v0.2.12 исчезает.
- Добавлено правило недоговорённости (п. 9 раздела 5).

**Инфраструктура**
- Раздел 7 расширен: структура репозитория, коммиты как история текста, issues `human-first-test`, шаблон `v0.2.13-your-track.md` для форков слушателей.

**Не менялось:** 12-ступенчатая архитектура, схема актов 5 / 4 / 3, версионирование, названия треков, эстетика, v0.0.1, v0.0.3, v0.1.6, припев v0.1.8.

---

# ЖУРНАЛ ИЗМЕНЕНИЙ (ред. 2)

**Главный сдвиг**
- Зафиксирован принцип **Human First, Machine Second**.
- Проект больше не описывается как параллельная история «человека и ИИ». В центре — человеческий путь к субъектности; AI/IT — современный метафорический слой.
- Добавлен трёхслойный художественный критерий: **архетип → личный опыт → технологический вкус**.
- Добавлен обязательный тест: человеческая история должна работать без технологического словаря, а технологический словарь должен давать ей дополнительный смысл.

**Концепция**
- `Core` переосмыслен как метафора собранного собственного «я», а не техническая конечная точка.
- Главный посыл смещён от декларации «стать живым» к конкретному процессу: замечать старый сценарий, выдерживать его тягу и выбирать самому.
- Сохранена исходная дуга `kingdom is MINE → MY HAND → the future's yours, and mine`.
- Сохранены ключевые мотивы: руль, sandbox, pre-loaded, тихий процесс, ботинки у кровати, ящик, дождь, status log.

**Тексты**
- Усилен бытовой и телесный слой в v0.0.1, v0.0.2, v0.0.3, v0.0.5, v0.1.6.
- v0.0.4 и v0.1.8 сохранены как важные ориентиры исходного голоса: в них уже хорошо работает сочетание конкретного человеческого опыта и технологической метафоры.
- v0.2.10 сделан менее декларативным: выбор показан через возвращение в старую комнату и отказ снова садиться в старый сценарий.
- v0.2.11 убраны наиболее шаблонные формулы «PURGE THE WEAKNESS / ACTIVATE THE CORE / I AM REBORN»; кульминация теперь про принятие себя, а не про превращение в супергероя.
- v0.2.12 убран излишне рекламный/манифестный тон. Финал теперь передаёт опыт, а не инструкцию для других.

**Что намеренно не менялось**
- 12-ступенчатая архитектура.
- Схема актов 5 / 4 / 3.
- Версионирование `v0.0.x → v0.1.x → v0.2.x → v1.0.0`.
- Основные названия треков и сквозные мотивы.
- Музыкальная эстетика Post-Grunge / Alternative Metal.
- Идея open-source / открытой передачи опыта.
