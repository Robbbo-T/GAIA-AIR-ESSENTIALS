
# GAIA-AIR-ESSENTIALS

**ESTRUCTURA PRIMARIA**

## ON GROUND (on-ground)
Infraestructura terrestre, soporte, operaciones base.

## INTRO ATMOSFERIC (intro-sphere)
Región atmosférica inferior, vuelos por debajo de la ionosfera

## EXO ATMOSFERIC (exo-sphere)
Región superior y exoatmosférica, operaciones orbitales o de límite.

ON-GROUND → ON-GROUND-ECOSYSTEMS

INTRO-SPHERE → INTRO-SPHERE-ECOYSTEMS

EXO-SPHERE → EXO-SPHERE-ECOSYSTEMS

```MERMAID
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
navigating to [GAIA-AIR-ESSENTIALS](https://github.com/Robbbo-T/GAIA-AIR-ESSENTIALS/new/main?readme=1), creating a new file, and pasting the markdown content above. Let me know if you need further assistance!
