## Templates

### 1. Home Template (`_layouts/home.html`)
- template to the index.html
- Features navigation: Catalogs of topics, tools, and Support
- Uses the texas.png background image

### 2. Interpretations Template (`_layouts/interpretations.html`)
- Lists all available lessons 
- Has navigation back to home
- Links to individual lesson pages

### 3. Lesson Template (`_layouts/lesson.html`)
- Displays lesson content in markdown format
- Has navigation back to topic

## File Structure

```
static site/
├── _interpretations/
|   ├──Intro.md
|   ├──lesson1.md
|   ├──lesson2.md
|   ├──lesson3.md
|   ├──lesson4.md
|   ├──lesson5.md
|   ├──lesson6.md
|   ├──lesson7.md
|   └──Outro.md
├── _layouts/
│   ├── connectsupport.html
│   ├── home.html
│   ├── interpretations.html
│   └── lesson.html
├── _config.yml
├── index.markdown
├── interpretations.markdown
├── connect-support.markdown
├── texas.png
└── Gemfile
```

## Customization

- Edit `_config.yml` to change site settings
- Modify the layouts in `_layouts/` to change the design
- Update content for collections in `_config.yml`
- Add new lessons by creating new files in `_lessons/`