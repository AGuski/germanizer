

# germanizer

Una habilidad para Claude Code y OpenCode que mejora cualquier texto haciéndolo más alemán.

Basado en [humanizer](https://github.com/blader/humanizer) de blader.

## Instalación

### Claude Code

Clona directamente en el directorio de habilidades de Claude Code:

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/AGuski/germanizer.git ~/.claude/skills/germanizer
```

O copia el archivo de la habilidad manualmente si ya tienes este repositorio clonado:

```bash
mkdir -p ~/.claude/skills/germanizer
cp SKILL.md ~/.claude/skills/germanizer/
```

### OpenCode

Clona directamente en el directorio de habilidades de OpenCode:

```bash
mkdir -p ~/.config/opencode/skills
git clone https://github.com/AGuski/germanizer.git ~/.config/opencode/skills/germanizer
```

O copia el archivo de la habilidad manualmente si ya tienes este repositorio clonado:

```bash
mkdir -p ~/.config/opencode/skills/germanizer
cp SKILL.md ~/.config/opencode/skills/germanizer/
```

> **Nota:** OpenCode también escanea `~/.claude/skills/` por compatibilidad, por lo que un solo clon en `~/.claude/skills/germanizer/` funciona para ambas herramientas.

## Uso

### Claude Code

```
/germanizer

[pega tu texto aquí]
```

### OpenCode

```
/germanizer

[pega tu texto aquí]
```

O pide al modelo que germanice el texto directamente en cualquiera de las herramientas:

```
Por favor, germaniza este texto: [tu texto]
```
