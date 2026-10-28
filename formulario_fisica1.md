# Formulario Fisica 1 – Primo parziale

Convenzioni: asse y verso l'alto, g = 9,81 m/s², α = inclinazione piano, θ = angolo generico.

---

## 1. VETTORI E CINEMATICA

### Vettori
- **Modulo vettore:** |a| = √(aₓ² + a_y² + a_z²)
- **Componenti da modulo, angolo:** aₓ = a cosθ ; a_y = a sinθ
- **Direzione vettore:** tgθ = a_y / aₓ → θ = arctg(a_y / aₓ)
- **Versore:** û = a / |a|
- **Prodotto scalare:** a·b = |a||b| cosθ = aₓbₓ + a_yb_y + a_zb_z
- **Angolo tra vettori:** cosθ = a·b / (|a||b|)
- **Prodotto vettoriale modulo:** |a∧b| = |a||b| sinθ
- **Prodotto vettoriale componenti:** a∧b = (a_yb_z − a_zb_y) ûₓ + (a_zbₓ − aₓb_z) û_y + (aₓb_y − a_ybₓ) û_z
- **Polari → cartesiane:** x = r cosθ ; y = r sinθ
- **Cartesiane → polari:** r = √(x² + y²) ; θ = arctg(y/x)

### Cinematica generale
- **Vettore spostamento:** Δr = r(t+Δt) − r(t)
- **Velocità media:** v_m = Δr / Δt
- **Velocità, accelerazione istantanee:** v = dr/dt ; a = dv/dt = d²r/dt²
- **Posizione da velocità:** x(t) = x₀ + ∫ v(t) dt
- **Accelerazione tangenziale, normale:** a = (dv/dt) û_T + (v²/R) û_N

### Moto rettilineo uniforme
- **Legge oraria MRU:** x = x₀ + v t
- **Inverse MRU:** v = (x − x₀)/t ; t = (x − x₀)/v

### Moto uniformemente accelerato
- **Velocità MRUA:** v = v₀ + a t
- **Inverse velocità MRUA:** a = (v − v₀)/t ; t = (v − v₀)/a
- **Legge oraria MRUA:** x = x₀ + v₀ t + ½ a t²
- **Accelerazione da spazio, tempo:** a = 2(Δx − v₀t)/t²
- **Relazione senza tempo:** v² = v₀² + 2aΔx
- **Inverse senza tempo:** Δx = (v² − v₀²)/(2a) ; a = (v² − v₀²)/(2Δx)
- **Spazio arresto:** d = v₀² / (2a)
- **Caduta libera da h:** t = √(2h/g) ; v = √(2gh)
- **Lancio verticale, altezza massima:** h_max = v₀²/(2g) ; t_salita = v₀/g

### Moto parabolico
- **Componenti velocità iniziale:** v₀ₓ = v₀ cosθ ; v₀y = v₀ sinθ
- **Leggi orarie parabolico:** x = x₀ + v₀ₓ t ; y = y₀ + v₀y t − ½ g t²
- **Velocità istante t:** vₓ = v₀ₓ (costante) ; v_y = v₀y − g t
- **Modulo, angolo velocità:** v = √(vₓ² + v_y²) ; tgα = v_y / vₓ
- **Equazione traiettoria:** y = x tgθ − g x² / (2v₀² cos²θ)
- **Tempo salita vertice:** t_H = v₀ sinθ / g
- **Altezza massima:** h_max = v₀² sin²θ / (2g)
- **Tempo volo stessa quota:** t_v = 2v₀ sinθ / g
- **Gittata stessa quota:** x_G = v₀² sin2θ / g = 2x_H
- **Gittata massima (45°):** x_G,max = v₀² / g
- **Velocità iniziale da gittata:** v₀ = √(g x_G / sin2θ)
- **Tempo volo da gittata:** t = x_G / (v₀ cosθ)
- **Tempo volo da quota h:** t = [v₀y + √(v₀y² + 2gh)] / g
- **Gittata da quota h:** d = v₀ₓ · t
- **Lancio orizzontale da h:** t = √(2h/g) ; d = v₀ √(2h/g)
- **Velocità impatto suolo:** v = √(v₀² + 2gh)

### Moto circolare
- **Arco, angolo, raggio:** s = Rθ ; θ = s/R
- **Velocità angolare, tangenziale:** v = ωR ; ω = v/R
- **Vettore velocità rotazione:** v = ω ∧ r
- **Periodo, frequenza:** T = 2π/ω = 2πR/v ; f = 1/T ; ω = 2πf
- **Accelerazione centripeta:** a_c = v²/R = ω²R ; v = √(a_c R)
- **Accelerazione angolare:** α = dω/dt = a_T / R
- **Accelerazione totale circolare:** a = √(a_T² + a_c²)
- **Circolare uniformemente accelerato:** ω = ω₀ + αt ; θ = θ₀ + ω₀t + ½αt²
- **Circolare senza tempo:** ω² = ω₀² + 2αΔθ

### Uscita da guida ad arco
- **Quota salita arco θ:** Δh = R(1 − cosθ)
- **Avanzamento orizzontale arco θ:** Δx = R sinθ
- **Velocità uscita, componenti:** vₓ = v cosθ ; v_y = v sinθ

### Moto armonico semplice
- **Equazione differenziale armonica:** d²x/dt² + ω²x = 0
- **Legge oraria armonica:** x = A sin(ωt + φ)
- **Velocità, accelerazione armonica:** v = Aω cos(ωt + φ) ; a = −ω²x
- **Valori massimi armonici:** v_max = Aω ; a_max = Aω²
- **Periodo armonico:** T = 2π/ω ; ω = 2π/T

---

## 2. DINAMICA DEL PUNTO

### Principi
- **Secondo principio:** ΣF = m a ; a = ΣF/m ; m = ΣF/a
- **Terzo principio:** F₁₂ = −F₂₁
- **Forza peso:** P = m g
- **Normale piano orizzontale:** N = m g
- **Ascensore accelerato verso alto:** N = m(g + a)

### Attrito
- **Attrito statico massimo:** F_s ≤ μ_s N
- **Attrito dinamico:** F_d = μ_d N
- **Spinta orizzontale con attrito:** a = (F − μ_d mg)/m
- **Decelerazione solo attrito:** a = μ_d g ; d = v₀²/(2μ_d g)

### Piano inclinato
- **Componenti peso inclinato:** P∥ = mg sinα ; P⊥ = mg cosα
- **Normale piano inclinato:** N = mg cosα
- **Inclinato liscio:** a = g sinα
- **Discesa con attrito:** a = g(sinα − μ_d cosα)
- **Salita con attrito (decelerazione):** a = g(sinα + μ_d cosα)
- **Condizione equilibrio statico inclinato:** tgα ≤ μ_s
- **Attrito statico da angolo limite:** μ_s = tgα_lim
- **Attrito dinamico da accelerazione:** μ_d = (g sinα − a)/(g cosα)
- **Velocità fondo inclinato liscio:** v = √(2gL sinα)

### Forza elastica
- **Legge Hooke:** F = −k x ; k = F/x ; x = F/k
- **Equilibrio molla verticale:** kΔx = mg → Δx = mg/k
- **Equilibrio molla inclinata:** kΔx = mg sinα
- **Pulsazione massa-molla:** ω = √(k/m)
- **Periodo massa-molla:** T = 2π√(m/k) ; k = 4π²m/T²
- **Periodo pendolo semplice:** T = 2π√(L/g) ; L = gT²/(4π²)

### Corpi collegati da fune (stessa accelerazione)
- **Due corpi trainati orizzontale:** a = F/(m₁+m₂) ; T = m₁a
- **Tavolo liscio, massa appesa:** a = m₂g/(m₁+m₂) ; T = m₁m₂g/(m₁+m₂)
- **Tavolo con attrito, appesa:** a = (m₂ − μ_d m₁)g/(m₁+m₂)
- **Macchina Atwood:** a = (m₂−m₁)g/(m₁+m₂) ; T = 2m₁m₂g/(m₁+m₂)
- **Molla traina corpi inclinato:** a = [kΔx − (m₁+m₂)g sinα]/(m₁+m₂)
- **Tensione fune corpo trainato:** T = m₁(a + g sinα)

### Dinamica circolare
- **Forza centripeta:** F_c = m v²/R = m ω² R
- **Tensione pendolo punto basso:** T = mg + m v²/L
- **Tensione pendolo angolo θ:** T = mg cosθ + m v²/L
- **Reazione guida concava, angolo θ:** N = mg cosθ + m v²/R
- **Reazione guida convessa, angolo θ:** N = mg cosθ − m v²/R
- **Distacco guida convessa:** v² = gR cosθ
- **Velocità minima giro morte:** v_min = √(gR)
- **Curva piana velocità massima:** v_max = √(μ_s g R)

---

## 3. LAVORO ED ENERGIA

### Lavoro
- **Lavoro forza costante:** W = F s cosθ = F·s
- **Lavoro forza variabile:** W = ∫ F·ds
- **Lavoro forza peso:** W = −mg(z_B − z_A)
- **Lavoro forza elastica:** W = ½k x_A² − ½k x_B²
- **Lavoro attrito:** W = −μ_d N d
- **Potenza:** P = W/Δt = F·v

### Energia
- **Energia cinetica:** K = ½ m v² ; v = √(2K/m)
- **Teorema energia cinetica:** W_tot = ½mv_B² − ½mv_A²
- **Potenziale gravitazionale:** U = mgh ; h = U/(mg)
- **Potenziale elastico:** U = ½ k x² ; x = √(2U/k)
- **Forza da potenziale:** F = −dU/dx
- **Conservazione energia meccanica:** ½mv_A² + U_A = ½mv_B² + U_B
- **Forze non conservative:** W_nc = E_B − E_A

### Casi tipici
- **Velocità dopo dislivello h:** v = √(v₀² + 2gh)
- **Altezza raggiunta da v:** h = v²/(2g)
- **Velocità dopo arco salita:** v_C = √(v_B² − 2gR(1 − cosθ))
- **Pendolo velocità punto basso:** v = √(2gh) ; h = L(1 − cosθ)
- **Molla lancia massa:** v = x√(k/m)
- **Compressione massima da v:** x_max = v√(m/k)
- **Massa cade su molla:** x = [mg + √((mg)² + 2kmgh)]/k
- **Salita inclinato attrito, distanza:** d = v₀²/[2g(sinα + μ_d cosα)]
- **Molla rilasciata, corpi inclinati:** v = √[(kΔx² − 2(m₁+m₂)gΔx sinα)/(m₁+m₂)]
- **Compressione massima molla inclinata:** x = [−mg sinα + √((mg sinα)² + kmv²)]/k

---

## 4. IMPULSO, QUANTITÀ DI MOTO, URTI

- **Quantità di moto:** p = m v
- **Teorema impulso:** J = ∫F dt = Δp = m(v_f − v_i)
- **Impulso da fermo:** J = m v ; v = J/m
- **Forza media urto:** F_m = Δp/Δt = J/Δt
- **Conservazione quantità moto:** Σ m_i v_i = costante (se ΣF_est = 0)
- **Distacco da fermo:** m₁v₁ + m₂v₂ = 0 → v₂ = −m₁v₁/m₂
- **Molla tra due corpi liberi:** v₁ = Δx √(kM/(m(m+M))) ; v₂ = −m v₁/M
- **Urto completamente anelastico:** V = (m₁v₁ + m₂v₂)/(m₁+m₂)
- **Energia persa anelastico:** ΔK = ½ m₁m₂(v₁ − v₂)²/(m₁+m₂)
- **Altezza pendolo dopo urto:** h_f = V²/(2g)
- **Urto elastico, conservazioni:** p e K conservate
- **Urto elastico velocità finali:** v₁' = [(m₁−m₂)v₁ + 2m₂v₂]/(m₁+m₂) ; v₂' = [(m₂−m₁)v₂ + 2m₁v₁]/(m₁+m₂)
- **Elastico, bersaglio fermo:** v₁' = (m₁−m₂)v₁/(m₁+m₂) ; v₂' = 2m₁v₁/(m₁+m₂)
- **Elastico masse uguali:** velocità si scambiano
- **Coefficiente restituzione:** e = −(v₂' − v₁')/(v₂ − v₁)

---

## 5. SISTEMI DI PUNTI E CENTRO DI MASSA

- **Massa totale:** M = Σ m_i
- **Posizione centro massa:** r_CM = Σ m_i r_i / M
- **Componenti centro massa:** x_CM = Σ m_i x_i / M (idem y, z)
- **Centro massa due corpi:** x_CM = (m₁x₁ + m₂x₂)/(m₁+m₂)
- **Velocità centro massa:** v_CM = Σ m_i v_i / M = P/M
- **Accelerazione centro massa:** a_CM = Σ m_i a_i / M
- **Prima equazione cardinale:** ΣF_est = M a_CM = dP/dt
- **Sistema isolato:** v_CM = costante
- **Sistema inizialmente fermo:** v_CM = 0 sempre
- **Teorema König:** K = ½ M v_CM² + K'

---

## 6. MOMENTO DELLA FORZA E MOMENTO ANGOLARE

- **Momento forza:** τ = r ∧ F ; |τ| = r F sinθ
- **Momento angolare:** L = r ∧ m v ; |L| = r m v sinθ
- **Momento angolare circolare:** L = m R v = m R² ω
- **Teorema momento angolare:** dL/dt = τ
- **Seconda equazione cardinale:** dL/dt = τ_est
- **Conservazione momento angolare:** τ_est = 0 → L = costante

---

## 7. COSTANTI E TRIGONOMETRIA

- **Accelerazione gravità:** g = 9,81 m/s²
- **Seni, coseni notevoli:** sin30° = cos60° = 0,5 ; sin60° = cos30° = 0,866 ; sin45° = cos45° = 0,707
- **Tangenti notevoli:** tg30° = 0,577 ; tg45° = 1 ; tg60° = 1,732
- **Formula duplicazione:** sin2θ = 2 sinθ cosθ
- **Identità fondamentale:** sin²θ + cos²θ = 1
- **Equazione secondo grado:** x = [−b ± √(b² − 4ac)]/(2a)
- **Prefissi:** k = 10³ ; M = 10⁶ ; G = 10⁹ ; c = 10⁻² ; m = 10⁻³ ; μ = 10⁻⁶ ; n = 10⁻⁹
- **Unità derivate:** N = kg·m/s² ; J = N·m ; W = J/s ; N·s = kg·m/s
