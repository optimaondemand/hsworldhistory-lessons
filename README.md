# HS World History: Fall of Rome to Present -- Lesson Pages

GitHub Pages-hosted lesson, primary-source, module-map, capstone, syllabus, and
teacher-facing pages for Optima Academy Online's Grade 9 World History course
(Florida course 2109310), iframed into Canvas.

## Structure

- `modules/m01/` .. `modules/m09/` -- one folder per thematic module (see
  `CLAUDE.md`'s module table in the course root). Each holds that module's
  lessons, primary sources, module map, and capstone reading page (Modules 5
  and 9 only), named by their `{module}.{order}` ordinal
  (e.g. `1.03_lesson1.html`), matching `ordinal-map.md`.
- `frontmatter/` -- the syllabus previews (Live and On-Demand) and the two
  teacher-facing pages (standards matrix, teacher's manual).
- `downloads/` -- the two downloadable, teacher-editable syllabus `.docx` files.

Reading quizzes, Critical Questions, Primary Source Exercises, VR Activities,
module discussions, quarterly exams, and the semester final are Canvas-native
objects (per `CLAUDE.md`'s deployment split) and are not hosted in this repo.

Source of truth: `03_Build/week-NN/*.md` in the course folder, rendered through
`03_Build/md_reader.py`. Never hand-edit the generated HTML in this repo --
change the source and redeploy.
