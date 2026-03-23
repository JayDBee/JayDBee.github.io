# JayDBee Jekyll Website

This is a Jekyll website with three main templates:

## Templates

### 1. Home Template (`_layouts/home.html`)
- Similar to the original index.html
- Features two main buttons: Catalogs and Connect&Support
- Uses the texas.png background image

### 2. Catalogs Template (`_layouts/catalogs.html`)
- Lists all available lessons (1-5)
- Has navigation back to home
- Links to individual lesson pages

### 3. Lesson Template (`_layouts/lesson.html`)
- Displays lesson content in markdown format
- Has navigation back to catalogs
- Styled consistently with the other pages

## Pages

- `index.markdown` - Home page using home layout
- `catalogs.markdown` - Catalogs page using catalogs layout
- `connect-support.markdown` - Connect & Support page using home layout
- `_lessons/lesson1.markdown` through `_lessons/lesson5.markdown` - Individual lesson pages

## Running the Site

To run this Jekyll site:

1. Make sure you have Ruby and Jekyll installed
2. Navigate to the `static site` directory
3. Run `bundle install` (if bundler works)
4. Run `jekyll serve`
5. Open your browser to `http://localhost:4000`

## File Structure

```
static site/
├── _layouts/
│   ├── home.html
│   ├── catalogs.html
│   └── lesson.html
├── _lessons/
│   ├── lesson1.markdown
│   ├── lesson2.markdown
│   ├── lesson3.markdown
│   ├── lesson4.markdown
│   └── lesson5.markdown
├── _config.yml
├── index.markdown
├── catalogs.markdown
├── connect-support.markdown
└── Gemfile
```

## Customization

- Edit `_config.yml` to change site settings
- Modify the layouts in `_layouts/` to change the design
- Update lesson content in `_lessons/`
- Add new lessons by creating new files in `_lessons/`