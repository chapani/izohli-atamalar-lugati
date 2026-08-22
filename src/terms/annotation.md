# Qayd

**Inglizça:** Annotation<br>
**Rusça:** Аннотация<br>
**Soha:** Dasturlov<br>

**Qayd** — dastur bitigida yorliqlar, topşiriqlar yoki boşqa tuzilmalarga qöşimça malumot beruvçi va ularning hususiyatlarini (masalan, jinsini yoki umrini) aniq körsatib ötuvçi belgilov. Tuzgiç uşbu belgilarga tayanib, hatoliklarni oldindan aniqlaydi va hotira omonligini taminlaydi. Masalan, Rust dilida umr qaydi (`'a`) qaratqiçlarning qança vaqt davomida amal qilişini belgilab beradi.

```text
[Keltirilgan Bitik] : fn koersat<'a>(x: &'a str)
                             └───┬───┘
                                 ▼
                     [Umr Qaydi: 'a davomida faol]

```

## Etiborga olingan muqobillar

- belgilov
- annotatsiya
