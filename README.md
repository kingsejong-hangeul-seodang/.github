# 킹세종 한글서당 · King Sejong Hangeul Seodang

> 2026-Fall Open-Source Software Project (CSC4004-01), Dongguk University — Team C

**Practice Korean handwriting with the K-pop lyrics and K-drama lines you love.**

Watch a short clip, copy the line onto a manuscript grid (*wongoji*) with Apple Pencil, and King Sejong checks your **spelling, spacing, and stroke order** — one after another.

## Why

International students in Korea have plenty of tools for speaking and listening, but almost nothing that corrects *how* they write Hangeul by hand. Existing apps check whether the final shape looks right. We look at the writing process itself.

## Key Features

- **Learn with what you like** — pick K-pop, K-drama, or basic practice, then write a line from a clip of 30 seconds or less
- **Manuscript grid** — one character per cell, and a blank cell for each space
- **Three-step checking** — spelling first, then spacing, then stroke order for the characters you got right
- **Three difficulty levels** — beginner (trace a guide), intermediate (word groups, no guide), advanced (blank cells only)
- **Stroke-order animation** — see the correct order drawn stroke by stroke
- **King Sejong as your teacher** — feedback, levels, and daily streaks to keep you writing

## Target

| | |
| --- | --- |
| Users | International students whose Hangeul handwriting is still unsteady |
| Device | iPad + Apple Pencil, Safari, portrait mode |
| Open source | Correction engine and reference stroke data |

## Repositories

| Repository | Description |
| --- | --- |
| [kingsejong-server](https://github.com/kingsejong-hangeul-seodang/kingsejong-server) | Backend server |
| kingsejong-web | Web frontend (React + TypeScript) — coming soon |
| kingsejong-engine | Handwriting correction engine (Python) — coming soon |

## Team

| Name | Part |
| --- | --- |
| 이동건 (Lee Donggeon) | Team lead · Frontend · Backend · Infrastructure |
| 이승원 (Lee Seungwon) | Frontend |
| 유정진 (Yoo Jeongjin) | AI correction engine |
| 권혁윤 (Kwon Hyeokyun) | AI correction engine · Engine deployment |
