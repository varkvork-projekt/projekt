# IoT Stendi Projekt - Juhend

## Kuidas see töötab?

```
Õpetaja käivitab → Issue 1 tekib → Õpilane teeb → Sulgeb → Issue 2 tekib → ... → Issue 8 → VALMIS!
```

---

## Õpetaja tegevused

| Millal | Mida teha | Kus |
|--------|-----------|-----|
| **Alguses** | Käivita workflow "Start" | Actions → Start → Run workflow |
| **Jooksvalt** | Jälgi progressi | Projects → Kanban board |
| **Jooksvalt** | Vasta küsimustele | Discussions |
| **Etapi lõpus** | Kontrolli töö, lisa kommentaar | Issues → vastav Issue |

---

## Õpilase tegevused

| Millal | Mida teha | Kus |
|--------|-----------|-----|
| **Iga etapp** | Loe ülesanne läbi | Issues → avatud Issue |
| **Iga etapp** | Tee ülesanded ära | Wiki, docs/ kaust |
| **Iga etapp** | Märgi checkboxid ✓ | Issue sees |
| **Kui valmis** | Sulge Issue | Issue → Close |
| **Küsimused** | Küsi abi | Discussions → Küsimused |

---

## 8 etappi

| # | Nimi | Kestus | Tulemus |
|---|------|--------|---------|
| 1 | Nõuded | 1 nädal | Wiki leht |
| 2 | Idee | 1-2 nädalat | `docs/idee.md` |
| 3 | Persoonad | 1 nädal | `docs/persoonad.md` |
| 4 | Disain | 1-2 nädalat | `schematics/` + `docs/disain.md` |
| 5 | Eelarve | 1-2 nädalat | `docs/eelarve.md` |
| 6 | Ehitamine | 2-3 nädalat | Töötav stend + `src/` |
| 7 | Testimine | 1-2 nädalat | `tests/testiraport.md` |
| 8 | Esitlus | 1-2 nädalat | Juhendid + esitlus |

---

## Kanban tulbad

| Tulp | Tähendus |
|------|----------|
| 📋 Ootel | Järgmised etapid |
| 🔄 Töös | Praegu tegeleb |
| 👀 Ülevaatus | Ootab õpetaja kontrolli |
| ✅ Tehtud | Kinnitatud |

---

## Label'id

`etapp1` `etapp2` `etapp3` `etapp4` `etapp5` `etapp6` `etapp7` `etapp8`

---

## Kiirlingid

- **Issues:** ülesanded
- **Projects:** kanban
- **Wiki:** juhendid
- **Discussions:** küsimused/teated
- **Actions:** automaatika

---

## Probleemid?

| Probleem | Lahendus |
|----------|----------|
| Issue ei teki | Kontrolli kas label on õige (`etapp1`, mitte `etapp-1`) |
| Workflow punane | Actions → vaata viga → paranda |
| Õpilane ei näe | Kontrolli repo õigusi (Settings → Collaborators) |