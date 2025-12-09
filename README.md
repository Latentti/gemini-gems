# Latentti Gems - Käyttöohje

**Versio:** 2.0
**Päivitetty:** Joulukuu 2025
**Tekijä:** Ari Hietamäki / Latentti.fi

---

## Mikä on Gemini Gem?

Gem on Google Geminin räätälöity AI-assistentti, jolla on:
- Oma rooli ja asiantuntemus (esim. strategiakonsultti, talousanalyytikko)
- Valmiit viitekehykset ja metodit
- Johdonmukainen tyyli kaikissa keskusteluissa
- **Erikoisominaisuudet:** Extensions, Deep Research, Code Execution, tiedostot

**Hyöty:** Saat asiantuntija-avun ilman, että sinun tarvitsee selittää kontekstia joka kerta uudelleen.

---

## Geminin erikoisominaisuudet 2025

### 1. Extensions / Connected Apps

Gemini voi yhdistää Google-palveluihin käyttämällä @-merkkiä:

| Extension | Käyttö | Esimerkki |
|-----------|--------|-----------|
| **@Gmail** | Sähköpostien haku ja analyysi | "Etsi @Gmail viimeisimmät viestit asiakkaalta X" |
| **@Drive** | Google Drive -tiedostot | "Analysoi @Drive strategiadokumentti.pdf" |
| **@Docs** | Google Docs -dokumentit | "Tiivistä @Docs markkinointisuunnitelma" |
| **@YouTube** | Video-sisällön analyysi | "Analysoi @YouTube kilpailijan tuote-esittely" |
| **@Google Maps** | Sijaintitiedot | "Näytä @Google Maps kilpailijoiden toimipisteet" |
| **@Flights / Hotels** | Matkustuspalvelut | Liikematka-suunnittelu |

### 2. Deep Research (Gemini Advanced)

Laaja tutkimustoiminto, joka:
- Tutkii monimutkaisia aiheita puolestasi
- Tuottaa kattavan raportin muutamassa minuutissa
- Voi käyttää Workspace-sisältöä (Gmail, Drive, Chat)

**Käyttötarkoitukset:**
- **Toimialatutkimus:** Trendit, markkinakoot, teknologiat
- **Kilpailijatutkimus:** Kilpailijoiden analysointi
- **Asiakastutkimus:** Prospektien taustatutkimus

**Rajoitus:** 10 raporttia / 30 päivää (perustilaus)

### 3. Code Execution

Gemini voi suorittaa Python-koodia:
- Monimutkaiset laskutoimitukset
- Data-analyysi
- Kaavioiden ja visualisointien luonti
- Excel/CSV-tiedostojen käsittely

### 4. File Upload

Lataa tiedostoja suoraan keskusteluun:
- PDF-dokumentit
- Excel/CSV-taulukot
- Word-dokumentit
- Kuvat ja kaaviot
- Google Drive -integraatio

### 5. Gemini 3 (Uusin malli)

- 1 miljoonan tokenin konteksti-ikkuna
- Parannettu pitkäaikainen päättely
- Parempi tool-use ja integraatiot
- Multimodaalinen ymmärrys (teksti, kuva, video)

---

## Suositellut ominaisuudet per Gem

| Gem | Deep Research | @Gmail | @Drive | Code Exec | File Upload |
|-----|:-------------:|:------:|:------:|:---------:|:-----------:|
| **Business Strategy** | **KRIITTINEN** | - | Suositeltu | Suositeltu | Suositeltu |
| **Financial Analyst** | Suositeltu | - | **KRIITTINEN** | **KRIITTINEN** | **KRIITTINEN** |
| **Marketing Strategist** | **KRIITTINEN** | Suositeltu | Suositeltu | Suositeltu | Suositeltu |

### Miksi nämä valinnat?

**Business Strategy Consultant:**
- Deep Research KRIITTINEN → Laaja kilpailija- ja markkinatutkimus
- @Drive → Yrityksen strategiadokumentit
- Code Execution → TAM/SAM/SOM-laskelmat, visualisoinnit

**Financial Analyst:**
- Code Execution KRIITTINEN → Talousmallit, DCF, laskelmat
- @Drive KRIITTINEN → Tilinpäätökset, budjetit
- File Upload KRIITTINEN → Excel-analyysit

**Marketing Strategist:**
- Deep Research KRIITTINEN → Kilpailija- ja trendianalyysi
- @Gmail → Kampanjatulokset, asiakaspalautteet
- Code Execution → AARRR-metriikat, ROI-laskelmat

---

## Gemini Gems vs. ChatGPT GPTs - Ominaisuusvertailu

Molemmat alustat tarjoavat kattavat ominaisuudet. Tässä vertailu:

| Ominaisuus | Gemini Gem | ChatGPT GPT | Huomiot |
|------------|:----------:|:-----------:|---------|
| **Code Execution** | ✅ Python | ✅ Python | Molemmat tukevat |
| **File Upload** | ✅ | ✅ | PDF, Excel, Word, CSV |
| **Web Search** | ✅ Sisäänrakennettu | ✅ Web Browsing | Molemmat hakevat netistä |
| **Deep Research** | ✅ (10/kk) | ❌ | Vain Geminissä |
| **Image Generation** | ❌ Imagen (rajoitettu) | ✅ DALL-E | GPT:ssä parempi |
| **Google Workspace** | ✅ Natiivi (@Gmail, @Drive) | ⚠️ Actions | Geminissä parempi |
| **YouTube-analyysi** | ✅ @YouTube | ⚠️ Rajoitettu | Geminissä parempi |
| **Custom Actions/API** | ⚠️ Rajoitettu | ✅ | GPT:ssä parempi |
| **Jakaminen** | ❌ Ei suoraa jakoa | ✅ Linkki + GPT Store | GPT:ssä parempi |
| **Konteksti-ikkuna** | 1M tokens | 128K tokens | Geminissä suurempi |

### Kumpi valita?

**Valitse Gemini Gem kun:**
- Käytät Google Workspacea (Gmail, Drive, Docs)
- Tarvitset Deep Research -tutkimuksia
- Haluat analysoida YouTube-videoita
- Käsittelet erittäin pitkiä dokumentteja (1M konteksti)

**Valitse ChatGPT GPT kun:**
- Tarvitset DALL-E kuvanluontia (markkinointi)
- Haluat jakaa GPT:n helposti muille
- Tarvitset custom API-integraatioita (Actions)
- Käytät jo ChatGPT Plus -tilausta

---

## Gemin asentaminen (kerran per Gem)

### Vaihe 1: Avaa Gemini
1. Mene osoitteeseen **gemini.google.com**
2. Kirjaudu Google-tililläsi

### Vaihe 2: Luo Gem
1. Klikkaa vasemmasta sivupalkista **Gems**
2. Klikkaa **+ New Gem** (tai **+ Uusi Gem**)
3. Anna Gemille nimi (esim. "Business Strategy Consultant")

### Vaihe 3: Kopioi ohjeet
1. Avaa haluamasi Gem-tiedosto tästä kansiosta
2. Etsi osio **"Gem Instructions (Copy to Gemini)"**
3. Kopioi kaikki ``` merkkien välissä oleva teksti
4. Liitä **Instructions**-kenttään Geminissä

### Vaihe 4: Tallenna
1. Klikkaa **Save** / **Tallenna**
2. Gem on nyt käyttövalmis!

### Vaihe 5: Aktivoi Extensions (TÄRKEÄ!)
1. Klikkaa **Settings** (hammasratas-ikoni)
2. Valitse **Extensions** tai **Connected Apps**
3. Aktivoi haluamasi integraatiot:
   - **Google Drive** - Tiedostojen käyttö
   - **Google Docs** - Dokumenttien analyysi
   - **Gmail** - Sähköpostien haku (valinnainen)
   - **YouTube** - Videoanalyysi (valinnainen)

### Vaihe 6: Deep Research (Gemini Advanced)
Jos sinulla on Gemini Advanced / Google AI Pro:
1. Deep Research on automaattisesti käytössä
2. Käytä sitä kirjoittamalla: "Tee Deep Research aiheesta [aihe]"
3. Rajoitus: 10 raporttia / 30 päivää

---

## Gemin käyttäminen (päivittäin)

### Aloita keskustelu
1. Avaa **Gems**-valikko vasemmasta sivupalkista
2. Klikkaa haluamaasi Gemiä
3. Kirjoita pyyntösi normaalisti

### Esimerkkejä keskustelun aloituksesta

**Business Strategy Consultant:**
- "Analyze the competitive landscape for [toimiala]"
- "Help me develop a market entry strategy for [markkina]"
- "Conduct a SWOT analysis for [yritys]"

**Financial Analyst:**
- "Create a 3-year financial projection for [yritys]"
- "Analyze the unit economics of [liiketoimintamalli]"
- "Calculate the valuation of [yritys] using DCF"

**Marketing Strategist:**
- "Develop a go-to-market strategy for [tuote]"
- "Help me define customer segments for [palvelu]"
- "Create a growth strategy to scale from X to Y customers"

### Vinkkejä tehokkaaseen käyttöön

| Vinkki | Esimerkki |
|--------|-----------|
| **Anna konteksti** | "We are a B2B SaaS company with 50 employees..." |
| **Määritä tavoite** | "I need this for investor presentation" |
| **Pyydä tiettyä viitekehystä** | "Use Porter's Five Forces to analyze..." |
| **Pyydä formaattia** | "Present this as a table" / "Give me bullet points" |

---

## Saatavilla olevat Gemit

| Gem | Tiedosto | Käyttötarkoitus |
|-----|----------|-----------------|
| **Business Strategy Consultant** | `Business-Strategy-Consultant-Gem.md` | Strateginen suunnittelu, kilpailija-analyysi, SWOT, Porter's Five Forces |
| **Financial Analyst** | `Financial-Analyst-Gem.md` | Talousennusteet, arvonmääritys, unit economics, ROI-analyysi |
| **Marketing Strategist** | `Marketing-Strategist-Gem.md` | Go-to-market, growth hacking, brand positioning, AARRR-metriikat |

---

## Usein kysytyt kysymykset

### Kuinka monta Gemiä voin luoda?
Voit luoda useita Gemejä. Jokainen toimii itsenäisesti.

### Muistaako Gem aiemmat keskustelut?
Gem muistaa keskustelun sisällä, mutta jokainen uusi keskustelu alkaa puhtaalta pöydältä. Gem kuitenkin noudattaa aina samoja ohjeita.

### Voinko muokata Gemiä?
Kyllä. Avaa Gem → **Edit** → muokkaa ohjeita → **Save**.

### Miksi Gem ei noudata ohjeita?
- Kokeile antaa selkeämpi pyyntö
- Pyydä eksplisiittisesti: "Use [framework] to analyze this"
- Tarkista, että ohjeet kopioituivat kokonaan

### Voinko jakaa Gemin muille?
Gemejä ei voi suoraan jakaa. Jaa tämän kansion tiedostot, ja vastaanottaja luo oman Gemin samoilla ohjeilla.

---

## Ongelmanratkaisu

| Ongelma | Ratkaisu |
|---------|----------|
| Gem ei vastaa odotetulla tavalla | Pyydä eksplisiittisesti haluamaasi viitekehystä tai formaattia |
| Vastaukset liian pitkiä | Lisää pyyntöön: "Be concise" tai "Max 3 bullet points" |
| Gem ei käytä oikeaa kieltä | Kirjoita pyyntösi haluamallasi kielellä |
| Gem unohtaa aiemman keskustelun | Tämä on normaalia - muistuta tärkeät asiat uudessa viestissä |

---

## Resurssit

- [Google Gemini](https://gemini.google.com)
- [Gemini Gems Help](https://support.google.com/gemini/answer/14575153)

---

*Latentti.fi - AI-avusteinen liiketoiminnan kehittäminen*
