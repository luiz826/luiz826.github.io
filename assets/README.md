# Assets Directory Structure

This directory contains all static assets for the portfolio website, organized by type and purpose.

## Directory Structure

```
assets/
├── css/
│   └── styles.css          # Main stylesheet with Medium-inspired design
├── docs/
│   └── curriculo.pdf       # PDF resume/CV document
└── images/
    ├── profile/            # Profile pictures and personal photos
    │   ├── me.jpeg
    │   └── me-crop.jpeg
    ├── companies/          # Company logos and workplace images
    │   ├── nubank.jpeg
    │   ├── embrapii.jfif
    │   └── mgi_tech.jpeg
    ├── certifications/     # Professional certification images
    │   ├── deep_learning.jpeg
    │   ├── huawei_cert.jpeg
    │   └── mlprod_cert.jpeg
    └── projects/           # Project screenshots and related images
        ├── ci.jpg
        ├── momento.png
        ├── resume.png
        ├── tail.png
        └── trilha.png
```

## Usage

All HTML files in the `pages/` directory reference these assets using relative paths:
- CSS: `../assets/css/styles.css`
- Images: `../assets/images/[category]/[filename]`
- Documents: `../assets/docs/[filename]`

## Maintenance

When adding new assets:
1. Place them in the appropriate category folder
2. Update any HTML files that reference them
3. Ensure consistent naming conventions (lowercase, descriptive)
