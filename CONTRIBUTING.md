# Hozzájárulási útmutató / Contributing Guidelines

🇭🇺 **Magyar** | [English](#english)

---

## 🇭🇺 Magyar

Köszönjük, hogy hozzájárulsz a HUN-OSINT projekthez! Ez a dokumentum segít abban, hogy a hozzájárulásod zökkenőmentes legyen.

### 📋 Tartalomjegyzék

- [Magatartási kódex](#magatartási-kódex)
- [Hogyan járulhatok hozzá?](#hogyan-járulhatok-hozzá)
- [Pull Request folyamat](#pull-request-folyamat)
- [Formázási irányelvek](#formázási-irányelvek)
- [Mit fogadunk el?](#mit-fogadunk-el)
- [Mit NEM fogadunk el?](#mit-nem-fogadunk-el)

---

### 🤝 Magatartási kódex

A projekthez való hozzájárulással elfogadod az alábbi elveket:

1. **Tiszteletteljes kommunikáció** - Minden hozzászólásban legyünk udvariasak
2. **Jogszerűség** - Csak legális eszközöket és forrásokat osztunk meg  
3. **Minőség** - Ellenőrzött, működő linkeket adunk hozzá
4. **Együttműködés** - Segítsük egymást a projekt fejlesztésében

---

### 🔧 Hogyan járulhatok hozzá?

#### 1. Hibás link jelentése

Ha találsz egy nem működő linket:

1. Nyiss egy **Issue**-t a GitHub-on
2. Add meg:
   - A hibás link URL-jét
   - A README.md-ben elfoglalt helyét (szekció neve)
   - Ha tudod, a helyes/új URL-t

#### 2. Új forrás hozzáadása

1. **Fork**-old a repository-t
2. Készíts egy új branch-et:
   ```bash
   git checkout -b feature/uj-forras-neve
   ```
3. Szerkeszd a `README.md` fájlt
4. Ellenőrizd a linket (működik-e?)
5. Commit-old a változtatásokat:
   ```bash
   git commit -am 'Új forrás hozzáadása: [forrás neve]'
   ```
6. Push-old a branch-et:
   ```bash
   git push origin feature/uj-forras-neve
   ```
7. Nyiss egy **Pull Request**-et

---

### 📝 Pull Request folyamat

1. **Egy PR = Egy változtatás** - Ne keverj össze több különböző módosítást
2. **Írd le a változtatást** - A PR leírásában magyarázd el, mit és miért változtattál
3. **Ellenőrizd a formázást** - Kövesd az alábbi irányelveket
4. **Várd meg a review-t** - A karbantartók átnézik a PR-t

---

### 📐 Formázási irányelvek

#### Táblázat formátum

Minden forrást táblázatban adunk meg a következő formátumban:

```markdown
| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **Szolgáltatás neve** | Rövid leírás | [domain.hu](https://domain.hu/) |
```

#### Link formátum

- Használj **HTTPS**-t ahol lehetséges
- A link szövege legyen a domain neve (pl. `[police.hu](https://www.police.hu/)`)
- Záró `/` a domain végén (konzisztencia miatt)

#### Emoji használat

Szekciócímekhez használj megfelelő emoji-kat:
- 🏛️ - Hatóságok
- 🏢 - Cégek
- 👤 - Személyek
- 🚗 - Közlekedés
- ⚖️ - Jog
- 📚 - Archívumok
- 🔓 - Biztonság
- 🛠️ - Eszközök
- 🔍 - Keresés
- 📊 - Adatok

---

### ✅ Mit fogadunk el?

- ✅ **Működő linkek** - Minden link működjön a beküldés időpontjában
- ✅ **Magyar vagy EU-s források** - A projekt fókusza Magyarország és az EU
- ✅ **Legális eszközök** - Csak nyilvánosan elérhető, legális források
- ✅ **OSINT relevancia** - A forrás legyen hasznos OSINT célokra
- ✅ **Jó dokumentáció** - Írd le, mire jó az adott forrás

#### Példa jó hozzájárulásra:

```markdown
| **Új Szolgáltatás** | Magyar cégek kapcsolati hálóinak vizualizációja | [ujszolgaltatas.hu](https://ujszolgaltatas.hu/) |
```

---

### ❌ Mit NEM fogadunk el?

- ❌ **Illegális eszközök** - Hackeléshez, jogosulatlan hozzáféréshez használható eszközök
- ❌ **Fizetős szolgáltatások regisztráció nélkül** - Ha csak fizetős, jelöld meg
- ❌ **Nem működő linkek** - Ellenőrizd a linket beküldés előtt
- ❌ **Duplikált tartalom** - Ne adj hozzá már meglévő forrásokat
- ❌ **Irreleváns tartalom** - Csak OSINT-releváns források
- ❌ **Személyes adatok** - Ne ossz meg személyes információkat

---

### 📧 Kapcsolat

Ha kérdésed van, nyiss egy **Issue**-t vagy írj a karbantartóknak.

---

---

## English

Thank you for your interest in contributing to HUN-OSINT! This document will help you contribute smoothly.

### 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Pull Request Process](#pull-request-process)
- [Formatting Guidelines](#formatting-guidelines)
- [What We Accept](#what-we-accept)
- [What We Don't Accept](#what-we-dont-accept)

---

### 🤝 Code of Conduct

By contributing to this project, you agree to:

1. **Respectful communication** - Be polite in all interactions
2. **Legality** - Only share legal tools and resources
3. **Quality** - Add verified, working links
4. **Collaboration** - Help each other improve the project

---

### 🔧 How to Contribute

#### 1. Report a Broken Link

If you find a non-working link:

1. Open an **Issue** on GitHub
2. Provide:
   - The broken URL
   - Its location in README.md (section name)
   - If known, the correct/new URL

#### 2. Add a New Resource

1. **Fork** the repository
2. Create a new branch:
   ```bash
   git checkout -b feature/new-resource-name
   ```
3. Edit `README.md`
4. Verify the link works
5. Commit your changes:
   ```bash
   git commit -am 'Add new resource: [resource name]'
   ```
6. Push the branch:
   ```bash
   git push origin feature/new-resource-name
   ```
7. Open a **Pull Request**

---

### 📝 Pull Request Process

1. **One PR = One Change** - Don't mix multiple unrelated changes
2. **Describe the change** - Explain what and why in the PR description
3. **Check formatting** - Follow the guidelines below
4. **Wait for review** - Maintainers will review your PR

---

### 📐 Formatting Guidelines

#### Table Format

All resources are listed in tables:

```markdown
| Service | Description | Link |
|---------|-------------|------|
| **Service Name** | Brief description | [domain.hu](https://domain.hu/) |
```

#### Link Format

- Use **HTTPS** where possible
- Link text should be the domain name (e.g., `[police.hu](https://www.police.hu/)`)
- Trailing `/` at the end of domains (for consistency)

---

### ✅ What We Accept

- ✅ **Working links** - All links must work at submission time
- ✅ **Hungarian or EU resources** - Project focus is Hungary and EU
- ✅ **Legal tools** - Only publicly available, legal resources
- ✅ **OSINT relevance** - Resource must be useful for OSINT purposes
- ✅ **Good documentation** - Describe what the resource is for

---

### ❌ What We Don't Accept

- ❌ **Illegal tools** - Tools for hacking or unauthorized access
- ❌ **Paid services without disclosure** - If paid-only, mark it as such
- ❌ **Broken links** - Verify links before submitting
- ❌ **Duplicate content** - Don't add existing resources
- ❌ **Irrelevant content** - Only OSINT-relevant resources
- ❌ **Personal data** - Don't share personal information

---

### 📧 Contact

If you have questions, open an **Issue** or contact the maintainers.

---

**Köszönjük / Thank you!** 🙏
