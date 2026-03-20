# RhinoPy — Python for Rhino & Grasshopper

> **A complete, free, offline learning package for Python scripting in Rhino and Grasshopper.**  
> 18 chapters · Full API reference · Quick-reference cheatsheet · No internet required

**Created by [Dinesh Kumar Alagusundaram](https://github.com/gridlogic-dk)**  
Licensed under the [MIT License](LICENSE.md) — Free to use, share, modify, and distribute.

---

## 🌐 Live Website

👉 **[gridlogic-dk.github.io/rhinopy](https://gridlogic-dk.github.io/rhinopy)**

Open `index.html` locally in any browser — works completely offline.

---

## What Is This?

RhinoPy is a **self-contained learning package** designed for architects, designers, engineers, and computational designers who want to learn Python scripting inside **Rhino 3D** and **Grasshopper**.

Most Python tutorials teach generic programming. RhinoPy is built specifically around how Python works *inside Rhino* — using `rhinoscriptsyntax`, `Rhino.Geometry`, and `GHPython`. Every example produces real geometry, real objects, and real results inside your 3D viewport.

Whether you are writing your first script or building parametric towers and attractor fields, this package takes you from zero to confident.

---

## What You Can Do With This Package

| You want to… | Go to |
|---|---|
| Learn Python from scratch for Rhino | `learn.html` — Chapters 1–4 |
| Understand brackets, indentation, types | `learn.html` — Chapters 2–3 |
| Write if/else and loop logic | `learn.html` — Chapters 5–6 |
| Work with lists, tuples, dictionaries | `learn.html` — Chapter 7 |
| Build your own classes and objects | `learn.html` — Chapter 8 |
| Create curves, surfaces, meshes in Rhino | `learn.html` — Chapter 9 |
| Import modules and use the full API | `learn.html` — Chapter 10 |
| Debug scripts step by step | `learn.html` — Chapter 11 |
| Write Python components in Grasshopper | `learn.html` — Chapter 12 |
| Master strings and text handling | `learn.html` — Chapter 13 |
| Handle errors gracefully | `learn.html` — Chapter 14 |
| Save and load data from files / JSON | `learn.html` — Chapter 15 |
| Use lambda, generators, *args | `learn.html` — Chapter 16 |
| Use RhinoCommon (rg.) geometry objects | `learn.html` — Chapter 17 |
| Build attractor fields, mesh functions, towers | `learn.html` — Chapter 18 |
| Look up any `rs.` method instantly | `api.html` — Full API Reference |
| Get a quick reminder of syntax | `cheatsheet.html` |

---

## Package Contents

```
rhinopy-complete/
├── index.html          ← Hub page — start here
├── learn.html          ← Full 18-chapter learning guide
├── api.html            ← Offline RhinoScriptSyntax API reference
├── cheatsheet.html     ← Printable quick-reference card
├── LICENSE.md          ← MIT License
└── README.md           ← This file
```

### `index.html` — The Hub
The starting page. Shows all 18 chapter cards and all 20 API categories at a glance. Click anything to jump straight to the content.

### `learn.html` — The Full Course (18 Chapters)

A complete, deeply explained learning guide covering every core topic with real Rhino code examples throughout.

| # | Chapter | What You Learn |
|---|---|---|
| 01 | What is Scripting? | Macros vs Scripts vs Programs, EditPythonScript, RunPythonScript |
| 02 | Python Essentials | Variables, data types, naming conventions, indentation, case sensitivity |
| 03 | Brackets Decoded | `( )` for calls, `[ ]` for lists/indexing, `{ }` for dicts, f-strings |
| 04 | Operators & Functions | All operators, def / return, default args, variable scope |
| 05 | Conditionals | if / elif / else, boolean logic, Venn diagrams, Rhino examples |
| 06 | Loops | while, for, range(), break, continue, nested loops |
| 07 | Lists, Tuples, Dicts | All container types, methods, list comprehensions, mutability |
| 08 | Classes & OOP | `__init__`, self, inheritance, polymorphism, isinstance() |
| 09 | Geometry in Rhino | Points, vectors, lines, planes, circles, NURBS, surfaces, meshes |
| 10 | Imports & Modules | All import forms, rs vs rg, GHPython template |
| 11 | Debugging | Rhino debugger, breakpoints, step controls, common error fixes |
| 12 | Grasshopper Python | GHPython inputs/outputs, rs vs rg, DataTree, facade panel example |
| 13 | Strings Deep Dive | All string methods, slicing, f-strings, format specifiers |
| 14 | Error Handling | try/except/finally, exception types, raising custom exceptions |
| 15 | File I/O | Read/write files, JSON save/load, os.path, settings persistence |
| 16 | Advanced Python | lambda, *args/**kwargs, generators/yield, map/filter |
| 17 | RhinoCommon (rg.) | Point3d, Vector3d, Plane, NurbsCurve, Brep, Transform |
| 18 | Parametric Patterns | Attractor fields, mesh from f(x,y), parametric tower, 5 design principles |

### `api.html` — Full Offline API Reference

A complete offline copy of the RhinoScriptSyntax API, organized into 20 categories. Every method entry shows:
- Full function signature with parameter names and types
- Optional vs required parameters
- Return type
- A working code example you can copy directly into Rhino

**Live search bar** filters all methods as you type — find anything in under a second.

| Category | What It Contains |
|---|---|
| Application | Command, EnableRedraw, Ortho, Osnap, Sleep, Prompt |
| Curve | AddLine, AddCurve, CurveLength, DivideCurve, EvaluateCurve |
| Surface | AddSphere, AddLoftSrf, EvaluateSurface, SurfaceFrame |
| Geometry | Distance, Angle, BrepClosestPoint |
| Object | DeleteObject, ObjectName, ObjectColor, ScaleObject |
| Point/Vector | AddPoint, VectorAdd, VectorCrossProduct, VectorRotate |
| Mesh | AddMesh, MeshVertices, MeshFaceVertices |
| Layer | AddLayer, LayerColor, ObjectLayer |
| Selection | GetObject, GetObjects, GetPoint, rs.filter constants |
| User Interface | GetString, GetNumber, MessageBox, ListBox, GetColor |
| Utility | UnitAbsoluteTolerance, ZoomExtents, Redraw |
| Transformation | XformTranslation, XformRotation, TransformObject |
| View | ViewNames, CurrentView, ViewDisplayMode |
| Document | DocumentName, DocumentSaved, SaveFile |
| Block | InsertBlock, BlockNames, IsBlock |
| Group | AddGroup, AddObjectsToGroup |
| Material | AddMaterial, ObjectMaterialSource, MaterialColor |
| Hatch | AddHatch, HatchPatternNames |
| Light | AddPointLight, AddDirectionalLight, AddSpotLight |
| Linetype | ObjectLineType, LinetypeNames |

### `cheatsheet.html` — Quick Reference Card

28 cards covering everything you need in one printable page. Works offline, print-friendly. Covers imports, variables, operators, loops, lists, functions, Rhino creation/query, vector math, selection, object attributes, performance patterns, strings, error handling, file I/O, lambda, generators, RhinoCommon, and parametric design patterns.

---

## How To Use It

### Online (GitHub Pages)
Just open the live link — no installation needed.

### Offline (Local)
1. Click the green **Code** button → **Download ZIP**
2. Unzip anywhere on your computer
3. Open `index.html` in Chrome, Firefox, Edge, or Safari
4. Everything works 100% offline — no internet, no server, no installation

### Inside Rhino
Copy any code example from `learn.html` or `api.html` directly into the **EditPythonScript** editor in Rhino and run it. All examples are tested and working.

### Inside Grasshopper
Chapter 12 and 17 examples are written specifically for **GHPython** components. Paste them into a Python Script component, connect your inputs, and run.

---

## Who Is This For?

- **Architects and designers** who want to automate repetitive tasks in Rhino
- **Students** learning computational design for the first time
- **Grasshopper users** who want to write their own Python components
- **Intermediate scripters** looking for a solid reference on RhinoCommon
- **Educators and workshop leaders** who want a ready-made teaching resource
- **Anyone** moving from RhinoScript (VBScript) to Python

No prior programming experience required for the first 6 chapters. Basic Python knowledge is assumed from Chapter 7 onwards.

---

## Sources & References

This package was researched and written using:

- **Python Primer for Rhino** — Skylar Tibbits, Arthur van der Harten, Steve Baer (McNeel & Associates, 2011)
- **RhinoScript Primer for Rhino 4** — David Rutten (McNeel & Associates, 2008)
- **RhinoScriptSyntax API Documentation** — [developer.rhino3d.com](https://developer.rhino3d.com/api/RhinoScriptSyntax/)
- **RhinoCommon SDK Documentation** — [developer.rhino3d.com/api/RhinoCommon/](https://developer.rhino3d.com/api/RhinoCommon/)

All code examples are original, written to illustrate the concepts clearly for learners.

Rhino® and Grasshopper® are registered trademarks of Robert McNeel & Associates.

---

## Contributing

Contributions are welcome! If you want to add a chapter, fix an error, improve an example, or translate the content — here is how:

1. **Fork** this repository (click the Fork button, top right)
2. Make your changes in your fork
3. **Submit a Pull Request** with a clear description of what you changed and why
4. Dinesh Kumar Alagusundaram will review and merge

### Contribution Guidelines

- Keep the same dark-theme design and code style
- All code examples must work in Rhino 6, 7, or 8
- Label Grasshopper-specific code clearly with a comment
- Do not remove or change the author credit or license
- Do not delete existing chapters — add new ones or improve existing ones
- One topic per Pull Request keeps reviews fast

### Ideas for Contributions

- Add more real-world script examples (facades, paneling, structural grids)
- Add a Chapter 19 on IronPython vs CPython differences in Rhino 8
- Add a Chapter 20 on rhinoinside (using Rhino outside Rhino)
- Translate to another language
- Add more API methods to `api.html`
- Add interactive examples with live code editing

---

## License

```
MIT License
Copyright (c) 2024 Dinesh Kumar Alagusundaram

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

**In plain English:**
- ✅ Free to use personally and commercially
- ✅ Free to share with anyone
- ✅ Free to modify and extend
- ✅ Free to use in paid workshops or courses
- ⚠️ Keep the author credit and license when redistributing

See [LICENSE.md](LICENSE.md) for the full text.

---

## Star This Repo ⭐

If this package helped you, give it a star — it helps other Rhino users find it.

---

*RhinoPy Complete · Created by Dinesh Kumar Alagusundaram · MIT License · Open Source*
