# Kanban Board seadistamine

## Kuidas luua

1. Repo → **Projects** → **New project**
2. Vali **Board** (mitte Table)
3. Nimi: `IoT Stendi Projekt`
4. Create

## Tulbad

Kustuta vaikimisi tulbad ja loo need:

| Tulp | Kirjeldus |
|------|-----------|
| 📋 **Ootel** | Ülesanded mis ootavad (järgmised etapid) |
| 🔄 **Töös** | Praegu teeme seda |
| 👀 **Ülevaatus** | Valmis, õpetaja kontrollib |
| ✅ **Tehtud** | Kinnitatud ja lõpetatud |

## Automaatika

Settings → Workflows → lülita sisse:

1. **Auto-add to project** → filter: `is:issue is:open`
2. **Item added to project** → Set status to `📋 Ootel`
3. **Item closed** → Set status to `✅ Tehtud`

## Kuidas kasutada

### Õpilane:
1. Võta Issue `📋 Ootel` tulbast
2. Lohista `🔄 Töös` tulpa
3. Kui valmis → lohista `👀 Ülevaatus`
4. Oota kuni õpetaja kontrollib

### Õpetaja:
1. Vaata `👀 Ülevaatus` tulpa
2. Kontrolli kas kõik OK
3. Sulge Issue → läheb automaatselt `✅ Tehtud`
4. Järgmine Issue tekib automaatselt!