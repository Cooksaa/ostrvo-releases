# Ostrvo

Desktop AI agent za Windows: malo „ostrvo“ na vrhu ekrana (kao Dynamic Island) s maskotom Lens.
Drži **desni Ctrl** i pričaj, a agent radi s fajlovima, mailom, podsjetnicima i ekranom.

## Preuzimanje
**[⬇ Preuzmi zadnju verziju](../../releases/latest)** → `Ostrvo-Setup-x.y.z.exe`

- Windows 10/11 (64-bit), mikrofon
- Instalira se bez admin prava; kasnija ažuriranja stižu iz same aplikacije (jedan klik na ostrvu)
- Treba ti **Anthropic API ključ** ([console.anthropic.com](https://console.anthropic.com/settings/keys)):
  plaćaš samo ono što agent potroši (obično par dolara mjesečno), a mjesečni limit postaviš u aplikaciji

Pri prvom pokretanju Windows može reći „Windows protected your PC“ (program još nije digitalno potpisan):
klikni **More info → Run anyway**.

## Šta zna
- **Glasom:** pitanja, fajlovi na kompjuteru, otvaranje programa, clipboard, Word dokumenti, web pretraga;
  „Piši: …“ upiše tekst gdje ti je kursor; desni Ctrl + Shift = pitanje uz sliku ekrana
- **Obavještenja:** samo važni mailovi i hitne WhatsApp/Viber poruke, fokus režim dok radiš
- **Podsjetnici i bilješke glasom**, jutarnji brief (vrijeme, podsjetnici, mail), sedmični pregled
- **Polica** za fajlove, **SD kartica** (kopira slike u pravi folder, nikad ne briše s kartice)
- **Potrošnja** API-ja po danu i modelu, s mjesečnim limitom

## Privatnost i sigurnost
- Sve radi na tvom kompjuteru. Ključevi i lozinke su u Windows Credential Manageru, podaci u `%APPDATA%\Ostrvo`.
- Agent **nikad ne briše** fajlove i **ništa ne šalje** u tvoje ime; prepisivanje i premještanje uvijek čeka tvoju potvrdu.
- Mail se samo čita (IMAP, lozinka za aplikacije).

Problemi i prijedlozi: hello@alemcoksa.com · [alemcoksa.com](https://alemcoksa.com)
