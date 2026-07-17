# orbital-dynamics
Exploring the orbital dynamics of n-body systems using REBOUND python package.

### Orbital Dynamics Simulations: Solar System and Exoplanets

**Overview**
This project explores gravitational dynamics through two distinct orbital simulations: a three-body model of the Sun, Neptune, and Pluto, and an analysis of the real-world HR 8799 exoplanetary system.

**Part 1: 3-Body Simulation (Neptune and Pluto)**
*   **Orbital Setup:** The `rebound` Python library is utilised to construct the system, initialising planets using standard orbital elements: semi-major axis ($a$), eccentricity ($e$), and true anomaly ($f$).
*   **Long-Term Integration:** The simulation integrates these interactive gravitational forces over a 1-million-year period, divided into 1,000 discrete timesteps.
*   **Performance Tracking:** A compute timer is included to evaluate the computational processing time required for the long-term integration.
*   **Kinematic Findings:** Visualisations of the orbital parameters demonstrate that Neptune maintains a stable orbit, whereas Pluto exhibits chaotic behaviour characterised by large, non-periodic variations in both eccentricity and semi-major axis.

---

**Part 2: The HR 8799 System**
*   **System Characteristics:** The simulation extends to HR 8799, a young star system located 39 parsecs away and roughly 30 million years old.
*   **Direct Imaging:** Due to their relatively recent formation, the system's four giant exoplanets (b, c, d, and e) still radiate substantial heat, enabling direct observation.
*   **Observational Data:** Reference is made to a one-hour L band (3.5 microns) exposure captured by the Keck II telescope (Marois et al., 2010). This successfully imaged the system by employing specialised optical techniques to obscure the host star's overwhelming light.
