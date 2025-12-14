# Kuidas see töötab?

## Ülevaade

Projekt kasutab GitHub'i automaatikat: kui õpilane sulgeb ühe etapi Issue, tekib automaatselt järgmine.

```
Õpetaja käivitab → Issue 1 tekib → Õpilane teeb → Sulgeb → Issue 2 tekib → ... → VALMIS!
```

## Seadistamine

### 1. Loo repo template'ist

1. Mine template repo juurde
2. Vajuta "Use this template" → "Create a new repository"
3. Anna nimi (nt `iot-stend-2024-grupp1`)
4. Vali "Public" (et GitHub Pages töötaks)

### 2. Luba GitHub Pages

1. Settings → Pages
2. Source: "GitHub Actions"

### 3. Lisa õpilased

1. Settings → Collaborators
2. Lisa iga õpilane (Write õigused)

### 4. Käivita esimene etapp

1. Actions → "Start"
2. "Run workflow"
3. Esimene Issue tekib automaatselt!

## Õpetaja tegevused

| Millal | Mida teha | Kus |
|--------|-----------|-----|
| **Alguses** | Käivita workflow "Start" | Actions → Start → Run workflow |
| **Jooksvalt** | Jälgi progressi | Projects → Kanban board |
| **Jooksvalt** | Vasta küsimustele | Discussions |
| **Etapi lõpus** | Kontrolli töö, lisa kommentaar | Issues → vastav Issue |

## Õpilase tegevused

| Millal | Mida teha | Kus |
|--------|-----------|-----|
| **Iga etapp** | Loe ülesanne läbi | Issues → avatud Issue |
| **Iga etapp** | Tee ülesanded ära | Wiki, docs/ kaust |
| **Iga etapp** | Märgi checkboxid ✓ | Issue sees |
| **Kui valmis** | Sulge Issue | Issue → Close |
| **Küsimused** | Küsi abi | Discussions → Küsimused |

## Probleemide lahendamine

| Probleem | Lahendus |
|----------|----------|
| Issue ei teki | Kontrolli kas label on õige (`etapp1`, mitte `etapp-1`) |
| Workflow punane | Actions → vaata viga → paranda |
| Õpilane ei näe | Kontrolli repo õigusi (Settings → Collaborators) |
| Pages ei tööta | Settings → Pages → kontrolli source |
