---
tags:
  - tipo/moc
creation_date: "{{date:YYYY-MM-DD}}"
---

# 🌤️ Dashboard Semanal: {{date:WW, YYYY}}

> [!summary] Un resumen de tus prioridades. Enfócate en 1-3 tareas importantes por área para evitar la sobrecarga.

---

## 🩺 Medicina

### Tareas Pendientes
```dataview
TASK
FROM "10_PROYECTOS" OR "20_AREAS"
WHERE !completed AND contains(file.tags, "#area/medicina")
GROUP BY file.link
```

### Notas Recientes
```dataview
LIST
FROM "50_ZETTELKASTEN"
WHERE contains(file.tags, "#area/medicina")
SORT file.ctime DESC
LIMIT 5
```

---

## 🧑‍🏫 Educación

### Tareas Pendientes
```dataview
TASK
FROM "10_PROYECTOS" OR "20_AREAS"
WHERE !completed AND contains(file.tags, "#area/educacion")
GROUP BY file.link
```

### Notas Recientes
```dataview
LIST
FROM "50_ZETTELKASTEN"
WHERE contains(file.tags, "#area/educacion")
SORT file.ctime DESC
LIMIT 5
```

---

## 🎨 Proyectos Creativos & Tech

### Tareas Pendientes
```dataview
TASK
FROM "10_PROYECTOS"
WHERE !completed AND (contains(file.tags, "#area/creativo") OR contains(file.tags, "#area/programacion"))
GROUP BY file.link
```

### Notas Germinando
```dataview
LIST
FROM "00_INBOX" OR "50_ZETTELKASTEN"
WHERE contains(file.tags, "#estado/0-germinando")
SORT file.ctime DESC
LIMIT 10
```
