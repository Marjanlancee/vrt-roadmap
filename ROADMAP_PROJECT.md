# VRT Taxateur Roadmap — Project Documentatie

## Over dit project
Een interactief leerplatform voor VRT-taxateurs, gemodelleerd naar roadmap.sh.
Gebouwd voor twee doelgroepen:
- **Salta Groep** — aantonen hoe opleidingen (LOI, NCOI, SkillsTown, Schoevers, De Baak, ROVC) aansluiten op loopbaanpaden in de taxateursector
- **VRT Taxateurs** — persoonlijk loopbaanpad waarbij professionals hun skillsgap zien en dichten via kleine leereenheden

## Salta Groep merken in de roadmap
| Merk | Toepassing |
|------|-----------|
| LOI | Wft Schadeverzekering particulier & zakelijk (online) |
| NCOI | Schadebehandelaar Aansprakelijkheid HBO (klassikaal) |
| Schoevers | Zakelijk schrijven & rapportage (blended) |
| ROVC | Bouwkunde & installatietechniek (klassikaal) |
| SkillsTown | AI & ChatGPT trainingen, toekomstvaardigheden (online) |
| De Baak | Soft skills: feedback, communicatie, presenteren (klassikaal) |

## Leervormen per node
- 🏫 Klassikaal — fysieke cursus of workshop
- 💻 Online — e-learning, zelfstandig tempo
- 🔄 Blended — combinatie klassikaal + online
- 📚 Zelfstudie — boeken, vakliteratuur

---

## FASE 1 — Rolgerichte & Vaardigheidsgerichte Roadmaps

### Checklist
- [x] Portal met hero, 4 secties (Role, Skill, Projects, Best Practices)
- [x] Bladwijzers per kaart
- [x] 6 Role Based roadmaps: Schade, Voertuig, Inboedel, Successie, Kunst & Antiek, Bedrijfsschade
- [x] 9 Skill Based roadmaps (kaarten aanwezig, flowcharts in Fase 2)
- [x] Node paneel met Leren op de werkvloer (praktische werkplek-activiteiten)
- [x] Opleidingen met leervorm badges per node
- [x] Salta-merken correct gekoppeld per node
- [x] Toekomstvaardigheden bij 8 relevante nodes (SkillsTown + De Baak)
- [x] Premium bronnen (boeken, software)
- [x] Status per node: Pending / Bezig / Afgerond ✓
- [x] Voortgangsbalk per roadmap
- [x] Gerelateerde roadmaps in sidebar
- [x] Live op Vercel (vrt-roadmap.vercel.app)
- [x] Hero titel + donker navy achtergrond
- [x] Alle 6 rollen volledig uitgewerkt (alle nodes)

### Disciplines & Rollen
| Discipline | Rol | Nodes | Status |
|-----------|-----|-------|--------|
| Schade | Schade Taxateur | 23 | ✅ Volledig |
| Voertuig | Voertuig Taxateur | 15 | ✅ Volledig |
| Inboedel | Inboedel & Opstal Taxateur | 12 | ✅ Volledig |
| Successie | Successie & Boedel Taxateur | 19 | ✅ Volledig |
| Kunst | Kunst & Antiek Taxateur | 15 | ✅ Volledig |
| Bedrijfsschade | Bedrijfsschade Taxateur | 15 | ✅ Volledig |

---

## FASE 2 — Praktijk & Toetsing (gepland)

### Checklist
- [ ] Project Ideas uitwerken per discipline (concrete opdrachten per fase)
- [ ] Best Practices uitwerken (VRT gedragscode, tuchtrecht, kwaliteitsnormen)
- [ ] Kennistoetsvragen per roadmap (voorbereiding VRT-toetsingscommissie)
- [ ] Skill Based roadmaps uitwerken als eigen flowcharts
- [ ] Beginner versie per roadmap (ingekort leerpad)
- [ ] Gevorderd versie per roadmap (volledig pad)

---

## FASE 3 — Slimme Functies (gepland)

### Checklist
- [ ] AI Tutor per node (vragen stellen, kennis testen)
- [ ] Deelbare voortgang URL (delen met begeleider of werkgever)
- [ ] Changelog (nieuwe opleidingen, wetswijzigingen, PE-nieuws)
- [ ] Koppeling met Talentshare skillsprofiel

---

## Technische Stack
- **Frontend**: Single page HTML (vanilla JS, geen framework)
- **Hosting**: Vercel (static deployment)
- **Versie**: v1.0 — Fase 1 compleet
- **GitHub**: github.com/Marjanlancee

## Deployment
1. Pas `index.html` aan
2. Upload naar Vercel via drag & drop of GitHub koppeling
3. Live op vrt-roadmap.vercel.app

