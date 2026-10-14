# lf-media

Hospedaje público de las imágenes de Los Futbolers™ para que el Social Planner de
GoHighLevel las pueda recoger. **No es un repositorio de trabajo**: es un bucket.

El conector de GHL puede crear y programar posts, pero su campo `media[].url` exige
una URL pública y el conector no expone ninguna operación de subida. De ahí este repo.

- `img/LF_S01_C1.png` … `LF_S12_C6.png` — las seis láminas de cada carrusel, en orden.
- `img/LF_S01_P1.png` … `LF_S12_P2.png` — los dos posts sueltos de cada semana.

Las imágenes se **generan**, no se editan: salen de `ragadaka-brands/los-futbolers`
(`scripts/laminas/produce.py`). Para cambiar una, se cambia el código y se regenera.

Los Futbolers™ — Isaac Hop Cherem LLC. Marca no registrada: **™, nunca ®**.
