# Geophone
Open source files for building you own geophone!

Geophone created by [Inspecteur la Street](https://www.instagram.com/inspecteurlastreet/) & [Neifen](https://www.instagram.com/nathan.eh/). Printing test and final done at [66Origin](https://www.instagram.com/sixtysixorigin/) by [Thomas Girod](https://www.instagram.com/speedbiscuit/).

Done with FreeCAD 0.21.2 and printed with a bambulab P1S.

![IMG_6013 2](https://github.com/user-attachments/assets/b5ce6d84-a8ce-4731-8fdc-f7bce7dd2567)

***

### Definition

A geophone is a seismic sensor that converts ground vibrations into an electrical signal. It works using a mass suspended inside a coil or a magnet: when the ground vibrates, the difference in movement between the mass and the housing generates an electrical current proportional to the velocity of the ground motion.

Geophones are used in seismology to detect earthquakes, in geophysics for oil exploration, and in engineering to monitor infrastructure vibrations.

The idea here is to use it to record ground and object vibrations, as well as natural sounds, in the context of field recording or sound experimentation. Unlike a piezo microphone, the geophone focuses on low frequencies because it is less sensitive to high frequencies.

***

### Sourcing


| Element | info  | link   |
| :---:   | :---: | :---: |
| Geophone sensor | EG-10HP-I (SM-24) / vertical | [Alibaba](https://www.alibaba.com/product-detail/High-Precision-10Hz-vertical-geophone-SM_1600268273669.html?spm=a2756.trade-list-buyer.0.0.749976e99944gs) |
| XLR male head | male | [Thomann](https://www.thomann.fr/neutrik_nc_3_mxxb.htm)   |
| XLR cable | ? | Thomann |
| Cable Glands | PG9 - IP68 | [Amazon](https://www.amazon.fr/-/en/dp/B09XGNLD4B?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1&language=fr_FR) |
| Flat Head Nut | M6 thread | [Amazon](https://www.amazon.fr/-/en/dp/B0B1TXMZ34?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1&language=fr_FR) |
| Screw | M6 / L 16 mm | [Thomann](https://www.thomann.fr/adam_hall_5410blk_rack_screw_pack.htm) |
| Magnets Round Rubber | M6 thread | [Amazon](https://www.amazon.fr/-/en/dp/B0CLZFZX44?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1&language=fr_FR) |
| Plunger | M6 thread | [Amazon](https://www.amazon.fr/-/en/627313_1_HuSjAn6Hi/dp/B0DMW68LCQ?crid=16STM5HQW72R2&dib=eyJ2IjoiMSJ9.76IrIQ2dlbbGOn-Sta9WIl1hCBua3o1R0ugKljg49xgoKEtLLKr9zVywbkU5ejqhMToZ736Rj0zklOsVaHV_OzpKwxDWOLGhpZ4XSLTcO1EErJdg22LgCyFRBwvrd2C2-34LNMQVMayOe_laKVIIJoR50yXeg1LGmC4RCwSNVRiQekUw-XL06mlQCMqGTADaebLy32JTlfvNP6BSmX8PdynlVuQBMwZI0hMR0hCYTJSkR69FWXskteOxQFP0xWSvk9hcc-4USMvHRPt98IQ9-guqbrls6Ow7D4DIG8CNOt0.cvg-YzcqHroSM7X0xNB2ShK-qSZ1eW_v0ZXxVEUKfZ8&dib_tag=se&keywords=ventouse+m6&qid=1745505189&sprefix=ventouse+m6%2Caps%2C99&sr=8-7) |
| Steel Straight Hand Wire | M6 thread | [Amazon](https://www.amazon.fr/-/en/dp/B09LCT2KBY?ref=ppx_yo2ov_dt_b_fed_asin_title) |
| O-Ring| 30,8 x 38 x 3,6 tore | / |
| O-Ring| 15,1 x 20,5 x 2,7 tore | / |

***

### Build information

![anotation github_00000](https://github.com/user-attachments/assets/dce7fe2b-9848-4121-a9c9-41acc37c643e)

Printed in [PLA-CF](https://eu.store.bambulab.com/fr-fr/collections/pla/products/pla-cf), but it also works well with PETG, which seems more suitable for outdoor use. Nonetheless, we haven’t had any issues with humidity when using PLA. The structure is thick enough to protect the sensor, and all the joints contribute to that. However, it's not designed to be submerged. For underwater use, we recommend checking out a good [DIY hydrophone tutorial](https://www.instructables.com/Lets-Build-Some-World-Class-Hydrophones/).

The flat head nut needs to be glued to the printed part.

![soudure](https://github.com/user-attachments/assets/5fb17083-150b-4e44-a2bb-51eb8b0440a6)

The ground connection is not required when soldering the XLR cable to the geophone (but need to be on the XLR head). It's recommended to test the polarity (positive and negative) beforehand, although our tests indicate that the orientation has little to no impact on performance.

If you have any questions, feel free to reach out.
