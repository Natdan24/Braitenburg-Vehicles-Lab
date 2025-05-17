# Braitenburg Vehicles Lab

A demonstration of the first four Braitenburg-style vehicles, **all implemented in Unreal Engine** as part of our Master’s in AI lab course. Each “vehicle” shows how simple sensor-motor couplings give rise to distinct emergent behaviors in a real-time 3D simulation.

---

## Vehicle 1 – “Alive”

- **Configuration:** 1 sensor → 1 motor (direct/excitatory)  
- **Behavior:** Speeds up in high-stimulus areas, slows in low-stimulus zones, appearing to “come alive.”

---

## Vehicle 2 – “Fear” and “Aggression”

- **Configuration:** 2 sensors (L/R) → 2 motors (direct/excitatory)  
- **Variants:**  
  - **Fear (2a):** Ipsilateral wiring causes the vehicle to turn *away* from the light.  
  - **Aggression (2b):** Contralateral wiring causes the vehicle to turn *toward* the light.

---

## Vehicle 3 – “Love” and “Explorer”

- **Configuration:** 2 sensors → 2 motors (inhibitory)  
- **Variants:**  
  - **Love (3a):** Contralateral inhibition → slows opposite wheel and gently settles next to the source.  
  - **Explorer (3b):** Ipsilateral inhibition → turns away and orbits in search of optimal stimulus.

---

## Vehicle 4 – “Values & Special Tastes”

- **Configuration:** 2 sensors → 2 motors (non-linear mapping)  
- **Behavior:** Prefers a “just right” stimulus level, orbiting at a set distance or tracing complex paths.

---

### Key Insight

> With just a handful of sensors and simple wiring rules—excitatory vs. inhibitory, crossed vs. uncrossed, linear vs. non-linear—you can recreate a surprising array of lifelike behaviors that look “intelligent.”

---

## Usage

1. Clone this repo  
2. Open the Unreal Engine project in `/UE_Project/`  
3. Press **Play** to watch each vehicle navigate toward or away from the light beacon in our custom scene

---

## Demo

Below is a snapshot from our Unreal Engine demonstration, showing the “Fear” variant veering away from the light source (white orb):

![Braitenburg Vehicle in Unreal Engine](AutoScreenshot.png)

*Figure: Vehicle “Fear” variant in UE4, avoiding the light beacon.*

---

## License

[MIT © Natasha Shereen Benita]
