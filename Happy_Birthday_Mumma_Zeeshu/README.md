# Happy Birthday Mumma ❤️

Zeeshu tarafthi Mumma mate banavelu responsive, static birthday experience. Site nu content Gujlish ma chhe. `index.html` ne local web server thi open karo (VS Code Live Server saral option chhe); koi backend ke database nathi.

## Photos mukvani rit

Tamari badhi 32 original photos `assets/images/gallery/photo-01.jpeg` thi `photo-32.jpeg` ma mukeli chhe. Gallery index pramane photo cards banave chhe; selected cards par Gujlish caption chhe. Original JPEG files quality jalavva mate convert ke crop karya vagar copy kari chhe. Gallery ane full-screen viewer ma photo no original aspect ratio jalvay chhe.

## Birthday music

`assets/music/instrumental.mp3` ma tamari emotional instrumental audio file muko. Music default OFF chhe; uparna Play control thi j chalu thashe. iPhone Safari ma audio user tap pachi j sharu thashe.

Three.js CDN thi load thay chhe; internet vagar baki website ane interactions chale chhe, pan Three.js particle field nahi dekhay. `vendor/` khali optional local library placement mate chhe.

## Mumma na quiz jawab

Quiz ma Mumma 10 jawab potana shabdo ma type kare chhe. Jawab e j browser ma automatically save thay chhe; pachi `Mumma na jawab juo` thi page par joi shakay chhe. Bijaa device par jovaa mate `Jawab download karo` thi text file download kari ne Zeeshu ne moklo. Static site ma jawab internet par upload/sync thata nathi.

## Folder structure

- `css/style.css` — responsive design, animation ane accessibility.
- `js/main.js` — gallery, lightbox, quiz, interactions ane Three.js particles.
- `assets/images/gallery/` — Mumma ni 32 original JPEG photos.
- `assets/music/` — instrumental music slot.
