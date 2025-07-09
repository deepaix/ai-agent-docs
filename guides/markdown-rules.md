# Markdown Rules (Quick Reference)

_Aim: keep docs consistent across GitHub, MkDocs Material, and other CommonMark engines._

## 1. Headings

| Level | Syntax | Example              |
|-------|--------|----------------------|
| H1    | `#`    | `# Title`            |
| H2-H6 | `##`…  | `## Section`         |

* Leave **one blank line** before and after a heading.

## 2. Paragraphs & Line Breaks

* Separate blocks with **one blank line**.  
* Hard break → end line with **two spaces** (use sparingly).

## 3. Lists

* Top-level markers: `-`, `*`, `+`, or `1.`  
* **Nest with 4 spaces** (or 1 tab).

```markdown
- Item A
    - Sub-item
```

## 4. Code

* Inline → `` `code` ``
* Block → <code>`lang</code> … <code>`</code>
* When inside lists, indent the fence **4 extra spaces**.

````markdown
- Example
    ```python
    print("hello")
    ```
````

## 5. Links & Images

* `[text](URL)` / `![alt](URL)`
* Use **relative paths from `docs/`** for local files.

## 6. Emphasis

* *Italic* → `*text*`
* **Bold** → `**text**`
* Identifiers with underscores → wrap in back-ticks: `` `regime_std` ``

## 7. Tables (keep minimal)

```markdown
| Col A | Col B |
|-------|-------|
| 1     | 2     |
```

* Header row + `---` separator only.
* Avoid for complex layouts.

## 8. HTML

* Inline HTML may render inconsistently—**avoid unless essential**.

---

Follow these rules and Markdown will render predictably throughout the project.

```
::contentReference[oaicite:0]{index=0}
```
