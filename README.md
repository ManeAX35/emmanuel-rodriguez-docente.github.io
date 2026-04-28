# Emmanuel Alfredo Rodríguez Ortiz · Portafolio Docente

🌐 **Sitio:** https://ManeAX35.github.io/emmanuel-rodriguez-docente.github.io

---

## Cómo publicar en GitHub Pages (primera vez)

1. Crea un repositorio en GitHub llamado: `emmanuel-rodriguez-docente.github.io`
2. Entra a la carpeta del ZIP que descargaste y abre una terminal aquí
3. Ejecuta estos comandos uno por uno:

```bash
git init
git add .
git commit -m "Portafolio docente inicial"
git branch -M main
git remote add origin https://github.com/ManeAX35/emmanuel-rodriguez-docente.github.io.git
git push -u origin main
```

4. Ve a **Settings → Pages → Source: main / (root) → Save**
5. En 1-2 minutos tu sitio está en vivo ✅

---

## Cómo actualizar cada semestre

Al final de cada semestre, solo:

1. Agrega los archivos nuevos (PDFs de notas, notebooks, fotos) a las carpetas correspondientes
2. Reemplaza el `index.html` con la versión nueva que te genere Claude
3. Desde la carpeta del repo ejecuta:

```bash
git add .
git commit -m "Actualización semestre 2026-2"
git push
```

Listo — GitHub Pages se actualiza automáticamente en segundos.

---

## Estructura del repositorio

```
emmanuel-rodriguez-docente.github.io/
│
├── index.html                        ← página principal
├── README.md
│
├── img/
│   ├── foto-perfil.png               ← foto de perfil del hero
│   └── galeria/                      ← fotos de galería (8 actuales)
│
├── constancias/
│   ├── titulos-cedulas/              ← títulos y cédulas PDF
│   │   ├── titulo-licenciatura.pdf
│   │   ├── cedula-licenciatura-13338361.pdf
│   │   ├── titulo-maestria.pdf
│   │   └── cedula-maestria-15085091.pdf
│   ├── CV_Emmanuel_Rodriguez.pdf
│   ├── TOEFL_EARO.pdf
│   └── ... (todas las demás constancias)
│
├── notas/                            ← PDFs de notas de clase (agregar conforme avance)
│
└── codigos/                          ← notebooks Jupyter por materia
    ├── Metodos numericos, ingenieria LaSalle/
    ├── Simulacion estocastica/
    ├── Inteligencia artificial, ingenieria economica, lasalle/
    ├── Python basico/
    └── Analisis de datos/
```

---

## Checklist fin de semestre

- [ ] ¿Nuevos cursos que agregar?
- [ ] ¿Notas de clase en PDF para subir?
- [ ] ¿Notebooks nuevos de clase?
- [ ] ¿Ponencias, congresos o charlas nuevas?
- [ ] ¿Nuevas constancias o certificaciones?
- [ ] ¿Fotos nuevas para la galería?

---

*Morelia, Michoacán · 2022–presente*
