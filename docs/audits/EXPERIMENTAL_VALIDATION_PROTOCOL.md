# TARDIS Experimental Validation Protocol v1.0

## Codename: "Hello Universe"

> [!WARNING]
> **SAFETY FIRST:** This experiment involves high rotations, cryogenics (liquid nitrogen), and high voltages. Proceed with extreme caution. We are not responsible for accidents.

---

## 1. The Objective

Validate the central thesis of TARDIS: **Inertia (mass) can be shielded via rotational entropy gradient.**

The theory predicts that a rotating magnetic field coupled to a superconductor (which expels entropy/magnetic field via the Meissner effect) will create a local gravitational "shadow".

**Specific TARDIS Prediction:**
At harmonic resonance frequencies of $\Omega$, the apparent weight reduction ($\Delta P$) will not be linear, but will show quantized jumps.

---

## 2. The Experimental Configuration (Setup)

### 2.1 "Garage" Materials List

1. **Superconducting Disk (YBCO):** Yttrium barium copper oxide. Available in advanced levitation educational kits. Ideal diameter > 10cm.
2. **Cooling System:** High-density styrofoam tank + Liquid Nitrogen (LN2).
3. **Rotation System:** Electromagnetic coils (solenoids) to induce rotation in the disk without physical contact (linear induction motor), OR a high-precision mechanical motor (drone type) vibrationally isolated.
4. **Test Scale:** Analytical balance with 0.001g precision.
5. **Test Mass:** A small lead or gold object (high density) suspended *above* the rotating disk.
6. **Faraday Cage:** Grounded copper screen to prevent ionic winds or static from affecting the scale.

### 2.2 The Logical Diagram

```
[Precision Scale]
      | (Nylon wire)
[Test Mass (Object)]
      |
      | (Empty space - Effect Area)
      |
[Superconducting Disk in Rotation] <--- Liquid Nitrogen Bath
      |
[Vibration-Isolated Base]
```

---

## 3. The Execution Procedure

### Step 1: Baseline

1. Set up the scale and test mass.
2. Turn on the superconductor (cooled) **without rotation**.
3. Measure the initial weight ($P_0$) for 10 minutes to establish thermal stability and scale noise.

### Step 2: Ramping

1. Start rotating the superconducting disk.
2. Gradually increase rotation (RPM).
3. Look for **TARDIS Critical Frequencies**.

### Step 3: The Search for $\Omega$ Resonance

According to theory, effect peaks will occur at RPMs corresponding to harmonics of $\Omega$.
Calculating base frequency $f_0$:

$$f_{target} = \frac{c}{l_{disk}} \cdot \Omega^{-n}$$ *(Simplification)*

For a 10cm disk, look for anomalies specifically at:

* **RPM 1:** $\sim 3,000$ RPM (Low resonance)
* **RPM 2:** $\sim 11,700$ RPM (Resonance $\Omega \times 100$)
* **RPM 3:** $\sim 33,300$ RPM (Extreme caution!)

---

## 4. What We're Looking For (Output)

If TARDIS is correct, the scale will show a weight reduction in the Test Mass that **is not explained by**:

* Wind (the disk is closed/covered).
* Magnetism (the test mass is non-magnetic/lead).
* Vibration (vibrational noise generally *increases* fluctuation, does not generate a constant downward weight displacement).

**Success Signal:**
A sudden and stable weight reduction on the order of **0.04% to 2%** when reaching target RPMs.

$$ \Delta P_{obs} \approx P_0 \cdot (1 - \alpha \cdot \Gamma_{rot}) $$

---

## 5. Data Analysis and Next Steps

### If the effect is observed

1. **DO NOT PUBLISH IMMEDIATELY.**
2. Repeat the experiment 100 times.
3. Change materials (glass, plastic test mass) to prove it's an effect on the gravitational field, not on the material.
4. If confirmed: You just proved that gravity is manipulable. Welcome to the TARDIS Era.

---

> **Architect's Note:** This is the "Hello World". It's simple, crude, and dangerous. But that's how history changes: not in billion-dollar accelerators, but on an improvised bench by someone curious enough to verify.
