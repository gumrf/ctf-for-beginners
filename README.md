# СTF for Beginers

**CTF** или соревнования по безопасности **Capture The Flag** — отличный способ научиться взламывать системы. Это соревнования, в которых участники соревнуются, пытаясь найти `«флаг»`, чтобы доказать, что они взломали систему.

## Почему стоит играть в CTF?

Это один из лучших способов освоить определенные навыки безопасности, такие как бинарная эксплуатация, веб-эксплуатация или реверс-инжиниринг.

## Виды CTF

Существует два основных вида CTF: `Jeopardy` и `Attack-Defense`.

CTF в стиле **Jeopardy** — это, по сути, список хакерских задач, которые вы можете выполнить для получения флагов, приносящих определенное количество очков. Эти задачи включают в себя использование уязвимости или решение задачи программирования, чтобы украсть `«флаг»`. Команды соревнуются, кто найдет больше флагов и наберет больше очков за отведенное время.

Хакерские испытания в CTF в стиле Jeopardy часто сортируются по уровням сложности, поэтому новички также могут легко принять в них участие. Часто есть разные наборы задач, из которых вы можете выбирать, от криптографии, реверс-инжиниринга, эксплуатаци двоичного кода, сети, программирования, форензики, сетевых задач до проблем, которые представляют собой сочетание некоторых или всех этих навыков.

Более продвинутой версией CTF является CTF в стиле `Attack-Defense`. В этих соревнованиях команды защищают свои серверы от атак и атакуют серверы противников, чтобы набрать очки. Эти CTF требуют больше навыков для участия в соревнованиях и почти всегда проводятся в командах.

## Необходимы навыки

Для новичков в СТF Jeopardy часто не требуются специальные технические навыки. В конце концов, это то, чему вы пытаетесь научиться! Тем не менее, хорошо иметь общее представление о том, как использовать `командную строку`, и иметь базовые знания в области программирования. Например, будет очень полезно изучить основы `Python`.
> Курс от [**Hexlet**](https://ru.hexlet.io/courses/python-basics)
> Курс на [**code-basics**](https://ru.code-basics.com/languages/python)

Более продвинутые технические навыки можно получить, выполнив более простые задания или погуглив. Также полезно быть в курсе последних новостей в области безопасности, поскольку задачи CTF часто основаны на недавно обнаруженных уязвимостях.

## Где играть в CTF?

Если вы хотите принять участие в CTF, загляните на [CTFtime.org](https://ctftime.org/), чтобы найти список текущих и предстоящих турниров CTF.

## Как подготовиться к CTF?

Начать решать задачи, постепенно накапливая опыт. Необязательно уметь решать сразу все задачи. Можно выбрать одно направление и углубиться в изучение его аспектов.

Для старта можно начать с Beginer-friendly СTF:

- [fokbomb](https://forkbomb.ru/tasks) by [SPbCTF](https://vk.com/spbctf)
- [picoCTF](https://picoctf.org/)
- [MetaCTF](https://metactf.com/cybergames)

YouTubers:

- [John Hammond](https://www.youtube.com/c/JohnHammond010)
- [David Bombal](https://www.youtube.com/c/DavidBombal)

### Crypto

В СТF задачах по криптографии цель обычно состоит в том, чтобы взломать или клонировать криптографические объекты или алгоритмы для получения флага.

Статья [Crypto for beginers(en)](https://charcharbinks.com/post/ctf_crypto_for_beginners/)

[Преезнтация по подбору паролей](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/JaysesS/4hsl33p_borda/main/flask/data/presentation/passwrd.pdf) от команды [4hsl33p](https://vk.com/gumrf_ctf)

[Презентация по крипте](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/JaysesS/4hsl33p_borda/main/flask/data/presentation/Crypto.pdf) от команды [4hsl33p](https://vk.com/gumrf_ctf)

- [CyberChef](https://gchq.github.io/CyberChef/)
- [CrackStation](https://crackstation.net/)
- Python

### Forensics

CTF задачи по `форензике/криминалистики` могут включать анализ формата файла, стеганографию, анализ дампа памяти или анализ захвата сетевых пакетов. Любая задача по изучению и обработке скрытой части информации из статических файлов данных (в отличие от исполняемых программ или удаленных серверов) может считаться задачей криминалистики (если только она не связана с криптографией)

[Презентация по форензике](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/JaysesS/4hsl33p_borda/main/flask/data/presentation/Forensics.pdf) от команды [4hsl33p](https://vk.com/gumrf_ctf)

[Презентация по стегонографии](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/JaysesS/4hsl33p_borda/main/flask/data/presentation/Stego.pdf) от команды [4hsl33p](https://vk.com/gumrf_ctf)

- [WireShark](https://www.wireshark.org/)
- R-Studio
- hexdump
- [010Editor](https://www.sweetscape.com/download/010editor/)
- [Audacity](https://www.audacityteam.org/)
- [Stegsolve](http://www.caesum.com/handbook/Stegsolve.jar)

### Web

Веб-задачи в соревнованиях CTF обычно включают использование HTTP (или аналогичных протоколов) и технологий, связанных с передачей и отображением информации через Интернет, таких как PHP, CMS (например, Django), SQL, Javascript и другие.

[Презентация по вебу](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/JaysesS/4hsl33p_borda/main/flask/data/presentation/Web.pdf) от команды [4hsl33p](https://vk.com/gumrf_ctf)

Tools:

- [WireShark](https://www.wireshark.org/)
- [Nmap](https://nmap.org/download.html)
- [gobuster](https://github.com/OJ/gobuster)
- [Postman](https://www.postman.com/)
- [Curl](https://curl.se/download.html)
- [BurpSuite](https://portswigger.net/burp/communitydownload)
- [SQLMap](https://github.com/sqlmapproject/sqlmap)

### Osint

OSINT задачи нацелена на посик информации из открытых источников

- [Поиск по картинкам](https://www.osintessentials.com/search-by-image)
- [Web Archive](https://web.archive.org/)

### Reverse

Реверс-инжиниринг в CTF обычно представляет собой процесс преобразования скомпилированной программы (машинный код, байт-код) в более удобный для человека формат.

[Презентация по реверсу](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/JaysesS/4hsl33p_borda/main/flask/data/presentation/Reverse.pdf) от команды [4hsl33p](https://vk.com/gumrf_ctf)

- [IDA by hex-rays](https://www.hex-rays.com/ida-free/#download)

## Conclusion

Have fun :wink:
