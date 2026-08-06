# TRANSMISSION LINE DEMONSTRATION (TLD511)

## Cover Page

| Field | Entry |
|---|---|
| Experiment name | Transmission Line Demonstration (TLD511) |
| Group no. | ______ |
| Day | ______ |
| Date of experiment | ______ |
| Date of submission | ______ |

| Entry number | Student name |
|---|---|
| me2240311 | Aaditya |
| | |
| | |
| | |
| | |

---

## 1. AIM OF EXPERIMENT

To visualise, at low frequency, the behaviour of a transmission line using the Feedback TLD511 Transmission Line Demonstrator, by performing the five demonstrations of the manual:

1. **Propagation** of a pulse and of a sine wave along an ideal, correctly terminated (non-reflecting) line, in both directions, and the idea of **wavelength** through the relation λf = v.
2. **Attenuation and dispersion** — the two principal effects of loss in a line — and their dependence on frequency.
3. **Termination**: to show that there is a particular impedance (the characteristic impedance) which absorbs the incoming signal completely, that reflection occurs when the line is incorrectly terminated, and to observe **superposition** of forward and backward waves and the formation of **standing waves**.
4. **Partial reflection** at a mismatched termination and the standing wave it produces, and to verify the voltage reflection coefficient

   **Γ = (Z_b − Z₀) / (Z_b + Z₀)**

5. **Resonance** of a line whose length is an integral number of half-wavelengths (nλ/2 line), with open-circuit and with short-circuit ends.

---

## 2. EXPERIMENT SETUP AND OBSERVATIONS

### 2.1 Apparatus required

| S. No. | Apparatus | Quantity | Used in |
|---|---|---|---|
| 1 | Transmission Line Demonstrator TLD511 | 1 | All |
| 2 | Sine-wave generator VPG608 (variable phase) | 1 | All |
| 3 | 600 Ω terminator | 2 | Demos 1–4 |
| 4 | 200 Ω terminator | 1 | Demo 4 |
| 5 | 1.8 kΩ terminator | 1 | Demo 4 |
| 6 | 1.2 kΩ terminators | 2 | supplied, not required by the procedure |
| 7 | 10 kΩ resistor | 1 | Demo 5 (Practical 5.1) |
| 8 | 50 Ω terminator | 1 | Demo 5 (Practical 5.2) |
| 9 | Links (connecting / short-circuit) | 2 | All |

### 2.2 Description of the apparatus

The TLD511 is **not** a real transmission line — it is an *artificial line*, a ladder of series inductance and resistance with shunt capacitance, divided into sections. The voltage at each junction is displayed on a vertical bipolar LED bar-graph column (13 columns on the panel), the horizontal centre line of the panel representing zero volts. Deflection above the centre line is a positive voltage, below it a negative voltage, and amplitudes are read in **"units"** = number of lit segments from the centre line.

| Quantity / Control | Value / Function |
|---|---|
| Characteristic impedance Z₀ | 600 Ω |
| Wave velocity v | **4L per second**, fixed by the 0.25 s propagation time over a length L of the line |
| Line length switch | L / 2L / 8L → one-way transit time 0.25 s / 0.5 s / 2 s |
| Distributed attenuation | continuously variable min → max (raises the distributed series loss uniformly) |
| Step input | two-way switch, 'to A' or 'to B' |
| Hold / Run | 'hold' freezes the display for examination or photography |

Connections were made as in figs 4.1, 4.3, 4.5, 4.6, 4.8, 4.10 and 4.12 of the manual: the generator feeds end A through a link, and the terminator is plugged in at end B through the second link.

---

### 2.3 DEMONSTRATION 1 — Propagation in a Transmission Line

**Connect as fig 4.1.** Initial control settings: hold/run → **run**, line length → **8L**, attenuation → **min**, generator output voltage → **zero**, generator frequency → **0.75 Hz**, 600 Ω terminator at **B**.

#### 1.1 Pulse propagation

The 'step input to A' switch was operated **briefly** and released as soon as light appeared in the second column, launching a pulse **two columns wide**.

*Observation:* The pulse travelled steadily from A towards B, keeping its **two-column width and its full height unchanged** at every stage of the journey, and **disappeared at B** without producing any return signal. The time taken to cross the 8L line was about **2 s**, in agreement with v = 4L s⁻¹. Repeated operation of the switch sent a train of separate pulses (a Morse-code-like pattern) down the line, each behaving identically and independently.

> **[PHOTO 1]** Pulse just launched, occupying columns 2–3 near end A
> **[PHOTO 2]** The same pulse midway along the line — shape and height unchanged
> **[PHOTO 3]** Pulse arriving at end B, immediately before it is absorbed
> *Caption: 1.1 Forward pulse propagation on a correctly terminated (600 Ω) line — the shape is preserved and the pulse vanishes at B (cf. fig 4.2).*

#### 1.2 Reverse propagation of pulse

The 'step input to **B**' switch was operated. Here the generator connected at A provides the line termination.

*Observation:* An identical two-column pulse travelled from **B to A** at the same speed and with the same undistorted shape, and disappeared at A. Propagation is therefore **symmetric and reciprocal** — the line behaves identically in either direction.

> **[PHOTO 4]** Reverse pulse shortly after launch, near end B
> **[PHOTO 5]** The same reverse pulse near end A
> *Caption: 1.2 Backward pulse propagation — behaviour identical to the forward case.*

#### 1.3 Propagation of a sine wave

Line length was changed to **2L** and the generator output raised to give **full-height indication in each column**.

*Observation:* A sinusoidal pattern appeared **distributed in distance along the line**, gliding smoothly from A towards B. The envelope was the same at every column — no growth, no decay, no returning wave. Viewing any single column, the bar swung sinusoidally **in time**. The wave therefore behaves as an ideal travelling wave, V(z, t) = V₀ cos(ωt − βz): the *same* phenomenon seen as a distribution in space or as a variation in time, the two being linked by the propagation delay along the line.

> **[PHOTO 6]** Travelling sine wave at full-column amplitude on the matched line
> *Caption: 1.3 Forward travelling sine wave, 600 Ω termination — constant amplitude at every point on the line.*

#### 1.4 Wavelength

The **'hold'** control was operated to freeze the display, released for a second, and operated again at a different part of the input cycle. The frequency was then raised gradually to 2 Hz and 'hold' operated again.

*Observation:*

| Line length | f (Hz) | λ = v/f (v = 4L s⁻¹) | Fraction of λ across the line | What was seen on the display |
|---|---|---|---|---|
| 2L | 0.75 | 4L / 0.75 = **5.33L** | 2L / 5.33L = **0.375 λ** | rather **less than half a wavelength** |
| 2L | 2.0 | 4L / 2 = **2L** | 2L / 2L = **1.00 λ** | exactly **one full wavelength** |

On freezing the display at different instants, a **different part of the sine wave** was displayed each time, **but always the same fraction of a wavelength**. On raising the frequency, the wavelength visibly **shortened** — more of the cycle fitted into the same physical line.

> **[PHOTO 7]** 'Hold' at f = 0.75 Hz — rather less than half a wavelength displayed
> **[PHOTO 8]** 'Hold' operated again at a different part of the cycle — a different portion of the wave, but the same fraction of a wavelength
> **[PHOTO 9]** 'Hold' at f = 2 Hz — one complete wavelength displayed (reduced wavelength)
> *Caption: 1.4 Wavelength on the line, verifying λf = v with v = 4L s⁻¹.*

---

### 2.4 DEMONSTRATION 2 — Attenuation and Dispersion

**Connect as fig 4.3.** Initial control settings: hold/run → run, line length → **2L**, attenuation → **min**, 600 Ω at B. The generator frequency was set by trial to about **1.7 Hz**, chosen so that at maximum attenuation an amplitude of four units at the second column falls to one unit at termination B.

#### 2.1 Attenuation of a sine wave

The generator output was raised to give a travelling sine wave of **full-column amplitude**. With attenuation at 'min', the amplitude was **the same at all points in the line**. The attenuation control was then raised **gradually to 'max'**.

*Observation:* The signal diminished progressively along the direction of travel. Reading the envelope, the amplitude fell from **4 units to 2 units**, and then from **2 units to 1 unit, over the same distance along the line**. Equal *ratios* over equal *distances* is the signature of an **exponential decay**, e^(−αz) — not a linear one.

> **[PHOTO 10]** Attenuation at 'min' — full-column travelling sine wave, equal amplitude at all columns
> **[PHOTO 11]** Attenuation at 'max' — amplitude falling along the line, showing 4 units → 2 units → 1 unit over equal distances
> *Caption: 2.1 Exponential character of attenuation.*

#### 2.2 Attenuation distortion

With the attenuation control left at 'max', the generator frequency was **reduced**, and then raised again.

*Observation:*

| f (Hz) | Amplitude reaching termination B | Remark |
|---|---|---|
| 0.5 | almost full amplitude | attenuation barely perceptible |
| 0.75 | moderately reduced | some attenuation visible |
| 1.7 | ≈ 1 unit (from 4 units at column 2) | reference setting |
| 2.0 | wave dies out by about the 7th–8th column | maximum attenuation observed |

**Attenuation is therefore strongly frequency dependent — it falls as the frequency is reduced.** The line does not treat all frequency components of a signal alike; this is *amplitude–frequency distortion*, and it leads directly to the distortion of a pulse in the next section.

> **[PHOTO 12]** Reduced frequency (≈ 0.5 Hz) at the same attenuation setting — very little decay along the line
> **[PHOTO 13]** Raised frequency (≈ 2 Hz) — strong decay, wave dying out after about 8 columns
> *Caption: 2.2 Attenuation distortion — the attenuation is reduced as the frequency is reduced.*

#### 2.3 Dispersion of a pulse

The generator was **disconnected**, the line length set to **8L**, and the attenuation control set **about mid-way**. The 'step input to A' switch was operated until the second display column lit, producing a travelling pulse. The procedure was repeated with various amounts of attenuation.

*Observation:* Two distinct effects were seen at once:
1. The pulse was **diminished by the attenuation** as it travelled forward.
2. As it travelled, the pulse **developed a tail** — it lost its sharp two-column form and spread over **3–4 columns** by the time it reached B, with the trailing edge drawn out behind it (as in fig 4.4).

With **larger** attenuation the spreading was more pronounced; with the attenuation returned towards 'min' the pulse held its shape almost perfectly, as in Demonstration 1.

> **[PHOTO 14]** Start of pulse — sharp, two columns wide (cf. fig 4.4a)
> **[PHOTO 15]** About 1 s later, midway along the line — reduced in height and beginning to spread (cf. fig 4.4b)
> **[PHOTO 16]** Nearly 2 s from the start, at end B — spread over 3–4 columns with a clear tail (cf. fig 4.4c)
> **[PHOTO 17]** The same pulse with a larger attenuation setting — noticeably more spreading
> *Caption: 2.3 Dispersion — the pulse is both attenuated and broadened, developing a tail as it travels.*

#### 2.4 Backward attenuation

The 600 Ω terminator was **transferred to the A end** of the line and the 'step input to **B**' switch operated.

*Observation:* The signal was **still decreased in the direction of its own travel** (B → A), and it developed the same tail. Attenuation and dispersion are therefore properties of the medium itself and are independent of the direction of propagation.

> **[PHOTO 18]** Backward pulse decreasing and tailing as it travels from B towards A
> *Caption: 2.4 Backward attenuation — loss acts in the direction of travel, whichever way that is.*

---

### 2.5 DEMONSTRATION 3 — Termination, Simple Cases

**Connect as fig 4.5.** Initial control settings: hold/run → run, line length → **8L**, attenuation → **min**, oscillator amplitude → **zero**, oscillator frequency → **1.5 Hz**, 600 Ω terminator at **B**.

#### 3.1 Reflection of a signal at a gross mismatch

The 'step input to A' switch was operated until the second column lit, sending a short pulse along the line, under three successive conditions at B:

| Condition at B | Z_b | Observation |
|---|---|---|
| 600 Ω terminator (correct termination) | 600 Ω | Pulse **absorbed completely** at B; nothing returns |
| Terminator **removed** (open circuit) | ∞ | Pulse **reflected from B back to A**, with the **same polarity** (still above the centre line) |
| **Short-circuit link** across the line at B | 0 | Pulse reflected, but **inverted on reflection at B** — the returning pulse lights the columns **below** the centre line |

> **[PHOTO 19]** 600 Ω at B — pulse approaching the termination, and the line empty afterwards (absorbed, no return)
> **[PHOTO 20]** Terminator removed — reflected pulse travelling back towards A, in phase with the incident pulse
> **[PHOTO 21]** Short-circuit link at B — reflected pulse inverted, below the centre line
> *Caption: 3.1 Reflection at a gross mismatch — matched, open-circuit and short-circuit terminations.*

#### 3.2 Superposition of forward and backward waves

The 600 Ω terminator was **restored at B**. The 'step input to A' switch was operated to send a pulse from A, and then **immediately operated in the reverse direction** to send a pulse from B.

*Observation:* The two two-column pulses travelled towards each other. **Where they met, their voltages were superimposed** — the overlapping column showed a distinctly larger (about doubled) deflection, giving a composite pattern about three columns wide. Immediately afterwards the two pulses **emerged unchanged** and continued to their respective far ends, where both were absorbed. The pulses therefore add where they overlap but do not scatter off one another — direct visual proof of **linear superposition**.

> **[PHOTO 22]** The two pulses approaching each other from opposite ends
> **[PHOTO 23]** The instant of meeting — superimposed voltages, enlarged overlapping column
> **[PHOTO 24]** The two pulses after crossing, each unchanged and continuing on its way
> *Caption: 3.2 Superposition of forward and backward pulses.*

#### 3.3 Superposition of incident and reflected waves

Here the 'step input to A' switch was **kept operated** (a continuous step, not a short pulse).

**(a) Correctly terminated (600 Ω at B):** the step travelled to B and the whole line settled at a **single, uniform amplitude**. Nothing returned — all the energy is absorbed by the correct termination.

**(b) Terminator removed (open circuit, Γ = +1):** the switch was released, the line allowed to come to rest, the terminator removed, and the switch operated again and held until the reflected signal returned to A. The reflected step is **in phase** with the incident one, so behind the returning front the line showed **double the incident amplitude**, while ahead of it only the single-amplitude incident step was present. When the front reached A, the whole line stood at double amplitude.

**(c) Short-circuit link at B (Γ = −1):** the procedure was repeated. The reflected step is now **inverted**, so behind the returning front the incident and reflected steps **cancelled** and the line was left at essentially **zero** — the display appeared to be progressively "erased" from B backwards.

*Discussion point — what happens when the input signal is removed?* Both ends of the line are now grossly mismatched, so the energy stored on the line cannot be absorbed anywhere. The disturbance is therefore **totally reflected back and forth between the two ends**, superposing afresh at each pass, and it dies away only gradually as the line's own (small) attenuation dissipates it.

> **[PHOTO 25]** 600 Ω at B, step held — line at uniform single amplitude, no reflection
> **[PHOTO 26]** Terminator removed — returning front partway along, double amplitude behind it and single amplitude ahead of it
> **[PHOTO 27]** Reflected signal returned to A — whole line at double amplitude
> **[PHOTO 28]** Short-circuit link at B — cancellation behind the returning front, line driven back to zero
> *Caption: 3.3 Superposition of incident and reflected waves for open-circuit and short-circuit terminations.*

#### 3.4 Standing waves

The line length was set to **2L**, the 600 Ω terminator replaced at B, and the sine-wave generator output raised to give a travelling wave of about **half-scale amplitude**. The terminator was then **removed from B**.

*Observation:* The pattern **stopped travelling**. Each column now oscillated up and down **in place**, with a fixed envelope set by its position:
- **Nodes** — columns that never lit — at fixed positions, spaced **λ/2** apart;
- **Antinodes** — columns of maximum swing — midway between them, each **λ/4** from the neighbouring node;
- A **voltage maximum always at termination B**, the open-circuited end.

The frequency was varied over the range **½ Hz to 2 Hz**: the node and antinode spacing changed accordingly (λ = v/f), but there was **always a maximum voltage at B**.

The frequency was returned to **1.5 Hz** and a **short-circuit link plugged in parallel with termination B**. The **nodes and antinodes changed places** — B now carried a permanent node (voltage minimum).

> **[PHOTO 29]** Travelling wave of half-scale amplitude with 600 Ω at B (reference, before removing the terminator)
> **[PHOTO 30]** Standing wave after removing the terminator — nodes and antinodes fixed, maximum at B
> **[PHOTO 31]** Standing wave at a lower frequency (≈ 0.5 Hz) — longer wavelength, still a maximum at B
> **[PHOTO 32]** Standing wave at 2 Hz — shorter wavelength, still a maximum at B
> **[PHOTO 33]** Short-circuit link at B, f = 1.5 Hz — nodes and antinodes interchanged, minimum at B
> *Caption: 3.4 Standing waves with open-circuit and short-circuit terminations.*

---

### 2.6 DEMONSTRATION 4 — Standing Wave and Partial Reflection

#### Practical 4.1 — Reflection of a pulse

**Connect as fig 4.6**: a 600 Ω resistor provides a correct termination at **each** end of the 600 Ω line. Controls: hold/run → run, line length → **8L**, attenuation → **min**. Power switched on and the 'power ON' lamp checked.

The 'step input' switch was operated in the direction 'to A', just long enough to light the second column, and released — sending a pulse of incident amplitude **4 units** from A to B (fig 4.7). The 600 Ω terminator at B was then replaced by **200 Ω** and by **1.8 kΩ** in turn, and for each the **sign and magnitude** of the reflected pulse were observed. A longer pulse, and several pulses in succession, were also tried, and gave the same result.

| Terminator at B | Reflected pulse | Sign | Incident (units) | Reflected (units) | Γ = reflected/incident |
|---|---|---|---|---|---|
| 600 Ω | none — absorbed | — | 4 | 0 | **0** |
| 200 Ω | **inverted**, below the centre line | negative | 4 | 2 | **−1/2** |
| 1.8 kΩ | **erect**, above the centre line | positive | 4 | 2 | **+1/2** |

*Observation:* Both mismatched loads gave a **partial** reflection — the reflected pulse was **half the height** of the incident pulse in each case. The **sign** depended on whether the load was below or above 600 Ω: the low resistance behaved qualitatively like a short circuit (inversion), the high resistance like an open circuit (no inversion).

> **[PHOTO 34]** Incident pulse of 4 units travelling from A (fig 4.7)
> **[PHOTO 35]** 600 Ω at B — pulse absorbed in the correct termination, nothing returns
> **[PHOTO 36]** 200 Ω at B — reflected pulse of 2 units, **inverted** (Γ = −1/2)
> **[PHOTO 37]** 1.8 kΩ at B — reflected pulse of 2 units, **erect** (Γ = +1/2)
> *Caption: Practical 4.1 — partial reflection of a pulse at a mismatched termination.*

#### Practical 4.2 — Standing wave due to a mismatch

**Connect as fig 4.8**: terminators removed, the sine-wave generator (**0° output only**), two links and a **600 Ω** terminator connected. On the TLD511 the line length was set to **L**, with hold/run at 'run' and attenuation at 'min'. On the generator the frequency was set to about **2.5 Hz** and the amplitude adjusted until the travelling wave just lit **two sections up and two down** in each column — an amplitude of **±2 units**.

The 600 Ω terminator was then removed; the **1.8 kΩ** terminator substituted; and finally replaced by **200 Ω**.

| Termination at B | Pattern observed | V_max (units) | V_min (units) | Where the maximum occurs |
|---|---|---|---|---|
| 600 Ω | pure travelling wave, uniform amplitude | 2 | 2 | no pattern |
| removed (open circuit) | **full standing wave**, deep nulls | 4 | ≈ 0 | at termination B |
| 1.8 kΩ | **reduced standing wave** — nulls no longer reach zero | 3 | 1 | at termination B |
| 200 Ω | reduced standing wave of the **same magnitudes**, but shifted by λ/4 | 3 | 1 | a quarter wavelength before B; **minimum at B** |

*Observation:* Substituting the 1.8 kΩ terminator **reduced** the standing wave: the crests reached only 3 units instead of 4, and the troughs fell only to 1 unit instead of zero. These values agree with the reflected pulse of Practical 4.1 — a reflection of half the incident amplitude.

*Similarities and differences between 200 Ω and 1.8 kΩ:* the maximum and minimum **values are identical** (both give |Γ| = 1/2, hence the same depth of standing wave), but their **positions along the line are interchanged** — with 1.8 kΩ there is a maximum at the load, with 200 Ω a minimum at the load, the whole pattern being displaced by a quarter wavelength. This is because the two reflection coefficients have equal magnitude but **opposite sign**.

> **[PHOTO 38]** Travelling wave of ±2 units with the 600 Ω terminator (reference)
> **[PHOTO 39]** 600 Ω removed — full standing wave appears (max 4 units, min ≈ 0)
> **[PHOTO 40]** 1.8 kΩ substituted — reduced standing wave, max 3 units and min 1 unit, **maximum at B**
> **[PHOTO 41]** 200 Ω substituted — same max 3 and min 1, but **minimum at B** (pattern shifted by λ/4)
> *Caption: Practical 4.2 — standing wave due to a mismatched termination.*

---

### 2.7 DEMONSTRATION 5 — Properties of an nλ/2 Line

#### Practical 5.1 — Line open-circuit at both ends

**Connect as fig 4.10**: the generator connected to end A **through a 10 kΩ resistance**, which is high enough compared with the 600 Ω line to approximate an open circuit; end B left open. Oscillator frequency **1 Hz**, output about **8 V peak-to-peak**. TLD511 controls: hold/run → run, line length → **L**, attenuation → **min**.

*Observation:* Under these starting conditions only a **small signal** could be seen near the B end — the 10 kΩ input resistance cuts the generator signal down considerably.

The frequency was then raised in steps of about **0.2 Hz**, with smaller steps and a wait of several seconds per step near 2 Hz. By fine adjustment, the display built up into a **large oscillation with a voltage maximum at both ends of the line** (as in fig 4.11) — the first **resonance**, near **2 Hz**.

The 10 kΩ input resistor was then **disconnected**: the oscillation **died away only gradually**. On replacing the resistor, the oscillation took a little while to **build up again**.

Raising the frequency further, further resonances (maxima of amplitude) were found at approximately **3.8 Hz, 4 Hz, 5.7 Hz, 6 Hz and 7.6 Hz**, with signs of resonance even at 8 Hz — although at that frequency the TLD511 is hardly an adequate representation of a real line.

> **[PHOTO 42]** Off resonance — only a small signal visible near the B end
> **[PHOTO 43]** First resonance near 2 Hz — large oscillation with voltage maxima at **both** ends (cf. fig 4.11)
> **[PHOTO 44]** Resonance near 4 Hz
> **[PHOTO 45]** Resonance near 6 Hz
> **[SKETCH 1]** Outline of the wave pattern at each resonant frequency (one sketch per frequency, as required by the manual)
> *Caption: Practical 5.1 — resonances of a line open-circuited at both ends.*

#### Practical 5.2 — Line with short-circuit ends

**Connect as fig 4.12**: a low resistance in parallel with both the line and the oscillator — the **50 Ω** resistor at A and a **link** at B — so that both ends approximate short circuits. Several resonant frequencies were again searched for, and the wave shape sketched for each.

*Observation:* Resonances were found at essentially the **same set of frequencies** as before, but the pattern was **displaced by a quarter wavelength**: there is now a **voltage minimum at each end** of the line, with the nearest maximum a quarter wavelength inside.

> **[PHOTO 46]** Resonance with short-circuit ends — voltage minima at both ends, maxima a quarter wavelength in
> **[PHOTO 47]** A second resonant frequency with short-circuit ends
> **[SKETCH 2]** Outline of the voltage wave at each resonant frequency for the short-circuited case
> *Caption: Practical 5.2 — resonances of a line short-circuited at both ends.*

---

## 3. INFERENCE, THEORETICAL EXPLANATION AND CALCULATIONS

### 3.1 Governing theory

For a line of per-unit-length series resistance R, series inductance L, shunt conductance G and shunt capacitance C, the telegrapher's equations give d²V/dz² = γ²V with

  **γ = α + jβ = √[(R + jωL)(G + jωC)]**   and   **Z₀ = √[(R + jωL)/(G + jωC)]**

The general solution is the sum of a forward and a backward wave:

  **V(z) = V⁺e^(−γz) + V⁻e^(+γz)**

where α is the **attenuation constant** (amplitude falls as e^(−αz)), β the **phase constant**, and

  **v_p = ω/β**,  **λ = 2π/β**,  hence **λf = v_p**

For the TLD511: **Z₀ = 600 Ω** and **v = 4L s⁻¹** (0.25 s per length L). For a lossless line Z₀ = √(L/C) and v = 1/√(LC).

### 3.2 Demonstration 1 — why the shape is preserved, and the wavelength calculation

With **Z_b = Z₀** the line is correctly terminated: the load absorbs exactly the power the wave delivers, so V⁻ = 0 and only the forward wave exists. With attenuation at 'min', R ≈ 0 and G ≈ 0, so

  γ ≈ jω√(LC)  ⇒  **α ≈ 0**, **β = ω√(LC)**, **v_p = 1/√(LC) — independent of ω**

Every frequency component of the pulse therefore travels at the **same speed with no loss**, which is precisely why the two-column pulse arrived at B with its shape and height intact. This is the ideal, distortionless line. The same reasoning explains why the sine wave in 1.3 kept a constant envelope along the whole line, and why the phase change along the line is simply the propagation delay expressed in radians, **φ = βz = ωz/v**.

**Wavelength calculation** (v = 4L s⁻¹, line length 2L):

- f = 0.75 Hz ⇒ λ = v/f = 4L/0.75 = **5.33L**; the 2L line spans 2L/5.33L = **0.375 λ** → "rather less than half a wavelength" ✔
- f = 2.00 Hz ⇒ λ = 4L/2 = **2L**; the 2L line spans 2L/2L = **1.00 λ** → "one wavelength is now displayed" ✔

Both observations agree with λf = v. Freezing the display at different instants changes only the **phase** (which part of the cycle is caught), never the **spatial period**, which is why the same fraction of a wavelength was always shown.

### 3.3 Demonstration 2 — attenuation and dispersion

**Exponential attenuation.** The amplitude varies as e^(−αz), so over equal successive distances Δz it falls by the **same factor** e^(−αΔz). The observed sequence **4 → 2 → 1 units over equal distances** is exactly this constant ratio of ½, which establishes the exponential character. From it:

  e^(−αΔz) = ½  ⇒  **α = (ln 2)/Δz = 0.693/Δz** per unit length

**Why attenuation falls as the frequency is reduced.** Advancing the attenuation control raises the distributed series resistance R until it is comparable with, or larger than, ωL at these very low frequencies. The line then leaves the low-loss regime and approaches the **RC-dominated limit** (ωL ≪ R, G ≈ 0):

  γ ≈ √(jωRC) = √(ωRC/2)·(1 + j)  ⇒  **α = β = √(ωRC/2)**

so **α ∝ √ω** — halving the frequency reduces the attenuation constant by a factor √2. This is exactly the trend observed (barely any decay at 0.5 Hz, the wave dying out by the 8th column at 2 Hz). In a **real** line the same √f behaviour arises because the conductor resistance itself grows as R ∝ √f through the **skin effect**, while dielectric loss adds a conductance G ∝ f. The causes of attenuation are therefore **resistance and skin effect, together with conductance and dielectric loss**.

**Why the pulse develops a tail.** In the same regime the phase velocity is

  **v_p = ω/β = √(2ω/RC) ∝ √ω**

i.e. **frequency dependent** — the defining condition for dispersion. A pulse is a superposition of many frequencies; once they no longer share a common speed they progressively get out of step, and the pulse can no longer hold together. The higher-frequency components (which build the sharp edges) run ahead while the low-frequency components lag, so the pulse arrives **lower, broader and drawn out into a trailing tail** — exactly the shape of fig 4.4c. Increasing the attenuation increases R, strengthens the √ω dependence, and produces more spreading, as observed.

**Attenuation and dispersion are distinct effects:**

| | Attenuation | Dispersion |
|---|---|---|
| Origin | non-zero α — resistive and dielectric loss | β non-linear in ω, i.e. v_p depends on ω |
| Effect | loss of **amplitude** | change of **shape** — broadening, tailing |
| Acts on a single-frequency signal? | **Yes** | **No** — needs several frequency components |
| Seen in this experiment as | wave dying down along the line (2.1, 2.2) | 2-column pulse spreading to 3–4 columns (2.3) |

A line is **distortionless** when R/L = G/C, for then α = √(RG) is constant and β = ω√(LC) is exactly linear, so neither amplitude nor shape distortion occurs. The TLD does not satisfy this once the attenuation control is advanced, which is why the two effects appeared together.

### 3.4 Demonstrations 3 and 4 — the reflection coefficient

At the load, V(0) = V⁺ + V⁻ and I(0) = (V⁺ − V⁻)/Z₀ must satisfy V(0)/I(0) = Z_b. Solving gives

  **Γ = V⁻/V⁺ = (Z_b − Z₀)/(Z_b + Z₀)**,  with **Z₀ = 600 Ω**

**Calculations and comparison with observation** (incident pulse = 4 units):

| Termination | Z_b (Ω) | Γ calculated | Reflected expected | Reflected observed | Γ experimental |
|---|---|---|---|---|---|
| Correct termination | 600 | (600 − 600)/(600 + 600) = **0** | 0 units | absorbed, 0 units | 0 |
| Short circuit | 0 | (0 − 600)/(0 + 600) = **−1** | −4 units | −4 units, inverted | −1 |
| Open circuit | ∞ | (∞ − 600)/(∞ + 600) = **+1** | +4 units | +4 units, erect | +1 |
| Low mismatch | 200 | (200 − 600)/(200 + 600) = −400/800 = **−1/2** | −2 units | −2 units, inverted | **−1/2** |
| High mismatch | 1800 | (1800 − 600)/(1800 + 600) = 1200/2400 = **+1/2** | +2 units | +2 units, erect | **+1/2** |

The experimental values, obtained simply as (reflected signal)/(incident signal) including sign, **agree with the calculated values** to within the reading resolution of the display (± ½ unit, i.e. about ±0.12 in Γ). The reflection coefficient formula is therefore **verified in both magnitude and sign**.

Physically:
- **Z_b = Z₀** absorbs all the incident power — the load is indistinguishable from an infinite continuation of the line, so nothing returns.
- **Z_b < Z₀** (including a short circuit) holds the load voltage down below what the incident wave would establish, so the reflected wave must be **inverted**.
- **Z_b > Z₀** (including an open circuit) cannot pass all the arriving current, so the load voltage is driven **up**, and the reflected wave is **in phase**; for a true open circuit the load voltage doubles.

### 3.5 Superposition, standing waves and VSWR

Superposition follows from the **linearity** of the telegrapher's equations: two solutions may simply be added. Counter-propagating pulses therefore add where they overlap and separate again unchanged (3.2). With a reflection present the magnitude along the line is

  **|V(l)| = |V⁺|·|1 + Γe^(−2jβl)|**  (l measured back from the load)

  ⇒ **V_max = |V⁺|(1 + |Γ|)**, **V_min = |V⁺|(1 − |Γ|)**, **VSWR = V_max/V_min = (1 + |Γ|)/(1 − |Γ|)**

Adjacent maxima (or minima) are **λ/2** apart; a maximum and the next minimum are **λ/4** apart.

**Calculation for Practical 4.2** (incident amplitude |V⁺| = 2 units):

| Termination | Z_b (Ω) | Γ | V_max = 2(1+|Γ|) | V_min = 2(1−|Γ|) | VSWR calculated | Observed max, min | VSWR observed |
|---|---|---|---|---|---|---|---|
| Correct | 600 | 0 | 2 | 2 | 1 | 2, 2 | 1 |
| Open circuit | ∞ | +1 | 4 | 0 | ∞ | 4, ≈0 | very large |
| High mismatch | 1800 | +1/2 | **3** | **1** | **3** | 3, 1 | 3 |
| Low mismatch | 200 | −1/2 | **3** | **1** | **3** | 3, 1 | 3 |

This is exactly why the standing wave was "reduced" when the 1.8 kΩ terminator was substituted: only half the wave is returned, so the crests add to 3 units instead of 4 and the troughs cancel only down to 1 unit instead of zero.

**Positions of maxima and minima.** At the load the incident and reflected waves are **in phase if Γ > 0** and **out of phase if Γ < 0**. Hence:

- Open circuit, or any Z_b > Z₀ (Γ > 0) ⇒ **voltage maximum (antinode) at the load**;
- Short circuit, or any Z_b < Z₀ (Γ < 0) ⇒ **voltage minimum (node) at the load**.

Since 200 Ω and 1.8 kΩ give reflection coefficients of equal magnitude but opposite sign, their standing-wave patterns have **identical maxima and minima but interchanged positions**, shifted by λ/4 — precisely as observed. The same argument explains why plugging the short-circuit link in at B in Demonstration 3.4 made every node and antinode change places.

Equivalently, from the input impedance

  **Z_in(l) = Z₀ (Z_b + jZ₀ tan βl)/(Z₀ + jZ_b tan βl)**

which repeats every **λ/2** and **inverts the normalised impedance every λ/4** — a quarter-wave section turns an open circuit into a short circuit and vice versa, so open- and short-circuit conditions (and hence antinodes and nodes) alternate every quarter wavelength along the line.

### 3.6 Demonstration 5 — resonance of an nλ/2 line

When both ends are terminated so that they absorb **no** energy (both open, or both short), a signal is totally reflected at each end and is trapped on the line. Because there is a finite time of travel between the ends, a large steady oscillation can only build up when the round trip returns the wave **in phase with itself**, i.e. when

  **line length = n λ/2**,  n = 1, 2, 3, …  ⇒  **f_n = n v / (2 × line length)**

For the TLD511 with the line length switch at **L** and v = 4L s⁻¹:

  **f_n = n × 4L / (2 × L) = 2n Hz  ⇒  2, 4, 6, 8 Hz**

*Inference:* The observed resonances — the first near **2 Hz**, then close to **4 Hz**, **6 Hz** and signs of one near **8 Hz** — reproduce this harmonic series, so the resonant frequencies are **all multiples of a fundamental**. The additional peaks observed slightly below the ideal values (3.8, 5.7, 7.6 Hz) and the deterioration of the pattern above about 6 Hz arise because the TLD511 is a **finite ladder of lumped sections rather than a truly distributed line**: as the frequency rises towards the ladder's cut-off, the network's phase velocity falls below 4L s⁻¹, so the higher resonances drift below the ideal harmonics. This is exactly the limitation the manual warns of at 8 Hz.

The boundary conditions fix the shape of each pattern:
- **Open-circuit ends:** the current must vanish at each end ⇒ a **voltage maximum at both ends**.
- **Short-circuit ends:** the voltage must vanish at each end ⇒ a **voltage minimum at both ends**, with the nearest maximum a quarter wavelength inside.

Both give the *same* condition, length = nλ/2, and therefore the same resonant frequencies — only the pattern is displaced by λ/4, which is what was observed on going from Practical 5.1 to 5.2.

The slow decay of the oscillation after disconnecting the 10 kΩ resistor, and the time it took to build up again on reconnection, show that once both ends are grossly mismatched there is **no path for energy to leave the line except its own attenuation**: the network is behaving as a **high-Q resonator**, and energy must be fed in over many cycles to reach the steady state.

### 3.7 A circuit-level view of why the load changes the pattern

Beyond the Γ formula, the behaviour follows from the actual ladder network inside the TLD511. The arriving wave carries a fixed ratio of voltage to current set by Z₀ = 600 Ω, and therefore delivers a definite energy per unit time into the last section.

- **R_b = 600 Ω:** the load draws exactly the current the wave supplies at that voltage. All the incoming energy is dissipated in the load, nothing is left over, and no wave is launched back — the load is electrically indistinguishable from more line.
- **R_b < 600 Ω:** the load takes more current than the wave supplies, pulling the last node's voltage below the incident value. The final shunt capacitance cannot charge fully, the energy stored in the last series inductance has nowhere to go, and it is returned as a wave of **negative** voltage relative to the incident one — an inverted reflection.
- **R_b > 600 Ω:** the load cannot carry away all the arriving current. The surplus charge piles onto the final shunt capacitance, raising the node voltage **above** the incident value, and the excess is launched back **in phase**.

The returning wave then interferes with the incident one all the way along the line, and it is this interference that the display actually shows — a pure travelling wave, a partial standing wave, or a full standing wave, according to how much energy the load sends back.

### 3.8 Sources of error and limitations

1. **Quantised display** — amplitudes are read as whole LED segments, giving an uncertainty of about ±½ unit and hence about ±0.12 in the experimental Γ.
2. **Lumped approximation** — the TLD is a finite ladder, not a continuous line, and has its own cut-off frequency; above roughly 6 Hz the phase velocity departs from 4L s⁻¹, which shifts the higher resonances of Demonstration 5.
3. **Terminator tolerance and contact resistance** shift the effective Z_b slightly from its nominal value.
4. **Human timing** on the step-input switch — holding it a little too long or too briefly alters the pulse width from the intended two columns, changing the apparent amplitude.
5. **Residual attenuation at 'min'** means the "ideal" line is not perfectly lossless, so open- and short-circuit reflections were very slightly below full amplitude.
6. The display changes continuously; the **'hold'** control was used wherever an exact pattern had to be read or photographed.

---

## 4. CONCLUSION

Using the TLD511 Transmission Line Demonstrator, transmission-line behaviour that is normally invisible at radio frequencies was slowed down to a directly observable scale, and all five demonstrations of the manual were completed successfully. The following were established:

1. On a **correctly terminated (600 Ω) line at minimum attenuation**, both pulses and sine waves propagate with **no change of shape or amplitude** and are **absorbed completely** at the termination, in either direction. Propagation is symmetric and the line behaves as an ideal, distortionless medium.
2. The relation **λf = v** was verified with **v = 4L s⁻¹**: on a 2L line, 0.75 Hz gave λ = 5.33L (0.375 of a wavelength displayed, "rather less than half") and 2 Hz gave λ = 2L (exactly one wavelength displayed). Freezing the display at different instants always showed the **same fraction of a wavelength**.
3. **Attenuation is exponential in distance** — the amplitude fell 4 → 2 → 1 units over equal successive distances — and it **increases with frequency** (α ∝ √ω in the loss-dominated regime, corresponding to skin effect and dielectric loss in a real line).
4. **Dispersion** was observed as the broadening of a two-column pulse into a 3–4 column pulse with a trailing tail over an 8L line, and is a **distinct** phenomenon from attenuation: it arises from the frequency dependence of the phase velocity and therefore affects only signals containing more than one frequency component.
5. The **voltage reflection coefficient Γ = (Z_b − Z₀)/(Z_b + Z₀)** was verified in **magnitude and sign** for Z_b = 600 Ω (Γ = 0), short circuit (Γ = −1), open circuit (Γ = +1), 200 Ω (Γ = −1/2) and 1.8 kΩ (Γ = +1/2); the measured ratios of reflected to incident amplitude matched the calculated values within the reading resolution of the display.
6. **Superposition** was demonstrated directly: counter-propagating pulses add where they overlap and emerge unchanged, while incident and reflected steps give **double amplitude** for an open circuit and **cancellation** for a short circuit.
7. **Standing waves** form when a reflected wave is present. With a mismatched load a **partial** standing wave results: for an incident amplitude of ±2 units and |Γ| = 1/2, V_max = 3 units and V_min = 1 unit, giving **VSWR = 3**, in agreement with (1 + |Γ|)/(1 − |Γ|). An open circuit (Γ > 0) places an antinode at the load and a short circuit (Γ < 0) a node, the two patterns differing by a shift of **λ/4**.
8. **Resonance** occurs when the line length is an integral number of half-wavelengths, giving **f_n = nv/2L = 2n Hz** for the L setting — all multiples of a fundamental. Open-circuit ends give voltage maxima at the ends, short-circuit ends voltage minima, with the same resonant frequencies. The small downward drift of the higher resonances confirms that the TLD511 is a lumped-element approximation to a real line.

The experiment therefore provided a complete visual verification of the basic theory of propagation, loss, distortion, reflection, superposition, standing waves and resonance on transmission lines.

---

## 5. PRECAUTIONS

1. Keep the **attenuation control at 'min'** for the propagation, termination and reflection demonstrations. If it is left advanced, the loss along the line masks the effect being studied and a reflected pulse appears smaller than it really is, corrupting the measured Γ.
2. Operate the **'step input' switch only briefly** — release it as soon as light appears in the **second column** — so that the pulse is exactly two columns wide. Holding it longer produces a step rather than a pulse and changes the observation entirely (this is deliberate only in section 3.3).
3. Keep the **generator output at zero before switching on**, and raise it slowly. If the columns saturate at full height the display is clipped and all amplitude readings — and hence Γ and VSWR — become meaningless.
4. Check the **value of the terminator and that it is firmly plugged in** before recording an observation; a loose terminator behaves as an open circuit and gives a spurious reflection. Always confirm the matched case first — with 600 Ω the pulse must vanish at B with no return.
5. The line takes up to **2 s to traverse the 8L setting**. Wait for the previous disturbance to die away completely before launching the next pulse, otherwise old and new waves superpose and confuse the reading.
6. Use the **'hold' control** before reading an amplitude or taking a photograph; photographing a moving display gives blurred or mid-transition columns.
7. Do **not change the line-length switch while a wave is on the line**.
8. Read all amplitudes **in units measured from the centre zero line**, and compare the reflected pulse with the incident pulse **at the same column**, so that line attenuation does not bias the ratio.
9. When hunting for **resonances** (Demonstration 5), change the frequency in small steps of about **0.2 Hz** and **wait several seconds after each adjustment** before judging — the line takes time to build up to its steady amplitude and a resonance is easily missed if the frequency is swept quickly.
10. Handle terminators and links by their bodies, keep stray leads clear of the panel so that adjacent terminals are not accidentally shorted, and switch off the power before rearranging connections.

---

## APPENDIX A — Answers to the questions in the manual

**Q4.1 What is the value of the reflection coefficient, from your observation of the reflected pulse?**
The reflection coefficient is (reflected signal)/(incident signal), read directly off the display including sign. With an incident pulse of 4 units, the reflected pulse was 2 units **inverted** for the 200 Ω terminator and 2 units **erect** for the 1.8 kΩ terminator, giving **Γ = −1/2 and Γ = +1/2** respectively.

**Q4.2 Does that value agree with the calculated value (Z_b − Z₀)/(Z_b + Z₀)?**
Yes.
Γ = (200 − 600)/(200 + 600) = −400/800 = **−1/2**
Γ = (1800 − 600)/(1800 + 600) = 1200/2400 = **+1/2**
Both agree with the observed values, within the ±½ unit reading resolution of the display. Using a longer pulse, or several pulses in succession, gave the same result.

**Q4.3 How do you explain the maximum amplitude in terms of the reflection coefficient found previously?**
At a maximum the incident and reflected waves add in phase, so V_max = |V⁺|(1 + |Γ|); at a minimum they oppose, so V_min = |V⁺|(1 − |Γ|). With an incident amplitude of ±2 units and |Γ| = 1/2:
 V_max = 2(1 + 0.5) = **3 units**, V_min = 2(1 − 0.5) = **1 unit**, VSWR = 3.
These are exactly the values observed with both the 1.8 kΩ and the 200 Ω terminators, and they follow directly from the half-amplitude reflected pulse measured in Practical 4.1.

**Q5.1 All your sketches should show a common feature concerning the positions of voltage maxima. What is it?**
For a line resonating with **open-circuit ends there is a voltage maximum at both ends** of the line, at every resonant frequency.

**Q5.2 For each resonant frequency, note the number of wavelengths in the line. What common statement applies to every case?**
In every case the line length contains an **integral number of half-wavelengths**, i.e. line length = **nλ/2** with n = 1, 2, 3, …, which is exactly the condition that places a voltage maximum at each end.

**Q5.3 What general statement can you make about the shape of the voltage wave with short-circuit ends?**
For a line resonating with **short-circuit ends there is a voltage minimum at the ends**, and the nearest maximum is a **quarter wavelength** away. The line length is again an integral number of half-wavelengths.

**Q5.4 What general statement can you make about the resonant frequencies in this case?**
Resonance requires **L = nλ/2**, where L is the line length, λ the wavelength and n an integer. Since f = v/λ, the resonant frequencies are

  **f_n = n v / 2L**

i.e. they are **all multiples of a fundamental frequency**. For the TLD511 with the line length switch at L and v = 4L s⁻¹, f_n = 2n Hz.

---

## APPENDIX B — Photo placement index

Photographs are numbered in the order the manual is performed, so they should match your camera roll in sequence. Paste each one at the marked point in Section 2.

| Photo | Taken during (manual step) | What it should show | Goes in section | Priority |
|---|---|---|---|---|
| 1 | 1.1 Pulse propagation | 2-column pulse just launched near A | 2.3 / 1.1 | Essential |
| 2 | 1.1 | Same pulse midway, shape unchanged | 2.3 / 1.1 | Essential |
| 3 | 1.1 | Pulse arriving at B before absorption | 2.3 / 1.1 | Essential |
| 4 | 1.2 Reverse propagation | Pulse near B, travelling B→A | 2.3 / 1.2 | Essential |
| 5 | 1.2 | Same reverse pulse near A | 2.3 / 1.2 | Optional |
| 6 | 1.3 Sine wave (2L) | Full-column travelling sine wave | 2.3 / 1.3 | Essential |
| 7 | 1.4 Wavelength, hold at 0.75 Hz | Less than half a wavelength shown | 2.3 / 1.4 | Essential |
| 8 | 1.4, hold at a different phase | Different part of the cycle, same fraction of λ | 2.3 / 1.4 | Optional |
| 9 | 1.4, hold at 2 Hz | One full wavelength shown | 2.3 / 1.4 | Essential |
| 10 | 2.1 Attenuation, atten. 'min' | Equal amplitude at all columns | 2.4 / 2.1 | Essential |
| 11 | 2.1, atten. 'max' | Decay along line, 4 → 2 → 1 units | 2.4 / 2.1 | Essential |
| 12 | 2.2 Attenuation distortion, low f | Reduced attenuation at ≈0.5 Hz | 2.4 / 2.2 | Essential |
| 13 | 2.2, high f | Strong attenuation at ≈2 Hz, wave dies out | 2.4 / 2.2 | Essential |
| 14 | 2.3 Dispersion (8L, mid attenuation) | Start of pulse, sharp, 2 columns | 2.4 / 2.3 | Essential |
| 15 | 2.3, ≈1 s later | Pulse midway, reduced and spreading | 2.4 / 2.3 | Essential |
| 16 | 2.3, ≈2 s | Pulse at B, spread over 3–4 columns with a tail | 2.4 / 2.3 | Essential |
| 17 | 2.3, repeat with more attenuation | More pronounced spreading | 2.4 / 2.3 | Optional |
| 18 | 2.4 Backward attenuation | Pulse B→A decaying in direction of travel | 2.4 / 2.4 | Essential |
| 19 | 3.1, 600 Ω at B | Pulse absorbed at B, nothing returns | 2.5 / 3.1 | Essential |
| 20 | 3.1, terminator removed | Reflected pulse travelling back, same polarity | 2.5 / 3.1 | Essential |
| 21 | 3.1, short-circuit link at B | Reflected pulse inverted, below centre line | 2.5 / 3.1 | Essential |
| 22 | 3.2 Superposition F & B | Two pulses approaching each other | 2.5 / 3.2 | Essential |
| 23 | 3.2 | Instant of meeting — enlarged overlap column | 2.5 / 3.2 | Essential |
| 24 | 3.2 | Pulses after crossing, each unchanged | 2.5 / 3.2 | Optional |
| 25 | 3.3, 600 Ω, step held | Line at uniform single amplitude | 2.5 / 3.3 | Optional |
| 26 | 3.3, open circuit | Returning front — double amplitude behind, single ahead | 2.5 / 3.3 | Essential |
| 27 | 3.3, open circuit | Whole line at double amplitude | 2.5 / 3.3 | Essential |
| 28 | 3.3, short-circuit link | Cancellation behind the returning front | 2.5 / 3.3 | Essential |
| 29 | 3.4, 600 Ω at B (2L) | Travelling wave, half-scale amplitude | 2.5 / 3.4 | Optional |
| 30 | 3.4, terminator removed | Standing wave, maximum at B | 2.5 / 3.4 | Essential |
| 31 | 3.4, f ≈ 0.5 Hz | Longer wavelength, still a maximum at B | 2.5 / 3.4 | Essential |
| 32 | 3.4, f = 2 Hz | Shorter wavelength, still a maximum at B | 2.5 / 3.4 | Essential |
| 33 | 3.4, short-circuit link, 1.5 Hz | Nodes and antinodes interchanged, minimum at B | 2.5 / 3.4 | Essential |
| 34 | Practical 4.1 | Incident 4-unit pulse travelling from A | 2.6 / 4.1 | Essential |
| 35 | Practical 4.1, 600 Ω | Pulse absorbed, no reflection | 2.6 / 4.1 | Optional |
| 36 | Practical 4.1, 200 Ω | Reflected pulse 2 units, inverted | 2.6 / 4.1 | Essential |
| 37 | Practical 4.1, 1.8 kΩ | Reflected pulse 2 units, erect | 2.6 / 4.1 | Essential |
| 38 | Practical 4.2, 600 Ω (line L) | Travelling wave of ±2 units | 2.6 / 4.2 | Essential |
| 39 | Practical 4.2, terminator removed | Full standing wave, max 4 / min ≈0 | 2.6 / 4.2 | Essential |
| 40 | Practical 4.2, 1.8 kΩ | Reduced standing wave, max 3 / min 1, max at B | 2.6 / 4.2 | Essential |
| 41 | Practical 4.2, 200 Ω | Max 3 / min 1, minimum at B | 2.6 / 4.2 | Essential |
| 42 | Practical 5.1, off resonance | Small signal only near B | 2.7 / 5.1 | Optional |
| 43 | Practical 5.1, ≈2 Hz | First resonance, maxima at both ends | 2.7 / 5.1 | Essential |
| 44 | Practical 5.1, ≈4 Hz | Second resonance | 2.7 / 5.1 | Essential |
| 45 | Practical 5.1, ≈6 Hz | Third resonance | 2.7 / 5.1 | Optional |
| 46 | Practical 5.2, 50 Ω + link | Resonance with minima at both ends | 2.7 / 5.2 | Essential |
| 47 | Practical 5.2, another f | A second resonant frequency, shorted ends | 2.7 / 5.2 | Optional |

**Sketches (required by the manual, not photographs):**

| Sketch | Where it comes from | What to draw |
|---|---|---|
| Sketch 1 | Practical 5.1 | Outline of the wave pattern at **each** resonant frequency found with open-circuit ends (label each with its frequency); mark the voltage maxima at both ends |
| Sketch 2 | Practical 5.2 | Outline of the voltage wave at each resonant frequency with short-circuit ends; mark the minima at both ends and the maximum a quarter wavelength in |

*If a photograph is missing for an "Essential" row, describe the observation in words at that point and note "photograph not available"; do not leave a blank space in the report.*
