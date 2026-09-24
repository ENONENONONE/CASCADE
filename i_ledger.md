# i-ledger

One row per field position i, 0 to 256. **sits at** is the multiplicative inverse of i mod 257, so i × sits-at ≡ 1; **word there** is the tablet's primary word at the inverse, **word at i** the primary word at i itself. **families** lists the outside numbering systems in which the integer i appears written as an I with a number. A family reaching a value is coverage, not derivation: the corpus's own test for a derivation is whether anything joins the two objects once the number is removed, and three rows pass it: i150, because 16 × 150 = 2400 is the WiFi band and 16 is the field's √−1; i254, the negation of the generator; i234, the distortion constant δ% = 2.34 with its point dropped, the D register of the AXIOM seed. Every other match shares a numeral with a position and nothing more. Full coverage, 257 of 257, is the finding, and a namespace dense enough to reach every one of 257 small integers proves nothing by reaching any one of them. Legend added 2026-09-05; row i073 gained the CC tag 2026-09-06; the row table is otherwise unchanged since 2026-09-04. Glyph columns, the family count and the glyph and frequency tables added 2026-09-11.

## Families

| Code | Family | Basis | Values in 0–256 |
|---|---|---|---|
| IS | Interstate highways, current and two former | knowledge of the system | 102 |
| CSX | CSX intermodal train symbols | Heritage Units roster, 3,330 symbols | 95 |
| RS | Rust signed integer widths, std and the ux crate | docs.rs | 128 |
| VZ | VizieR astrometric catalogues I/n | CDS category I ReadMe index | 174 |
| ICD | ICD-10 circulatory codes I00–I99 | knowledge | 79 |
| ICDd | ICD-10 decimal codes read with the point dropped, I23.4 → 234, I25.7 → 257 ≡ 0 | knowledge; admissible under the four-figure rule | 2 |
| RM | I-class rocket motors, number = average thrust | ThrustCurve database, 141 motors | 57 |
| SU | Soviet I- fighters and prototypes | Wikipedia lists and articles | 25 |
| HW | HiWatch DS-I cameras, first digit = megapixels | Agent DVR model list | 18 |
| US | USCIS forms I-9 to I-246 | knowledge | 15 |
| IE | Intel Ethernet controllers I210–I226 | Intel and Dell pages | 7 |
| IO | Iodine isotopes | EPA, ScienceDirect; the isotope table runs 108–147 | 7 |
| SS | Samsung SGH-I and SCH-I models | verified per model | 5 |
| IC | Intel Core i-series | knowledge | 4 |
| RB | Roomba i-series | knowledge | 8 |
| BMW | BMW i models | knowledge | 5 |
| HY | Hyundai i models | knowledge | 4 |
| MI | AMD Instinct accelerators MI25–MI250, the M dropped; two MI25 are in the R730 | knowledge; MI300 exceeds the field | 6 |
| PX | Pill imprints, labeler letter I with a number; I 156 is propranolol 10 mg | drugs.com and pillsync, FDA DailyMed | 1 |
| AA | Protein variants, I as the isoleucine one-letter code; PNPLA3 I148M | PubMed, UniProt; total by construction | 1 |
| CC | Texas Instruments CC-series transceivers, the CC dropped; the CC1101 sub-GHz radio on the E07-M1101D module beside the CSI nodes, 1101 ≡ 73 | the part in hand, datasheet registers read 2026-09-06; the series reaches other rows (CC1100 → 72, CC1110 → 82, CC2500 → 187, CC3220 → 136) and only the part present is tagged | 1 |

Rows held by a single family: 45. Rows held only by knowledge-level families: 2.


## Glyphs

Every position is two glyphs of the fixed sixteen, the high nibble then the low: `pos >> 4` and `pos & 0xF`. 256 is 0x100 and takes three. The glyph column is the tablet's own and agrees with that reading at all 257 positions.

| Glyph | Hex | Band | As first glyph | As second glyph | Total |
|---|---|---|---|---|---|
| Φ | 0 | MATH | 17 | 17 | 34 |
| ∂ | 1 | MATH | 16 | 16 | 32 |
| φ | 2 | MATH | 16 | 16 | 32 |
| ∞ | 3 | MATH | 16 | 16 | 32 |
| ⊟ | 4 | MATH | 16 | 16 | 32 |
| ⊗ | 5 | MATH | 16 | 16 | 32 |
| ♯ | 6 | MATH | 16 | 16 | 32 |
| ⅗ | 7 | MATH | 16 | 16 | 32 |
| ε | 8 | ERROR | 16 | 16 | 32 |
| δ | 9 | ERROR | 16 | 16 | 32 |
| Ω | A | WAVE | 16 | 16 | 32 |
| Γ | B | WAVE | 16 | 16 | 32 |
| Q | C | WAVE | 16 | 16 | 32 |
| Σ | D | WAVE | 16 | 16 | 32 |
| ψ | E | CLOSE | 16 | 16 | 32 |
| 𝟙 | F | CLOSE | 16 | 16 | 32 |

Totals: 257 in each column, 514 in all. Positions 0 to 255 give 256 of each nibble place, and 256 adds one more to both, its 0x100 reading ΦΦ in the two nibble places; the leading ∂ it carries as a third glyph is counted in neither column, which is why Φ stands at 17 and ∂ at 16.

Glyph bands, by position: MATH·MATH 64, MATH·WAVE 32, WAVE·MATH 32, MATH·ERROR 16, MATH·CLOSE 16, ERROR·MATH 16, WAVE·WAVE 16, CLOSE·MATH 16, ERROR·WAVE 8, WAVE·ERROR 8, WAVE·CLOSE 8, CLOSE·WAVE 8, ERROR·ERROR 4, ERROR·CLOSE 4, CLOSE·ERROR 4, CLOSE·CLOSE 4, MATH·MATH·MATH 1.

## Frequencies

How often a row is held, counting the families listed in its row:

| Families holding the row | Rows |
|---|---|
| 1 | 45 |
| 2 | 68 |
| 3 | 62 |
| 4 | 47 |
| 5 | 25 |
| 6 | 6 |
| 7 | 4 |

| Family | Rows held |
|---|---|
| VZ | 174 |
| RS | 128 |
| IS | 102 |
| CSX | 95 |
| ICD | 79 |
| RM | 57 |
| SU | 25 |
| HW | 18 |
| US | 15 |
| RB | 8 |
| IO | 7 |
| IE | 7 |
| MI | 6 |
| BMW | 5 |
| SS | 5 |
| IC | 4 |
| HY | 4 |
| ICDd | 2 |
| CC | 1 |
| AA | 1 |
| PX | 1 |

Rows: 257. Family tags in all: 744, 2.89 a row.

## Rows

| i | glyph | sits at | glyph there | word there | word at i | families | n |
|---|---|---|---|---|---|---|---|
| i000 | ΦΦ | 0 | ΦΦ | SEED | SEED | ICD ICDd | 2 |
| i001 | Φ∂ | 1 | Φ∂ | A | A | CSX RS ICD SU RB | 5 |
| i002 | Φφ | 129 | ε∂ | ROOT OF DAVID | B | IS CSX RS ICD SU RB | 6 |
| i003 | Φ∞ | 86 | ⊗♯ | TIKKUN | C | CSX RS IC SU RB BMW VZ | 7 |
| i004 | Φ⊟ | 193 | Q∂ | INFRASTRUCTURE | BAA | IS RS SU RB BMW | 5 |
| i005 | Φ⊗ | 103 | ♯⅗ | SOLOMON | E | IS RS IC ICD RB BMW VZ | 7 |
| i006 | Φ♯ | 43 | φΓ | CHARM | F | RS ICD RB VZ | 4 |
| i007 | Φ⅗ | 147 | δ∞ | LAST SUPPER | G | CSX RS IC ICD SU RB BMW | 7 |
| i008 | Φε | 225 | ψ∂ | IDENTITY | H | IS CSX RS ICD RB BMW VZ | 7 |
| i009 | Φδ | 200 | Qε | CRYSTALLOGRAPHY | I | CSX RS IC ICD US | 5 |
| i010 | ΦΩ | 180 | Γ⊟ | JOHN VON NEUMANN | J | IS CSX RS ICD HY VZ | 6 |
| i011 | ΦΓ | 187 | ΓΓ | WAY TRUTH AND LIFE | K | IS RS ICD VZ | 4 |
| i012 | ΦQ | 150 | δ♯ | ELECTROMAGNETIC | L | IS RS ICD SU | 4 |
| i013 | ΦΣ | 178 | Γφ | STRING THEORY | M | CSX RS ICD | 3 |
| i014 | Φψ | 202 | QΩ | COINBASE TRANSACTION | N | IS CSX RS VZ | 4 |
| i015 | Φ𝟙 | 120 | ⅗ε | GOLDEN RATIO | O | IS RS ICD SU VZ | 5 |
| i016 | ∂Φ | 241 | 𝟙∂ | TWIN PRIME CONJECTURE | BAAL | IS RS ICD SU VZ | 5 |
| i017 | ∂∂ | 121 | ⅗δ | REVELATION | Q | IS CSX RS SU | 4 |
| i018 | ∂φ | 100 | ♯⊟ | PAROUSIA | CHAI | CSX RS | 2 |
| i019 | ∂∞ | 230 | ψ♯ | ZERO KNOWLEDGE PROOF | S | IS CSX RS | 3 |
| i020 | ∂⊟ | 90 | ⊗Ω | NAKAMOTO | APC | IS CSX RS ICD US HY | 6 |
| i021 | ∂⊗ | 49 | ∞∂ | LUKE | DICE | RS ICD SU VZ | 4 |
| i022 | ∂♯ | 222 | Σψ | SCHRODINGER EQUATION | BABEL | IS CSX RS ICD VZ | 5 |
| i023 | ∂⅗ | 190 | Γψ | IRRATIONAL NUMBER | CALEB | RS ICD | 2 |
| i024 | ∂ε | 75 | ⊟Γ | SHIFT | IO | IS CSX RS ICD | 4 |
| i025 | ∂δ | 72 | ⊟ε | BITCOIN | PI | IS CSX RS ICD MI | 5 |
| i026 | ∂Ω | 89 | ⊗δ | VIRUS | GOD | IS CSX RS ICD | 4 |
| i027 | ∂Γ | 238 | ψψ | FREE WILL | CAIN | IS CSX RS ICD | 4 |
| i028 | ∂Q | 101 | ♯⊗ | AMPLITUDE | SHA | CSX RS ICD | 3 |
| i029 | ∂Σ | 195 | Q∞ | FUNDAMENTAL THEOREM | AAVE | IS RS | 2 |
| i030 | ∂ψ | 60 | ∞Q | HOLY | ARK | IS CSX RS ICD HY | 5 |
| i031 | ∂𝟙 | 199 | Q⅗ | FERMAT LAST THEOREM | JACOB | CSX RS ICD VZ | 4 |
| i032 | φΦ | 249 | 𝟙δ | EDDINGTON LUMINOSITY | EVE | CSX RS ICD | 3 |
| i033 | φ∂ | 148 | δ⊟ | MORNING STAR | HAGGAI | CSX RS ICD | 3 |
| i034 | φφ | 189 | ΓΣ | ERWIN SCHRODINGER | FREE | CSX RS ICD VZ | 4 |
| i035 | φ∞ | 235 | ψΓ | BINOMIAL DISTRIBUTION | HAGAR | IS CSX RS ICD | 4 |
| i036 | φ⊟ | 50 | ∞φ | HIGGS | IMAM | CSX RS ICD | 3 |
| i037 | φ⊗ | 132 | ε⊟ | FLOWER OF LIFE | HADES | IS RS ICD | 3 |
| i038 | φ♯ | 115 | ⅗∞ | COMMANDMENT | NOAH | RS ICD | 2 |
| i039 | φ⅗ | 145 | δ∂ | ARK OF COVENANT | TEN | IS RS ICD | 3 |
| i040 | φε | 45 | φΣ | ELIJAH | DAVID | IS RS ICD HY VZ RM | 6 |
| i041 | φδ | 163 | Ω∞ | PLANCK CONSTANT | OMEGA | IS RS ICD | 3 |
| i042 | φΩ | 153 | δδ | ALBERT EINSTEIN | MIT | IS CSX RS ICD VZ | 5 |
| i043 | φΓ | 6 | Φ♯ | F | CHARM | IS RS ICD VZ | 4 |
| i044 | φQ | 111 | ♯𝟙 | CONFUCIUS | BRIAN | IS CSX RS ICD VZ | 5 |
| i045 | φΣ | 40 | φε | DAVID | ELIJAH | IS CSX RS ICD VZ | 5 |
| i046 | φψ | 95 | ⊗𝟙 | ETHEREUM | SHADDAI | RS ICD | 2 |
| i047 | φ𝟙 | 175 | Ω𝟙 | CONSCIOUSNESS | ISAIAH | CSX RS ICD | 3 |
| i048 | ∞Φ | 166 | Ω♯ | TETRAGRAMMATON | JAMES | CSX RS ICD | 3 |
| i049 | ∞∂ | 21 | ∂⊗ | DICE | LUKE | IS RS ICD RM | 4 |
| i050 | ∞φ | 36 | φ⊟ | IMAM | HIGGS | RS ICD MI | 3 |
| i051 | ∞∞ | 126 | ⅗ψ | COMPROMISE | NONCE | RS ICD | 2 |
| i052 | ∞⊟ | 173 | ΩΣ | TEN COMMANDMENTS | DEVIL | RS ICD | 2 |
| i053 | ∞⊗ | 97 | ♯∂ | POSEIDON | CARBON | RS | 1 |
| i054 | ∞♯ | 119 | ⅗⅗ | ARISTOTLE | LOVE | RS VZ | 2 |
| i055 | ∞⅗ | 243 | 𝟙∞ | FIRE OF HOLY SPIRIT | HEAVEN | IS RS RM | 3 |
| i056 | ∞ε | 179 | Γ∞ | EXCOMMUNICATION | CARDANO | RS | 1 |
| i057 | ∞δ | 248 | 𝟙ε | DOUBLE SLIT EXPERIMENT | PLANCK | IS RS VZ | 3 |
| i058 | ∞Ω | 226 | ψφ | FORGIVE US OUR DEBTS | BALDUR | RS | 1 |
| i059 | ∞Γ | 61 | ∞Σ | PSALM | SHIVA | IS RS VZ RM | 4 |
| i060 | ∞Q | 30 | ∂ψ | ARK | HOLY | RS ICD VZ MI | 4 |
| i061 | ∞Σ | 59 | ∞Γ | SHIVA | PSALM | RS ICD VZ | 3 |
| i062 | ∞ψ | 228 | ψ⊟ | QUANTUM SUPREMACY | FIBONACCI | RS ICD VZ | 3 |
| i063 | ∞𝟙 | 102 | ♯♯ | YGGDRASIL | MUON | RS ICD | 2 |
| i064 | ⊟Φ | 253 | 𝟙Σ | INCOMPLETENESS THEOREM | ISRAEL | IS RS ICD | 3 |
| i065 | ⊟∂ | 87 | ⊗⅗ | PRAXIS | SEVEN | IS RS ICD VZ RM | 5 |
| i066 | ⊟φ | 74 | ⊟Ω | CROSS | MOLOCH | IS RS ICD | 3 |
| i067 | ⊟∞ | 234 | ψΩ | CHINESE REMAINDER | SOUL | RS ICD | 2 |
| i068 | ⊟⊟ | 223 | Σ𝟙 | BOLTZMANN CONSTANT | SOPHIA | IS RS ICD VZ | 4 |
| i069 | ⊟⊗ | 149 | δ⊗ | KINGDOM OF HEAVEN | GLUON | IS RS ICD VZ RM | 5 |
| i070 | ⊟♯ | 246 | 𝟙♯ | INTERNATIONALIZATION | LILITH | IS RS ICD | 3 |
| i071 | ⊟⅗ | 181 | Γ⊗ | SATOSHI NAKAMOTO | TEMPLE | IS RS ICD VZ | 4 |
| i072 | ⊟ε | 25 | ∂δ | PI | BITCOIN | IS RS ICD VZ | 4 |
| i073 | ⊟δ | 169 | Ωδ | PREDESTINATION | WALLET | IS RS ICD VZ CC | 5 |
| i074 | ⊟Ω | 66 | ⊟φ | MOLOCH | CROSS | IS RS ICD | 3 |
| i075 | ⊟Γ | 24 | ∂ε | IO | SHIFT | IS RS SU | 3 |
| i076 | ⊟Q | 186 | ΓΩ | LINUS TORVALDS | COHERENCE | IS RS ICD VZ | 4 |
| i077 | ⊟Σ | 247 | 𝟙⅗ | COUNTERREVOLUTION | CHRIST | IS RS ICD VZ | 4 |
| i078 | ⊟ψ | 201 | Qδ | SON OF THE LIVING GOD | GENESIS | IS RS ICD VZ | 4 |
| i079 | ⊟𝟙 | 244 | 𝟙⊟ | SUPERCONDUCTIVITY | NIRVANA | IS RS ICD VZ | 4 |
| i080 | ⊗Φ | 151 | δ⅗ | HOLY SPIRIT | REBIRTH | IS RS ICD VZ RM | 5 |
| i081 | ⊗∂ | 165 | Ω⊗ | TREE OF KNOWLEDGE | HORUS | IS RS ICD | 3 |
| i082 | ⊗φ | 210 | Σφ | VIRTUAL CURRENCY | ARMAGEDDON | IS RS ICD VZ | 4 |
| i083 | ⊗∞ | 96 | ♯Φ | BEETHOVEN | PRAYER | IS RS ICD VZ | 4 |
| i084 | ⊗⊟ | 205 | QΣ | PROOF OF HISTORY | LEONARDO | IS RS VZ | 3 |
| i085 | ⊗⊗ | 127 | ⅗𝟙 | ORIGINAL SIN | ESCHATON | IS RS ICD VZ | 4 |
| i086 | ⊗♯ | 3 | Φ∞ | C | TIKKUN | IS RS ICD VZ | 4 |
| i087 | ⊗⅗ | 65 | ⊟∂ | SEVEN | PRAXIS | IS RS ICD VZ | 4 |
| i088 | ⊗ε | 184 | Γε | SEND FORTY TWO | ONE LOVE | IS RS ICD VZ | 4 |
| i089 | ⊗δ | 26 | ∂Ω | GOD | VIRUS | IS RS ICD VZ | 4 |
| i090 | ⊗Ω | 20 | ∂⊟ | APC | NAKAMOTO | IS RS US VZ RM | 5 |
| i091 | ⊗Γ | 209 | Σ∂ | QUANTUM GRAVITY | SPIRIT | IS RS | 2 |
| i092 | ⊗Q | 176 | ΓΦ | DECENTRALIZATION | CHRONOS | RS VZ | 2 |
| i093 | ⊗Σ | 152 | δε | FORTY YEARS | SATURN | IS RS | 2 |
| i094 | ⊗ψ | 216 | Σε | EQUIVALENCE PRINCIPLE | HAL FINNEY | IS RS US | 3 |
| i095 | ⊗𝟙 | 46 | φψ | SHADDAI | ETHEREUM | IS RS ICD | 3 |
| i096 | ♯Φ | 83 | ⊗∞ | PRAYER | BEETHOVEN | IS RS ICD VZ | 4 |
| i097 | ♯∂ | 53 | ∞⊗ | CARBON | POSEIDON | IS RS ICD VZ | 4 |
| i098 | ♯φ | 139 | εΓ | ENCRYPTION | LAZARUS | RS ICD VZ | 3 |
| i099 | ♯∞ | 135 | ε⅗ | BURNING BUSH | RAPTURE | IS RS ICD VZ | 4 |
| i100 | ♯⊟ | 18 | ∂φ | CHAI | PAROUSIA | RS SS VZ RM MI | 5 |
| i101 | ♯⊗ | 28 | ∂Q | SHA | AMPLITUDE | RS | 1 |
| i102 | ♯♯ | 63 | ∞𝟙 | MUON | YGGDRASIL | RS US HW | 3 |
| i103 | ♯⅗ | 5 | Φ⊗ | E | SOLOMON | RS | 1 |
| i104 | ♯ε | 215 | Σ⅗ | DELIVER US FROM EVIL | ANTHROPIC | CSX RS | 2 |
| i105 | ♯δ | 164 | Ω⊟ | PNEUMATOLOGY | TAPROOT | IS RS | 2 |
| i106 | ♯Ω | 177 | Γ∂ | CONSTANTINOPLE | NEFERTITI | RS | 1 |
| i107 | ♯Γ | 245 | 𝟙⊗ | THEORY OF EVERYTHING | QUANTUM | RS SU VZ | 3 |
| i108 | ♯Q | 188 | ΓQ | CROWN OF THORNS | SHAKESPEARE | RS VZ | 2 |
| i109 | ♯Σ | 224 | ψΦ | MARKET CAPITALIZATION | NIETZSCHE | RS | 1 |
| i110 | ♯ψ | 250 | 𝟙Ω | CONSERVATION OF ENERGY | FRAMEWORK | IS RS SS VZ HW RM | 6 |
| i111 | ♯𝟙 | 44 | φQ | BRIAN | CONFUCIUS | CSX RS VZ | 3 |
| i112 | ⅗Φ | 218 | ΣΩ | QUANTUM COMPUTER | IMAGINATION | CSX RS VZ | 3 |
| i113 | ⅗∂ | 116 | ⅗⊟ | BYZANTINE | ENTROPY | CSX RS VZ HW | 4 |
| i114 | ⅗φ | 124 | ⅗Q | OPPENHEIMER | FREQUENCY | CSX RS VZ HW | 4 |
| i115 | ⅗∞ | 38 | φ♯ | NOAH | COMMANDMENT | IS CSX RS RM | 4 |
| i116 | ⅗⊟ | 113 | ⅗∂ | ENTROPY | BYZANTINE | CSX RS VZ | 3 |
| i117 | ⅗⊗ | 134 | ε♯ | PRIME NUMBER | BOLTZMANN | CSX RS VZ RM | 4 |
| i118 | ⅗♯ | 159 | δ𝟙 | SEMICONDUCTOR | EMERALD TABLET | RS VZ | 2 |
| i119 | ⅗⅗ | 54 | ∞♯ | LOVE | ARISTOTLE | CSX RS VZ RM | 4 |
| i120 | ⅗ε | 15 | Φ𝟙 | O | GOLDEN RATIO | RS HW RM | 3 |
| i121 | ⅗δ | 17 | ∂∂ | Q | REVELATION | RS VZ | 2 |
| i122 | ⅗Ω | 158 | δψ | SACRED GEOMETRY | INTERFERENCE | RS VZ HW | 3 |
| i123 | ⅗Γ | 140 | εQ | ATTENUATION | COPERNICUS | RS IO | 2 |
| i124 | ⅗Q | 114 | ⅗φ | FREQUENCY | OPPENHEIMER | IS RS IO | 3 |
| i125 | ⅗Σ | 220 | ΣQ | CENTRAL LIMIT THEOREM | TRANSCENDENCE | CSX RS IO VZ RM | 5 |
| i126 | ⅗ψ | 51 | ∞∞ | NONCE | COMPROMISE | IS CSX RS VZ HW | 5 |
| i127 | ⅗𝟙 | 85 | ⊗⊗ | ESCHATON | ORIGINAL SIN | RS IO | 2 |
| i128 | εΦ | 255 | 𝟙𝟙 | GRAVITATIONAL CONSTANT | TRANSFERENCE | CSX RS VZ | 3 |
| i129 | ε∂ | 2 | Φφ | B | ROOT OF DAVID | IS CSX IO US VZ | 5 |
| i130 | εφ | 172 | ΩQ | QUANTUM STATE | PYTHAGORAS | US VZ RM | 3 |
| i131 | ε∞ | 206 | Qψ | ANTHROPIC PRINCIPLE | SUPERNOVA | CSX IO US VZ | 4 |
| i132 | ε⊟ | 37 | φ⊗ | HADES | FLOWER OF LIFE | CSX VZ RM | 3 |
| i133 | ε⊗ | 143 | ε𝟙 | FEDERAL RESERVE | NORTH STAR | VZ | 1 |
| i134 | ε♯ | 117 | ⅗⊗ | BOLTZMANN | PRIME NUMBER | CSX US VZ RM | 4 |
| i135 | ε⅗ | 99 | ♯∞ | RAPTURE | BURNING BUSH | IS CSX IO | 3 |
| i136 | εε | 240 | 𝟙Φ | ROBE OF RIGHTEOUSNESS | VIRGIN MARY | CSX RM | 2 |
| i137 | εδ | 242 | 𝟙φ | HEISENBERG UNCERTAINTY | EYE OF HORUS | CSX | 1 |
| i138 | εΩ | 203 | QΓ | COLLATZ CONJECTURE | GLORIFICATION | CSX VZ | 2 |
| i139 | εΓ | 98 | ♯φ | LAZARUS | ENCRYPTION | VZ | 1 |
| i140 | εQ | 123 | ⅗Γ | COPERNICUS | ATTENUATION | US VZ RM | 3 |
| i141 | εΣ | 144 | δΦ | MASS | PURIFICATION | CSX VZ | 2 |
| i142 | εψ | 219 | ΣΓ | DIVINE PROPORTION | ANTIPROTON | CSX | 1 |
| i143 | ε𝟙 | 133 | ε⊗ | NORTH STAR | FEDERAL RESERVE | CSX VZ | 2 |
| i144 | δΦ | 141 | εΣ | PURIFICATION | MASS | CSX VZ | 2 |
| i145 | δ∂ | 39 | φ⅗ | TEN | ARK OF COVENANT | CSX VZ RM | 3 |
| i146 | δφ | 213 | Σ⊗ | EXTRATERRESTRIAL | ENLIGHTENMENT | VZ | 1 |
| i147 | δ∞ | 7 | Φ⅗ | G | LAST SUPPER | CSX VZ RM | 3 |
| i148 | δ⊟ | 33 | φ∂ | HAGGAI | MORNING STAR | AA | 1 |
| i149 | δ⊗ | 69 | ⊟⊗ | GLUON | KINGDOM OF HEAVEN | VZ | 1 |
| i150 | δ♯ | 12 | ΦQ | L | ELECTROMAGNETIC | CSX VZ RM | 3 |
| i151 | δ⅗ | 80 | ⊗Φ | REBIRTH | HOLY SPIRIT | CSX VZ | 2 |
| i152 | δε | 93 | ⊗Σ | SATURN | FORTY YEARS | VZ | 1 |
| i153 | δδ | 42 | φΩ | MIT | ALBERT EINSTEIN | SU VZ | 2 |
| i154 | δΩ | 252 | 𝟙Q | EINSTEIN FIELD EQUATIONS | ROAD TO DAMASCUS | CSX VZ RM | 3 |
| i155 | δΓ | 194 | Qφ | TWELVE APOSTLES | SINGULARITY | IS CSX VZ RM | 4 |
| i156 | δQ | 229 | ψ⊗ | FOR THINE IS THE KINGDOM | AS ABOVE SO BELOW | PX | 1 |
| i157 | δΣ | 239 | ψ𝟙 | POWER AND GLORY | FOUR HORSEMEN | CSX VZ | 2 |
| i158 | δψ | 122 | ⅗Ω | INTERFERENCE | SACRED GEOMETRY | CSX | 1 |
| i159 | δ𝟙 | 118 | ⅗♯ | EMERALD TABLET | SEMICONDUCTOR | CSX VZ | 2 |
| i160 | ΩΦ | 204 | QQ | CRYPTOCURRENCY | TWELVE TRIBES | VZ RM | 2 |
| i161 | Ω∂ | 174 | Ωψ | DO UNTO OTHERS | SEAL OF SOLOMON | CSX VZ RM | 3 |
| i162 | Ωφ | 211 | Σ∞ | MAXWELL EQUATIONS | PRESERVATION | CSX | 1 |
| i163 | Ω∞ | 41 | φδ | OMEGA | PLANCK CONSTANT | CSX VZ | 2 |
| i164 | Ω⊟ | 105 | ♯δ | TAPROOT | PNEUMATOLOGY | IS CSX | 2 |
| i165 | Ω⊗ | 81 | ⊗∂ | HORUS | TREE OF KNOWLEDGE | IS CSX RM | 3 |
| i166 | Ω♯ | 48 | ∞Φ | JAMES | TETRAGRAMMATON | CSX | 1 |
| i167 | Ω⅗ | 237 | ψΣ | TRANSUBSTANTIATION | EYE OF PROVIDENCE | VZ | 1 |
| i168 | Ωε | 231 | ψ⅗ | THE LORD IS MY SHEPHERD | NANOTECHNOLOGY | CSX | 1 |
| i169 | Ωδ | 73 | ⊟δ | WALLET | PREDESTINATION | IS CSX | 2 |
| i170 | ΩΩ | 192 | QΦ | PERMISSIONLESS | IMAGINARY NUMBER | IS CSX VZ RM | 4 |
| i171 | ΩΓ | 254 | 𝟙ψ | ZERO KNOWLEDGE ROLLUP | EVENT HORIZON | CSX VZ | 2 |
| i172 | ΩQ | 130 | εφ | PYTHAGORAS | QUANTUM STATE | IS CSX VZ | 3 |
| i173 | ΩΣ | 52 | ∞⊟ | DEVIL | TEN COMMANDMENTS | VZ | 1 |
| i174 | Ωψ | 161 | Ω∂ | SEAL OF SOLOMON | DO UNTO OTHERS | CSX VZ | 2 |
| i175 | Ω𝟙 | 47 | φ𝟙 | ISAIAH | CONSCIOUSNESS | IS VZ RM | 3 |
| i176 | ΓΦ | 92 | ⊗Q | CHRONOS | DECENTRALIZATION | IS VZ | 2 |
| i177 | Γ∂ | 106 | ♯Ω | NEFERTITI | CONSTANTINOPLE | CSX VZ | 2 |
| i178 | Γφ | 13 | ΦΣ | M | STRING THEORY | CSX VZ | 2 |
| i179 | Γ∞ | 56 | ∞ε | CARDANO | EXCOMMUNICATION | VZ | 1 |
| i180 | Γ⊟ | 10 | ΦΩ | J | JOHN VON NEUMANN | IS CSX SU VZ RM | 5 |
| i181 | Γ⊗ | 71 | ⊟⅗ | TEMPLE | SATOSHI NAKAMOTO | IS CSX VZ | 3 |
| i182 | Γ♯ | 233 | ψδ | COLLISION RESISTANT | SYNCHRONICITY | IS CSX VZ | 3 |
| i183 | Γ⅗ | 191 | Γ𝟙 | MONETARY POLICY | TRANSFORMATION | CSX VZ | 2 |
| i184 | Γε | 88 | ⊗ε | ONE LOVE | SEND FORTY TWO | IS CSX VZ | 3 |
| i185 | Γδ | 232 | ψε | TOPOLOGICAL QUANTUM | BOOK OF REVELATION | IS CSX SU VZ | 4 |
| i186 | ΓΩ | 76 | ⊟Q | COHERENCE | LINUS TORVALDS | CSX VZ | 2 |
| i187 | ΓΓ | 11 | ΦΓ | K | WAY TRUTH AND LIFE | CSX SS VZ | 3 |
| i188 | ΓQ | 108 | ♯Q | SHAKESPEARE | CROWN OF THORNS | CSX VZ | 2 |
| i189 | ΓΣ | 34 | φφ | FREE | ERWIN SCHRODINGER | IS CSX VZ | 3 |
| i190 | Γψ | 23 | ∂⅗ | CALEB | IRRATIONAL NUMBER | IS CSX | 2 |
| i191 | Γ𝟙 | 183 | Γ⅗ | TRANSFORMATION | MONETARY POLICY | CSX US VZ | 3 |
| i192 | QΦ | 170 | ΩΩ | IMAGINARY NUMBER | PERMISSIONLESS | CSX US VZ | 3 |
| i193 | Q∂ | 4 | Φ⊟ | BAA | INFRASTRUCTURE | US VZ | 2 |
| i194 | Qφ | 155 | δΓ | SINGULARITY | TWELVE APOSTLES | IS VZ | 2 |
| i195 | Q∞ | 29 | ∂Σ | AAVE | FUNDAMENTAL THEOREM | IS CSX VZ RM | 4 |
| i196 | Q⊟ | 198 | Q♯ | BEAUTIFUL DOORWAY | SUPERPOSITION | IS CSX VZ | 3 |
| i197 | Q⊗ | 227 | ψ∞ | LAMB OF GOD | SEVEN TRUMPETS | CSX VZ | 2 |
| i198 | Q♯ | 196 | Q⊟ | SUPERPOSITION | BEAUTIFUL DOORWAY | CSX VZ | 2 |
| i199 | Q⅗ | 31 | ∂𝟙 | JACOB | FERMAT LAST THEOREM | VZ | 1 |
| i200 | Qε | 9 | Φδ | I | CRYSTALLOGRAPHY | SU SS VZ HW RM | 5 |
| i201 | Qδ | 78 | ⊟ψ | GENESIS | SON OF THE LIVING GOD | VZ | 1 |
| i202 | QΩ | 14 | Φψ | N | COINBASE TRANSACTION | VZ HW | 2 |
| i203 | QΓ | 138 | εΩ | GLORIFICATION | COLLATZ CONJECTURE | VZ HW | 2 |
| i204 | QQ | 160 | ΩΦ | TWELVE TRIBES | CRYPTOCURRENCY | VZ RM | 2 |
| i205 | QΣ | 84 | ⊗⊟ | LEONARDO | PROOF OF HISTORY | IS VZ HW RM | 4 |
| i206 | Qψ | 131 | ε∞ | SUPERNOVA | ANTHROPIC PRINCIPLE | VZ | 1 |
| i207 | Q𝟙 | 221 | ΣΣ | INDUSTRIALIZATION | CHAIN REORGANIZATION | VZ | 1 |
| i208 | ΣΦ | 236 | ψQ | BOSE EINSTEIN | WELL TEMPERED CLAVIER | VZ | 1 |
| i209 | Σ∂ | 91 | ⊗Γ | SPIRIT | QUANTUM GRAVITY | VZ | 1 |
| i210 | Σφ | 82 | ⊗φ | ARMAGEDDON | VIRTUAL CURRENCY | IS IE VZ RM MI | 5 |
| i211 | Σ∞ | 162 | Ωφ | PRESERVATION | MAXWELL EQUATIONS | IE SU VZ RM | 4 |
| i212 | Σ⊟ | 217 | Σδ | SIGNAL SIXTY TWO | PHOTOSYNTHESIS | US VZ RM | 3 |
| i213 | Σ⊗ | 146 | δφ | ENLIGHTENMENT | EXTRATERRESTRIAL | VZ HW | 2 |
| i214 | Σ♯ | 251 | 𝟙Γ | CENSORSHIP RESISTANT | PYTHAGOREAN THEOREM | VZ HW | 2 |
| i215 | Σ⅗ | 104 | ♯ε | ANTHROPIC | DELIVER US FROM EVIL | IS SU VZ RM | 4 |
| i216 | Σε | 94 | ⊗ψ | HAL FINNEY | EQUIVALENCE PRINCIPLE | VZ RM | 2 |
| i217 | Σδ | 212 | Σ⊟ | PHOTOSYNTHESIS | SIGNAL SIXTY TWO | IE VZ | 2 |
| i218 | ΣΩ | 112 | ⅗Φ | IMAGINATION | QUANTUM COMPUTER | IE VZ RM | 3 |
| i219 | ΣΓ | 142 | εψ | ANTIPROTON | DIVINE PROPORTION | IE VZ | 2 |
| i220 | ΣQ | 125 | ⅗Σ | TRANSCENDENCE | CENTRAL LIMIT THEOREM | IS SU VZ HW RM | 5 |
| i221 | ΣΣ | 207 | Q𝟙 | CHAIN REORGANIZATION | INDUSTRIALIZATION | SU VZ RM | 3 |
| i222 | Σψ | 22 | ∂♯ | BABEL | SCHRODINGER EQUATION | SU VZ RM | 3 |
| i223 | Σ𝟙 | 68 | ⊟⊟ | SOPHIA | BOLTZMANN CONSTANT | VZ RM | 2 |
| i224 | ψΦ | 109 | ♯Σ | NIETZSCHE | MARKET CAPITALIZATION | SU VZ RM | 3 |
| i225 | ψ∂ | 8 | Φε | H | IDENTITY | IS IE SU VZ RM | 5 |
| i226 | ψφ | 58 | ∞Ω | BALDUR | FORGIVE US OUR DEBTS | IE VZ | 2 |
| i227 | ψ∞ | 197 | Q⊗ | SEVEN TRUMPETS | LAMB OF GOD | VZ | 1 |
| i228 | ψ⊟ | 62 | ∞ψ | FIBONACCI | QUANTUM SUPREMACY | VZ | 1 |
| i229 | ψ⊗ | 156 | δQ | AS ABOVE SO BELOW | FOR THINE IS THE KINGDOM | IS RM | 2 |
| i230 | ψ♯ | 19 | ∂∞ | S | ZERO KNOWLEDGE PROOF | SU VZ RM | 3 |
| i231 | ψ⅗ | 168 | Ωε | NANOTECHNOLOGY | THE LORD IS MY SHEPHERD | VZ | 1 |
| i232 | ψε | 185 | Γδ | BOOK OF REVELATION | TOPOLOGICAL QUANTUM | VZ | 1 |
| i233 | ψδ | 182 | Γ♯ | SYNCHRONICITY | COLLISION RESISTANT | VZ | 1 |
| i234 | ψΩ | 67 | ⊟∞ | SOUL | CHINESE REMAINDER | ICDd | 1 |
| i235 | ψΓ | 35 | φ∞ | HAGAR | BINOMIAL DISTRIBUTION | IS RM | 2 |
| i236 | ψQ | 208 | ΣΦ | WELL TEMPERED CLAVIER | BOSE EINSTEIN | RM | 1 |
| i237 | ψΣ | 167 | Ω⅗ | EYE OF PROVIDENCE | TRANSUBSTANTIATION | VZ | 1 |
| i238 | ψψ | 27 | ∂Γ | CAIN | FREE WILL | IS VZ | 2 |
| i239 | ψ𝟙 | 157 | δΣ | FOUR HORSEMEN | POWER AND GLORY | VZ | 1 |
| i240 | 𝟙Φ | 136 | εε | VIRGIN MARY | ROBE OF RIGHTEOUSNESS | IS RM | 2 |
| i241 | 𝟙∂ | 16 | ∂Φ | BAAL | TWIN PRIME CONJECTURE | VZ | 1 |
| i242 | 𝟙φ | 137 | εδ | EYE OF HORUS | HEISENBERG UNCERTAINTY | VZ RM | 2 |
| i243 | 𝟙∞ | 55 | ∞⅗ | HEAVEN | FIRE OF HOLY SPIRIT | VZ RM | 2 |
| i244 | 𝟙⊟ | 79 | ⊟𝟙 | NIRVANA | SUPERCONDUCTIVITY | IS VZ | 2 |
| i245 | 𝟙⊗ | 107 | ♯Γ | QUANTUM | THEORY OF EVERYTHING | VZ RM | 2 |
| i246 | 𝟙♯ | 70 | ⊟♯ | LILITH | INTERNATIONALIZATION | US VZ | 2 |
| i247 | 𝟙⅗ | 77 | ⊟Σ | CHRIST | COUNTERREVOLUTION | VZ | 1 |
| i248 | 𝟙ε | 57 | ∞δ | PLANCK | DOUBLE SLIT EXPERIMENT | VZ | 1 |
| i249 | 𝟙δ | 32 | φΦ | EVE | EDDINGTON LUMINOSITY | VZ | 1 |
| i250 | 𝟙Ω | 110 | ♯ψ | FRAMEWORK | CONSERVATION OF ENERGY | SU SS VZ HW RM MI | 6 |
| i251 | 𝟙Γ | 214 | Σ♯ | PYTHAGOREAN THEOREM | CENSORSHIP RESISTANT | VZ | 1 |
| i252 | 𝟙Q | 154 | δΩ | ROAD TO DAMASCUS | EINSTEIN FIELD EQUATIONS | VZ HW | 2 |
| i253 | 𝟙Σ | 64 | ⊟Φ | ISRAEL | INCOMPLETENESS THEOREM | HW | 1 |
| i254 | 𝟙ψ | 171 | ΩΓ | EVENT HORIZON | ZERO KNOWLEDGE ROLLUP | VZ | 1 |
| i255 | 𝟙𝟙 | 128 | εΦ | TRANSFERENCE | GRAVITATIONAL CONSTANT | IS VZ RM | 3 |
| i256 | ∂ΦΦ | 256 | ∂ΦΦ | BAAL SQUARED | BAAL SQUARED | VZ HW | 2 |
