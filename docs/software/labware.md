# Labware

## ¿Qué es el labware?

Hay multitud de placas de pocillos y elementos en un laboratorio de un hospital.

Para ajustar el robot a cada placa de pocillos se utilizan librerías que contienen
los tamaños exactos de las placas de pocillos y otro material.

![Una placa de pocillos](/assets/images/hardware/pocillos.jpg)

## ¿Cómo se usa el labware?

El "labware" se utiliza a través de un API específico.

Consulte [esta página de internet](https://support.opentrons.com/en/articles/3136507-using-the-labware-library) para saber cómo usar el labware.

## Librería de labware

El fabricante del robot [tiene esta librería de labware](https://labware.opentrons.com/)
que puede utilizarse para ajustar el robot a las placas.

### Ejemplos

Algunos ejemplos de definiciones de labware que vienen con el robot:

- [Agilent 1 Well Reservoir 290 mL](https://labware.opentrons.com/agilent_1_reservoir_290ml/)
- [Axygen 1 Well Reservoir 90 mL](https://labware.opentrons.com/axygen_1_reservoir_90ml/)
- [Corning 96 Well Plate 360 µL Flat](https://labware.opentrons.com/corning_96_wellplate_360ul_flat/)
- [NEST 96 Well Plate 100 µL PCR Full Skirt](https://labware.opentrons.com/nest_96_wellplate_100ul_pcr_full_skirt/)

!!! note
    Obviamente, antes de ejecutar un protocolo con el robot debe ajustarse el labware al
    material que se vaya a usar. De otro modo la pipeta del robot derramará material fuera
    de los pocillos.




## ¿Cómo se hace un labware específico?

Si las placas tienen dimensiones específicas, puede usar esta [herramienta web](https://labware.opentrons.com/create) que permite crear (y compartir) labware a medida. 

[Esta página](https://support.opentrons.com/en/articles/3136504-creating-custom-labware-definitions) 
(en inglés) indica cómo hacer labware específico.



