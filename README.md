# MiniATC ✈️📡

A C++/SFML air traffic control simulator — manage landings, takeoffs, and taxiway traffic across 21 real-world airports in 7 countries.

![Language](https://img.shields.io/badge/language-C%2B%2B-blue)
![Engine](https://img.shields.io/badge/engine-SFML%203-orange)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey)

---

## 🎮 What is MiniATC?

MiniATC puts you in the seat of an air traffic controller. Guide aircraft through approach, holding pattern, landing, taxiway queue, and takeoff — all while respecting realistic wind direction, fuel constraints, and separation rules.

## ✈️ Features

- **21 real airports** across 7 countries (USA, UK, Morocco, Spain, Germany, UAE, Brazil) — with real runway headings
- **32 airline callsigns** based on real IATA codes for authentic aircraft identifiers
- **Realistic wind mechanics** — landings and takeoffs always happen into the wind
- **FIFO taxiway queue** — aircraft must depart in the correct order or risk collision
- **Fuel management** — emergency aircraft with critical fuel add pressure to your decisions
- **Full audio system** — alarms, radio chatter, engine sounds
- **Bilingual interface** — English / French
- **3 difficulty levels per country** — Easy, Medium, Hard

## 🕹️ How to play

| Key | Action |
|---|---|
| `Tab` / `←` `→` | Select an aircraft |
| `Num4` | Clear selected aircraft to land |
| `Num6` | Clear selected aircraft for takeoff |
| `P` / `Esc` | Pause |
| Mouse | Navigate menus, click buttons |

**Goal:** land and depart as many aircraft as possible without collisions, fuel emergencies, or taxiway violations.

## 📥 Download & Play

1. Go to the [**Releases**](../../releases) page
2. Download the latest `MiniATC-vX.X.zip`
3. Extract anywhere
4. Run `MiniATC.exe` — no installation needed

**Requirements:** Windows.

## 🖼️ Screenshots

<img width="1903" height="911" alt="Capture d&#39;écran 2026-07-29 121158" src="https://github.com/user-attachments/assets/a1e07bfc-4590-460c-96cf-2406ce1031aa" />

<img width="1903" height="962" alt="Capture d&#39;écran 2026-07-29 121239" src="https://github.com/user-attachments/assets/9e76cc82-5432-485d-ae59-b0799b07b7ec" />
<img width="1901" height="982" alt="Capture d&#39;écran 2026-07-29 121316" src="https://github.com/user-attachments/assets/3ecc773d-9c26-4f79-9a85-bf54adf48674" />
<img width="1911" height="975" alt="Capture d&#39;écran 2026-07-29 121405" src="https://github.com/user-attachments/assets/556c722c-93c8-4810-8bbf-297eebaffc91" />
<img width="1907" height="968" alt="Capture d&#39;écran 2026-07-29 122323" src="https://github.com/user-attachments/assets/ade9cf4f-37c2-4282-87d9-244dcd242294" />
<img width="1902" height="925" alt="Capture d&#39;écran 2026-07-29 122035" src="https://github.com/user-attachments/assets/0f5941e3-6e14-4e7a-91d4-460a8fed26d2" />
<img width="1895" height="946" alt="Capture d&#39;écran 2026-07-29 122411" src="https://github.com/user-attachments/assets/8c3f2352-36fe-4222-bcb3-5bfb487e9cbc" />

## 📬 Feedback

Found a bug or have a suggestion? Feel free to open an [issue](../../issues) — feedback is welcome!

---

*Built with C++20 and SFML 3.*
