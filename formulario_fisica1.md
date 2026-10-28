# Formulario Fisica 1 – Primo parziale

La versione da stampare, con i titoli evidenziati e gli schemi, è `formulario_fisica1.pdf`.

Da ricopiare a mano. In ogni sezione le formule sono in ordine di priorità: se manca spazio, taglia dal fondo della sezione.

Convenzioni: asse y verso l'alto; g = 9.81 m/s²; α = inclinazione del piano sull'orizzontale. θ è definito accanto alla formula. I moduli sono positivi.

## 0. Quale metodo usare

**Domanda → strumento**

- Accelerazione, tensione, reazione N, forza → DINAMICA (ΣF = ma)
- Velocità o quota tra due punti, senza tempo → ENERGIA
- Compressione massima molla → ENERGIA
- Tempo, gittata, moto dopo il distacco in volo → CINEMATICA / parabolico
- Urto, distacco, «fermi poi si separano» → QUANTITÀ DI MOTO
- Forza di durata trascurabile, impulso → J = Δp
- N o T in un punto curvo → ΣF radiale = mv²/R (v prima dall'energia)

**Parole chiave**

- «Istante iniziale», «accelerazione iniziale» → dinamica, forze in quell'istante
- «Molla torna a riposo», «arriva in B» → energia
- «Normale nulla», «si stacca» → N = 0 nell'equazione radiale
- «Completamente anelastico» → energia NON si conserva nell'urto
- «Parte da fermo» in sistema isolato → v_cm = 0
- «Liscio» → niente attrito; «con attrito» → W_attr = −μ_d N d

**Catene tipiche**

- Impulso → v_A; energia → v_B, v_C; dinamica circolare → N in C; parabolico → gittata
- Dinamica → a iniziale; energia → v a molla a riposo; energia → compressione max
- Quantità di moto (v_cm = 0) + energia → v blocco e v lastra
- Energia → v al fondo; urto → v'; energia → h_f
- Energia → v; ΣF radiale → T o N

Regola rapida: forze note e serve a o T → dinamica; due posizioni e serve v → energia; prima/dopo un urto → quantità di moto; mai energia per trovare un tempo.


## 1. Vettori e analisi dimensionale


### Vettori

- **Modulo vettore** — |a| = √(a_x² + a_y² + a_z²)  *[nel piano togli a_z]*
- **Componenti da modulo** — a_x = |a| cosθ ;  a_y = |a| sinθ  *[θ sull'asse x]*
- **Direzione vettore** — tgθ = a_y / a_x ;  θ = arctg(a_y / a_x)
- **Versore** — û = a / |a|
- **Prodotto scalare** — a·b = |a| |b| cosθ = a_x b_x + a_y b_y + a_z b_z
- **Angolo tra vettori** — cosθ = (a·b) / (|a| |b|)
- **Modulo prodotto vettoriale** — |a×b| = |a| |b| sinθ  *[θ tra i due vettori]*
- **Somma in componenti** — a_x = a_1x + a_2x  *[idem y, z]*
- **Posizione e polari** — x = r cosθ ;  y = r sinθ ;  r = √(x² + y²)
- **Angolo polare** — θ = arctg(y / x)  *[guarda il quadrante]*

### Analisi dimensionale

- **Dimensioni velocità** — [v] = L T⁻¹
- **Dimensioni accelerazione** — [a] = L T⁻²
- **Dimensioni forza** — [F] = M L T⁻² = [N]
- **Dimensioni quantità moto** — [p] = [impulso] = M L T⁻¹
- **Dimensioni energia** — [E] = [W] = M L² T⁻²
- **Dimensioni potenza** — [P] = M L² T⁻³
- **Dimensioni costante elastica** — [k] = M T⁻²
- **Dimensioni momento forza** — [M] = M L² T⁻²
- **Dimensioni momento angolare** — [L] = M L² T⁻¹
- **Dimensioni velocità angolare** — [ω] = T⁻¹ ;  [α] = T⁻²
- **Attrito adimensionale** — [μ] = 1 ;  [θ] = 1

*I due membri hanno le stesse dimensioni. Argomenti di sin, cos, tg, exp: adimensionali. Dimensioni sbagliate ⇒ risultato sbagliato.*

- **Unità newton** — 1 N = 1 kg·m/s²
- **Unità joule** — 1 J = 1 N·m = 1 kg·m²/s²
- **Unità watt** — 1 W = 1 J/s
- **Unità impulso** — 1 N·s = 1 kg·m/s

### Bassa priorità

- **Componenti prodotto vettoriale** — (a×b)_x = a_y b_z − a_z b_y ;  (a×b)_y = a_z b_x − a_x b_z ;  (a×b)_z = a_x b_y − a_y b_x
- **Prodotto misto nullo** — a·(a×b) = 0  *[a×b è perpendicolare ad a e a b]*

## 2. Cinematica del punto


### Traiettoria, posizione, velocità

- **Legge oraria** — x = x(t) ;  y = y(t) ;  z = z(t)
- **Traiettoria** — legame tra x, y, z senza il tempo
- **Vettore posizione** — r = (x, y, z)
- **Vettore spostamento** — Δr = r_B − r_A = (Δx, Δy, Δz)
- **Modulo spostamento** — |Δr| = √(Δx² + Δy² + Δz²)
- **Velocità media** — v_m = Δr / Δt
- **Velocità istantanea** — v = dr/dt ;  v_x = dx/dt  *[idem y, z]*
- **Accelerazione media** — a_m = Δv / Δt
- **Accelerazione istantanea** — a = dv/dt ;  a_x = dv_x/dt

### Moto rettilineo uniforme

- **Spazio MRU** — x = x_0 + v t
- **Velocità MRU** — v = (x − x_0) / t
- **Tempo MRU** — t = (x − x_0) / v

### Moto uniformemente accelerato


*a costante. a > 0 nel verso scelto come positivo.*

- **Velocità MRUA** — v = v_0 + a t
- **Accelerazione MRUA** — a = (v − v_0) / t
- **Tempo MRUA** — t = (v − v_0) / a
- **Spazio MRUA** — x = x_0 + v_0 t + ½ a t²
- **Velocità senza tempo** — v² = v_0² + 2 a Δx
- **Spazio senza tempo** — Δx = (v² − v_0²) / (2 a)
- **Accelerazione senza tempo** — a = (v² − v_0²) / (2 Δx)
- **Spazio di arresto** — d = v_0² / (2 |a|)  *[d è un modulo; a si oppone al moto]*

### Moto verticale


*Asse y verso l'alto: a = −g. Nei moduli qui sotto h è positivo.*

- **Caduta da fermo** — v = √(2 g h) ;  t = √(2 h / g) ;  h = ½ g t²
- **Quota da velocità** — h = v² / (2 g)
- **Lancio verso l'alto** — h_max = v_0² / (2 g) ;  v = 0 in cima
- **Tempo di salita** — t_sal = v_0 / g
- **Tempo volo verticale** — t_v = 2 v_0 / g  *[ritorna alla stessa quota]*
- **Velocità al ritorno** — v = −v_0  *[stessa quota, y verso l'alto]*
- **Lancio verso il basso** — v = √(v_0² + 2 g h)  *[v_0 è il modulo]*
- **Tempo lancio basso** — t = [−v_0 + √(v_0² + 2 g h)] / g  *[v_0 modulo, h discesa]*

### Traiettoria curvilinea

- **Velocità sul percorso** — v = ds/dt  *[s = ascissa curvilinea]*
- **Accelerazione tangenziale** — a_T = dv/dt
- **Accelerazione normale** — a_N = v² / ρ  *[verso il centro di curvatura]*
- **Accelerazione curvilinea** — a = a_T û_T + a_N û_N
- **Modulo accelerazione** — a = √(a_T² + a_N²)
- **Raggio di curvatura** — ρ = v² / a_N

### Bassa priorità

- **Posizione da velocità** — x = x_0 + ∫ v dt
- **Tempo da spazio** — t = [−v_0 ± √(v_0² + 2 a Δx)] / a  *[tieni il t > 0]*

## 3. Moto armonico semplice

- **Legge oraria armonica** — x = A sin(ω t + φ)  *[φ = fase iniziale]*
- **Velocità armonica** — v = A ω cos(ω t + φ)
- **Accelerazione armonica** — a = −ω² x
- **Partenza da estremo** — x = A cos(ω t) ;  v = −A ω sin(ω t)  *[fermo in x = A]*
- **Pulsazione** — ω = 2π / T = 2π f
- **Periodo e frequenza** — T = 2π / ω ;  f = 1/T ;  ω = 2π f
- **Velocità massima** — v_max = A ω ;  A = v_max / ω
- **Accelerazione massima** — a_max = A ω² = v_max² / A
- **Pulsazione molla** — ω = √(k / m)
- **Periodo molla** — T = 2π √(m / k)
- **Costante dalla molla** — k = 4π² m / T²
- **Massa dalla molla** — m = k T² / (4π²)
- **Periodo pendolo** — T = 2π √(L / g)  *[solo angoli piccoli]*
- **Lunghezza pendolo** — L = g T² / (4π²)
- **Energia armonica** — E = ½ k A² = ½ m v_max² = ½ m v² + ½ k x²
- **Ampiezza da energia** — A = √(2 E / k)
- **Equilibrio molla verticale** — Δ = m g / k  *[oscilla intorno a Δ, stesso T]*

### Bassa priorità

- **Gravità dal pendolo** — g = 4π² L / T²

## 4. Moto circolare e moto parabolico


### Circolare uniforme


*θ in radianti. a_N punta verso il centro.*

- **Arco e angolo** — s = R θ ;  θ = s / R ;  R = s / θ
- **Velocità e pulsazione** — v = ω R ;  ω = v / R ;  R = v / ω
- **Periodo circolare** — T = 2π R / v = 2π / ω
- **Frequenza circolare** — f = 1/T ;  ω = 2π f
- **Accelerazione centripeta** — a_N = v² / R = ω² R
- **Raggio da centripeta** — R = v² / a_N ;  v = √(a_N R)
- **Velocità angolare vettore** — v = ω × r ;  |v| = ω R

### Circolare accelerato

- **Pulsazione nel tempo** — ω = ω_0 + α t
- **Accelerazione angolare** — α = (ω − ω_0) / t = a_T / R
- **Angolo nel tempo** — θ = θ_0 + ω_0 t + ½ α t²
- **Pulsazione senza tempo** — ω² = ω_0² + 2 α Δθ
- **Angolo senza tempo** — Δθ = (ω² − ω_0²) / (2 α)

### Moto parabolico


*y verso l'alto, a_x = 0, a_y = −g. θ = angolo di lancio sull'orizzontale.*

- **Componenti velocità iniziale** — v_0x = v_0 cosθ ;  v_0y = v_0 sinθ
- **Moto orizzontale** — x = x_0 + v_0x t ;  v_x = v_0x  *[v_x resta costante]*
- **Moto verticale** — y = y_0 + v_0y t − ½ g t² ;  v_y = v_0y − g t
- **Equazione traiettoria** — y = y_0 + x tgθ − g x² / (2 v_0² cos²θ)  *[x misurata dal lancio]*
- **Tempo di salita** — t_H = v_0y / g = v_0 sinθ / g
- **Quota massima** — H = y_0 + v_0y² / (2 g) = y_0 + v_0² sin²θ / (2 g)
- **Tempo volo stessa quota** — t_v = 2 v_0 sinθ / g
- **Gittata stessa quota** — G = v_0² sin(2θ) / g = v_0x t_v
- **Gittata massima 45°** — G_max = v_0² / g
- **Velocità dalla gittata** — v_0 = √[ g G / sin(2θ) ]
- **Angolo dalla gittata** — sin(2θ) = g G / v_0²
- **Tempo dalla gittata** — t = G / (v_0 cosθ)  *[stessa quota]*
- **Modulo velocità** — v = √(v_x² + v_y²)
- **Angolo della velocità** — tgα = v_y / v_x
- **Impatto stessa quota** — il modulo torna v_0
- **Tempo, lanciato in alto** — t = [v_0y + √(v_0y² + 2 g h)] / g  *[h = metri di discesa fino all'arrivo; v_0y > 0]*
- **Tempo, lanciato in basso** — t = [−v_0y + √(v_0y² + 2 g h)] / g  *[v_0y è il modulo]*
- **Lancio orizzontale** — t = √(2 h / g) ;  G = v_0 √(2 h / g)
- **Gittata con dislivello** — G = v_0x · t  *[t da una delle formule sopra]*
- **Impatto più in basso** — v = √(v_0² + 2 g h)  *[qualsiasi angolo di lancio]*
- **Tempo arrivo più alto** — t = [v_0y − √(v_0y² − 2 g H)] / g  *[primo passaggio; serve v_0y² ≥ 2 g H]*
- **Secondo passaggio quota** — t = [v_0y + √(v_0y² − 2 g H)] / g
- **Impatto più in alto** — v = √(v_0² − 2 g H)

### Uscita da un arco


*Su una circonferenza l'angolo della tangente sull'orizzontale è uguale all'angolo del raggio sulla verticale. v_y > 0 se la tangente punta in alto.*

- **Quota sull'arco** — Δh = R (1 − cosθ)  *[θ del raggio, dalla verticale]*
- **Avanzamento sull'arco** — Δx = R sinθ  *[orizzontale, dallo stesso riferimento]*
- **Componenti uscita arco** — v_x = v cosθ ;  v_y = v sinθ  *[θ = inclinazione della tangente]*
- **Tempo fino al suolo** — t = [v_y + √(v_y² + 2 g h)] / g  *[h = quota di uscita sul suolo, v_y verso l'alto]*
- **Gittata dopo l'arco** — d = v_x · t

### Bassa priorità

- **Gradi e radianti** — θ_rad = θ° · π / 180 ;  180° = π ;  90° = π/2 ;  60° = π/3 ;  45° = π/4 ;  30° = π/6

## 5. Dinamica del punto


### Leggi, peso, equilibrio

- **Secondo principio** — ΣF = m a ;  a = ΣF / m ;  m = ΣF / a
- **Principio di inerzia** — ΣF = 0 ⇒ v costante  *[fermo oppure MRU]*
- **Terzo principio** — F_12 = −F_21  *[stessa retta, versi opposti]*
- **Forza peso** — P = m g
- **Equilibrio statico** — ΣF = 0 e v = 0
- **Equilibrio dinamico** — ΣF = 0 e v costante
- **Equilibrio momenti** — ΣM = 0  *[nessuna rotazione che accelera]*

*Forze: conservative o non conservative; interne o esterne; di contatto o a distanza.*


### Attrito radente

- **Attrito statico** — F_s ≤ μ_s N ;  μ_s = F_s,max / N
- **Attrito dinamico** — F_d = μ_d N  *[verso opposto al moto; μ_s > μ_d]*
- **Normale piano orizzontale** — N = m g
- **Trazione con attrito** — a = (F − μ_d m g) / m  *[F orizzontale]*
- **Arresto solo attrito** — |a| = μ_d g ;  d = v_0² / (2 μ_d g)
- **Forza minima spinta** — F_min = μ_s m g  *[per farlo partire, piano orizzontale]*

### Piano inclinato


*α = angolo del piano sull'orizzontale. N = mg cosα solo se niente altro spinge in direzione perpendicolare al piano.*

- **Quota e percorso** — h = s sinα ;  s = h / sinα
- **Base del percorso** — b = s cosα = h / tgα
- **Componenti del peso** — P_∥ = m g sinα ;  P_⊥ = m g cosα
- **Normale inclinato** — N = m g cosα
- **Inclinato liscio** — a = g sinα  *[verso la discesa]*
- **Discesa con attrito** — a = g (sinα − μ_d cosα)  *[parte da solo se tgα > μ_s]*
- **Attrito dalla discesa** — μ_d = (g sinα − a) / (g cosα)
- **Frenata in salita** — |a| = g (sinα + μ_d cosα)  *[modulo: il verso è opposto al moto]*
- **Arresto in salita** — d = v_0² / [2 g (sinα + μ_d cosα)]
- **Equilibrio sull'inclinato** — tgα ≤ μ_s
- **Attrito angolo limite** — μ_s = tg α_lim  *[α massimo da fermo]*
- **Velocità fondo liscio** — v = √(2 g h) = √(2 g s sinα)

### Molla e corpi collegati

- **Legge di Hooke** — F = −k x ;  k = |F| / |x|
- **Equilibrio molla verticale** — k Δ = m g ;  Δ = m g / k
- **Equilibrio molla inclinata** — k Δ = m g sinα ;  Δ = m g sinα / k
- **Trazione orizzontale** — a = F / (m1 + m2) ;  T = m1 a  *[m1 è il corpo trainato dalla fune]*
- **Tavolo liscio** — a = m2 g / (m1 + m2) ;  T = m1 m2 g / (m1 + m2)  *[m1 sul tavolo, m2 appesa]*
- **Tavolo con attrito** — a = (m2 − μ_d m1) g / (m1 + m2)  *[m1 sul tavolo, m2 appesa]*
- **Tensione fune tavolo** — T = m1 (a + μ_d g) = m2 (g − a)
- **Resta fermo se** — m2 ≤ μ_s m1  *[m1 sul tavolo]*
- **Macchina di Atwood** — a = (m2 − m1) g / (m1 + m2)  *[m2 è la più pesante, scende]*
- **Tensione Atwood** — T = 2 m1 m2 g / (m1 + m2) = m1 (g + a)

### Molla sul piano inclinato


*Molla fissata in alto. Verso positivo in salita. Quota: se la molla si accorcia di Δx il corpo sale di h = Δx sinα. Più corpi che restano collegati: al posto di m usa la massa totale. Se la fune si allenta, da lì in poi usa solo la massa ancora attaccata alla molla.*

- **Accelerazione iniziale** — a = [k Δx − (m1 + m2) g sinα] / (m1 + m2)  *[molla allungata, tira in salita]*
- **Tensione fune inclinata** — T = m1 (a + g sinα)  *[m1 è il corpo più in basso]*
- **Bilancio sale distendendo** — ½ k Δx² = ½ m v² + m g Δx sinα
- **Velocità sale distendendo** — v = √(k Δx² / m − 2 g Δx sinα)
- **Bilancio scende distendendo** — ½ k Δx² + m g Δx sinα = ½ m v²
- **Velocità scende distendendo** — v = √(k Δx² / m + 2 g Δx sinα)
- **Bilancio sale comprimendo** — ½ m v² = ½ k x² + m g x sinα
- **Compressione sale** — x = [−m g sinα + √((m g sinα)² + k m v²)] / k
- **Bilancio scende comprimendo** — ½ m v² + m g x sinα = ½ k x²
- **Compressione scende** — x = [+m g sinα + √((m g sinα)² + k m v²)] / k

### Dinamica circolare e arco


*θ = angolo tra il raggio e la verticale. θ = 0 nel punto più basso se il centro è sopra la guida, nel punto più alto se il centro è sotto. Il segno di N dipende da che parte sta la pista.*

- **Forza centripeta** — F_c = m v² / R = m ω² R  *[verso il centro]*
- **Normale, centro sopra** — N = m g cosθ + m v² / R  *[guida concava, corpo nella conca; θ dal basso]*
- **Normale in basso** — N = m g + m v² / R  *[θ = 0, centro sopra]*
- **Normale, centro sotto** — N = m g cosθ − m v² / R  *[dosso: il corpo sta sopra la pista; θ dalla cima]*
- **Normale in cima dosso** — N = m g − m v² / R  *[θ = 0]*
- **Distacco dal dosso** — N = 0 ⇒ v² = g R cosθ  *[in cima: v² = g R]*
- **Velocità dalla normale** — v = √[ R (N / m − g cosθ) ]  *[solo centro sopra la guida]*
- **Quota fra due punti** — Δh = R (1 − cosθ)
- **Avanzamento orizzontale** — Δx = R sinθ
- **Velocità salendo l'arco** — v_C = √[v_B² − 2 g R (1 − cosθ)]  *[C più in alto di B]*
- **Velocità scendendo l'arco** — v_C = √[v_B² + 2 g R (1 − cosθ)]
- **Raggio distacco in cima** — R = v_B² / [g (3 − 2 cosθ)]  *[C in cima con N = 0, centro sotto; B più in basso, angolo θ]*
- **Raggio distacco a 60°** — R = v_B² / (2 g)  *[caso θ = 60° della formula sopra]*
- **Tensione in basso** — T = m g + m v² / L  *[pendolo, punto più basso]*
- **Tensione ad angolo** — T = m g cosθ + m v² / L  *[θ dalla verticale, punto di sospensione sopra]*
- **Velocità dalla tensione** — v = √[ L (T / m − g cosθ) ]

### Giro della morte


*Pista sopra il corpo (anello), diversa dal dosso. Dislivello cima–fondo = 2R solo se il cerchio è completo.*

- **Normale in cima anello** — N = m v² / R − m g
- **Velocità minima in cima** — v ≥ √(g R)  *[altrimenti si stacca]*
- **Velocità minima in basso** — v ≥ √(5 g R)  *[per arrivare in cima con N = 0]*
- **Normale minima in basso** — N ≥ 6 m g  *[stesso caso]*

### Bassa priorità

- **Ascensore accelera su** — N = m (g + a)  *[a verso l'alto; in discesa a si sottrae]*
- **Curva piana attrito** — v_max = √(μ_s R g) ;  μ_s = v² / (R g)
- **Trazione con attrito sotto** — a = [F − μ_d (m1 + m2) g] / (m1 + m2) ;  T = m1 (a + μ_d g)  *[F su m2, m1 trainato]*

## 6. Quantità di moto e impulso

- **Quantità di moto** — p = m v ;  v = p / m
- **Impulso vettoriale** — J = Δp = m (v_f − v_i)
- **Impulso da fermo** — J = m v ;  v = J / m ;  m = J / v
- **Teorema dell'impulso** — J = ∫ F dt
- **Forza media** — F_m = Δp / Δt = J / Δt
- **Conservazione quantità moto** — ΣF_ext = 0 ⇒ p_tot costante
- **Conservazione per assi** — Σ m_i v_ix = costante  *[idem y, se quell'asse non ha forze esterne]*
- **Sistema parte fermo** — p_tot = 0 ⇒ m1 v1 + m2 v2 = 0
- **Velocità opposta** — v2 = − m1 v1 / m2

*Urto, distacco, molla tra due corpi: sezione 9 e 10. L'impulso di una forza di durata trascurabile è J = Δp, anche se F non si conosce.*


## 7. Lavoro, energia, conservazione


### Lavoro e potenza

- **Lavoro forza costante** — W = F s cosθ = F·s  *[θ tra F e spostamento]*
- **Lavoro forza variabile** — W = ∫ F·ds
- **Lavoro del peso** — W = −m g (z_B − z_A)  *[z verso l'alto]*
- **Lavoro peso discesa** — W = m g h  *[h = discesa]*
- **Lavoro forza elastica** — W = ½ k x_A² − ½ k x_B²  *[x dalla lunghezza a riposo]*
- **Lavoro attrito** — W_attr = −μ_d N d = −F_d d  *[sempre negativo, d percorso]*
- **Lavoro attrito inclinato** — W_attr = −μ_d m g s cosα  *[solo se N = m g cosα]*
- **Potenza media** — P = W / Δt
- **Potenza istantanea** — P = F·v

### Energie

- **Energia cinetica** — K = ½ m v² ;  v = √(2 K / m)
- **Teorema energia cinetica** — W_tot = ΔK = ½ m v_B² − ½ m v_A²
- **Potenziale peso** — U = m g h ;  h = U / (m g)
- **Potenziale elastico** — U = ½ k x² ;  x = √(2 U / k) ;  k = 2 U / x²
- **Forza dal potenziale** — F = − dU/dx
- **Conservazione energia** — ½ m v_A² + U_A = ½ m v_B² + U_B  *[solo forze conservative, W_nc = 0]*
- **Con forze non conservative** — W_nc = E_B − E_A  *[E = K + U]*
- **Velocità con attrito** — v_B = √[ v_A² + 2(U_A − U_B)/m + 2 W_nc/m ]

### Casi già risolti

- **Dopo un dislivello** — v = √(v_0² + 2 g h)  *[h discesa positiva; in salita h negativo dentro la radice, cioè v = √(v_0² − 2 g H)]*
- **Quota raggiunta** — H = v_0² / (2 g)  *[parte verso l'alto, v finale = 0]*
- **Molla orizzontale lancia** — v = x √(k / m) ;  x = v √(m / k)  *[parte da fermo, x = compressione]*
- **Compressione orizzontale** — x_max = v √(m / k)  *[molla ferma il corpo]*

*Inclinato, molla fissata in alto, h = Δx sinα. Masse collegate: m → massa totale. Fune allentata: solo la massa rimasta. Stesse formule della sezione 5: se le hai già copiate, salta queste quattro.*

- **Sale, molla si distende** — v = √(k Δx² / m − 2 g Δx sinα)
- **Scende, molla si distende** — v = √(k Δx² / m + 2 g Δx sinα)
- **Compressione, sta salendo** — x = [−m g sinα + √((m g sinα)² + k m v²)] / k
- **Compressione, sta scendendo** — x = [+m g sinα + √((m g sinα)² + k m v²)] / k
- **Salita su un arco** — v_C = √[v_B² − 2 g R (1 − cosθ)]  *[Δh = R(1 − cosθ); θ dalla verticale]*
- **Pendolo, punto basso** — v = √(2 g h) ;  h = L (1 − cosθ)  *[θ dalla verticale]*
- **Quota dopo l'urto** — h_f = v'² / (2 g)
- **Arresto in salita** — d = v_0² / [2 g (sinα + μ_d cosα)]

### Bassa priorità

- **Caduta sulla molla** — x = [m g + √((m g)² + 2 k m g h)] / k  *[fermo, h sopra la molla a riposo; x compressione]*

## 8. Momento della forza e momento angolare

- **Momento della forza** — M = r × F
- **Modulo del momento** — |M| = r F sinθ = F b  *[b = r sinθ = braccio; θ tra r e F]*
- **Braccio** — b = |M| / F ;  F = |M| / b
- **Momento angolare** — L = r × p = r × (m v)
- **Modulo momento angolare** — |L| = r m v sinθ  *[θ tra r e v]*
- **Circolare rispetto al centro** — L = m R v = m R² ω  *[verso di ω, perpendicolare al piano]*
- **Teorema momento angolare** — dL/dt = M  *[r misurato da un punto fisso, oppure dal CM]*
- **Seconda cardinale** — dL_tot / dt = M_ext
- **Conservazione momento angolare** — M_ext = 0 ⇒ L costante

*Componenti di r×F: come a×b, sezione 1. Le coppie interne azione-reazione sulla stessa retta hanno momento totale nullo: per questo conta solo M_ext.*


## 9. Sistemi, centro di massa, riferimenti

- **Massa totale** — M = Σ m_i
- **Posizione centro massa** — r_cm = (Σ m_i r_i) / M
- **Componenti centro massa** — x_cm = (Σ m_i x_i) / M  *[idem y, z]*
- **Centro massa due corpi** — x_cm = (m1 x1 + m2 x2) / (m1 + m2)
- **Velocità centro massa** — v_cm = (Σ m_i v_i) / M = p_tot / M
- **Accelerazione centro massa** — a_cm = (Σ m_i a_i) / M
- **Prima equazione cardinale** — ΣF_ext = M a_cm = dp_tot / dt
- **Sistema isolato** — ΣF_ext = 0 ⇒ v_cm costante
- **Parte da fermo** — v_cm = 0 per tutto il moto  *[solo se è isolato]*

### Laboratorio e centro di massa

- **Velocità nel CM** — v'_i = v_i − v_cm
- **Quantità di moto nel CM** — P' = Σ m_i v'_i = 0
- **Teorema di König** — K = ½ M v_cm² + K'  *[K' = Σ ½ m_i v'_i²]*
- **Velocità relativa** — v1 − v2 = v'_1 − v'_2  *[non cambia col riferimento]*
- **Momento angolare lab/CM** — L = L_cm + r_cm × (M v_cm)
- **Elastico nel CM** — v'_f = − v'_i  *[urto 1D: ogni velocità si inverte]*
- **Anelastico completo nel CM** — K' finale = 0  *[nel CM i corpi si fermano]*
- **Anelastico nel CM** — v'_f = −e v'_i  *[e = coefficiente di restituzione]*

### Blocco sulla lastra, molla


*Niente attrito, tutto parte fermo. La molla è fissata alla lastra: quando torna a riposo il blocco si stacca. Δx = d_0 − d.*

- **Centro di massa fermo** — v_cm = 0
- **Energia della molla** — E = ½ k Δx²
- **Quantità di moto nulla** — m v + M V = 0
- **Conservazione energia** — ½ k Δx² = ½ m v² + ½ M V²
- **Velocità del blocco** — v = √[ 2 E M / (m (m + M)) ]
- **Velocità della lastra** — V = − m v / M  *[verso opposto al blocco]*

## 10. Urti


*Durante l'urto le forze interne sono impulsive: p si conserva se le forze esterne non sono impulsive. K si conserva solo se l'urto è elastico. 1D, sulla retta dell'urto.*

- **Conservazione nell'urto** — m1 v1 + m2 v2 = m1 v1' + m2 v2'
- **Coefficiente restituzione** — e = (v2' − v1') / (v1 − v2)
- **Casi del coefficiente** — e = 1 elastico ;  e = 0 completamente anelastico ;  0 < e < 1 anelastico
- **Velocità dopo l'urto** — v1' = [m1 v1 + m2 v2 − m2 e (v1 − v2)] / (m1 + m2)
- **Velocità del bersaglio** — v2' = [m1 v1 + m2 v2 + m1 e (v1 − v2)] / (m1 + m2)
- **Elastico bersaglio fermo** — v1' = (m1 − m2) v1 / (m1 + m2) ;  v2' = 2 m1 v1 / (m1 + m2)
- **Elastico masse uguali** — v1' = v2 ;  v2' = v1  *[si scambiano le velocità]*
- **Anelastico completo** — V = (m1 v1 + m2 v2) / (m1 + m2)  *[restano attaccati, stessa velocità]*
- **Bersaglio fermo anelastico** — V = m1 v1 / (m1 + m2)
- **Massa ridotta** — μ = m1 m2 / (m1 + m2)
- **Energia persa completa** — ΔK = ½ μ (v1 − v2)²
- **Persa, bersaglio fermo** — ΔK = K_i · m2 / (m1 + m2)  *[K_i = ½ m1 v1²]*
- **Energia persa parziale** — ΔK = ½ μ (1 − e²) (v1 − v2)²
- **Pendolo dopo urto anelastico** — v' = m1 v / (m1 + m2) ;  h_f = v'² / (2 g)  *[bersaglio fermo, poi salgono insieme]*

### Bassa priorità

- **Urto in due dimensioni** — p si conserva su x e su y separatamente  *[e solo lungo la congiungente i centri]*

## 11. Teoria in promemoria


*All'esame queste vanno riscritte con una frase, non solo con la formula: il testo lo dice esplicitamente.*


*5.1 Moto uniformemente accelerato. a costante ⇒ v = v_0 + a t. La legge oraria è l'integrale: x = x_0 + ∫ v dt = x_0 + v_0 t + ½ a t².*


*5.2 Forza conservativa. Il lavoro non dipende dal percorso e su un percorso chiuso è nullo. Si può definire un'energia potenziale con W = −ΔU, e F = −dU/dx. Peso e molla lo sono; l'attrito no.*


*5.3 Attrito. Statico: si oppone allo scivolamento che sta per iniziare, F_s ≤ μ_s N, con μ_s = F_s,max / N. Dinamico: durante lo strisciamento, F_d = μ_d N, verso opposto alla velocità. In genere μ_s > μ_d.*


*5.4 Momenti. M = r×F, L = r×p, e per un punto dL/dt = M. Per un sistema dL_tot/dt = M_ext: le coppie interne (azione e reazione sulla stessa retta) hanno momento totale nullo, quindi restano solo i momenti esterni.*


*Urti, in una riga. Elastico: si conservano p e K (e = 1). Completamente anelastico: si conserva p, i corpi restano uniti, K diminuisce (e = 0). Anelastico: si conserva p, K diminuisce solo in parte (0 < e < 1).*


## 12. Costanti e trigonometria

- **Gravità e pi greco** — g = 9.81 m/s² ;  π = 3.1416 ;  π² ≈ 9.87
- **Seni e coseni** — sin30 = cos60 = 1/2 ;  sin45 = cos45 = √2/2 ;  sin60 = cos30 = √3/2 ;  sin90 = 1 ;  cos90 = 0 ;  sin0 = 0 ;  cos0 = 1
- **Decimali notevoli** — √2 ≈ 1.414 ;  √3 ≈ 1.732 ;  √2/2 ≈ 0.707 ;  √3/2 ≈ 0.866
- **Tangenti** — tg30 = 1/√3 ≈ 0.577 ;  tg45 = 1 ;  tg60 = √3 ≈ 1.732 ;  tg0 = 0
- **Angolo doppio** — sin(2θ) = 2 sinθ cosθ
- **Identità fondamentale** — sin²θ + cos²θ = 1
- **Radianti degli angoli** — 30° = π/6 ;  45° = π/4 ;  60° = π/3 ;  90° = π/2 ;  180° = π
- **Equazione secondo grado** — a x² + b x + c = 0 ⇒ x = [−b ± √(b² − 4 a c)] / (2 a)

### Bassa priorità

- **Coseno doppio** — cos(2θ) = cos²θ − sin²θ = 2 cos²θ − 1 = 1 − 2 sin²θ
- **Prefissi** — k = 10³ ;  M = 10⁶ ;  G = 10⁹ ;  c = 10⁻² ;  m = 10⁻³ ;  μ = 10⁻⁶ ;  n = 10⁻⁹
- **Stima rapida** — se serve un ordine di grandezza: g ≈ 10, π² ≈ 10


---

# NON COPIARE — nota di controllo

Questa nota non fa parte del formulario.

Nessun limite di pagine era indicato (il segnaposto era vuoto). Nel PDF le formule e gli schemi occupano 6 pagine; l'ultima pagina è la nota e non va copiata.

Le ipotesi geometriche e le formule senza un numero dei tuoi testi sono nella pagina finale del file Word.

