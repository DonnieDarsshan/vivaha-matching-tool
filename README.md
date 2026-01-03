# vivaha-matching-tool
Vedic &amp; KP based marriage horoscope matching tool with Nakshatra, Tatva and Tara Bala analysis.

# Horoscope Matching Tool (Vedic & KP)

A browser-based **Boy–Girl Horoscope Matching Tool** built using **pure HTML, CSS, and JavaScript**, following **Vedic astrology principles with KP support**.

This tool performs multiple compatibility analyses including:
- Lagna ↔ Lagna & Planet ↔ Planet
- Lagna → Planet analysis
- Tatva (Elemental) matching
- Tara Bala (pure Nakshatra-based)
- Rahu–Ketu automatic linkage
- Save / Load horoscope data (JSON)

No backend, no frameworks — **100% client-side**.

---

## ✨ Features

- ✅ **Vedic & KP systems**
- ✅ **Sign-to-Sign mode**
- ✅ **Ignore Padas option**
- ✅ **Rahu–Ketu automatic linking**
- ✅ **Tara Bala (Vedic, Nakshatra-only, no Pada rules)**
- ✅ **Directional analysis (Boy → Girl & Girl → Boy)**
- ✅ **Good / Average / Bad verdicts**
- ✅ **Save, Load, Clear chart**
- ✅ **Clean table layout with visual separators**

---

## 📊 Analysis Tables

1. **Table 1 – Input Details**
   - Lagna, planets, Rahu–Ketu, progressions

2. **Table 2 – Lagna ↔ Lagna & Planet ↔ Planet**
   - Directional results with house equivalence

3. **Table 3 – Lagna → Planet**
   - From Lagna house position comparison

4. **Table 4 – Tatva Matching**
   - Fire / Earth / Air / Water logic

5. **Table 5 – Tara Bala**
   - Pure Nakshatra-based (Janma, Sampath, Vipath, etc.)
   - Independent of KP / Vedic / Pada / Sign rules

---

## 🧠 Astrology Logic Notes

- **Tara Bala** is always calculated using **27 Nakshatras only**
- **Sign-to-Sign** overrides Pada & Nakshatra logic
- **Ignore Padas** uses Nakshatra-level distance
- **KP vs Vedic** affects distance offset logic
- **7–7, 1–7, 7–1** equivalences are handled correctly

---

## 🚀 How to Run

1. Download or clone the repository
2. Open the `.html` file in any modern browser
3. No server required

---

## 💾 Save / Load

- Charts are saved as `.json`
- Load restores:
  - System (Vedic/KP)
  - Options (Ignore Padas, Rahu–Ketu)
  - All planetary inputs

---

## 📁 Project Structure

```text
/
├── index.html   (entire project)
└── README.md



