# GAIA-AIR-ESSENTIALS

**ESTRUCTURA PRIMARIA**

## ON GROUND (on-ground)
Infraestructura terrestre, soporte, operaciones base.  
**Ecosystem:** ON-GROUND-ECOSYSTEMS

## INTRO ATMOSFERIC (intro-sphere)
Región atmosférica inferior, vuelos por debajo de la ionosfera.  
**Ecosystem:** INTRO-SPHERE-ECOSYSTEMS

## EXO ATMOSFERIC (exo-sphere)
Región superior y exoatmosférica, operaciones orbitales o de límite.  
**Ecosystem:** EXO-SPHERE-ECOSYSTEMS

---

## Interactive Diagram

To visualize the relationships between zones and ecosystems, here is an interactive diagram rendered using Mermaid:

```mermaid
graph TD
    %% Primary Structure
    ON_GROUND["ON GROUND (on-ground)\nInfraestructura terrestre, soporte, operaciones base."]
    INTRO_SPHERE["INTRO ATMOSPHERIC (intro-sphere)\nRegión atmosférica inferior, vuelos por debajo de la ionosfera"]
    EXO_SPHERE["EXO ATMOSPHERIC (exo-sphere)\nRegión superior y exoatmosférica, operaciones orbitales o de límite."]

    %% Ecosystems
    ON_GROUND --> ON_GROUND_ECOSYSTEMS["ON-GROUND-ECOSYSTEMS"]
    INTRO_SPHERE --> INTRO_SPHERE_ECOSYSTEMS["INTRO-SPHERE-ECOSYSTEMS"]
    EXO_SPHERE --> EXO_SPHERE_ECOSYSTEMS["EXO-SPHERE-ECOSYSTEMS"]

    %% Connections between zones
    ON_GROUND --> INTRO_SPHERE
    INTRO_SPHERE --> EXO_SPHERE
```

---

### Notes

- Use the [Mermaid Live Editor](https://mermaid-js.github.io/mermaid-live-editor/) to customize and interact with the diagram further.
- If the Mermaid diagram does not render in this Markdown viewer, copy the code into the live editor above for visualization.

```
