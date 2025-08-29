# Orchestra Omaha Newsletter Assets

This directory contains assets for Orchestra Omaha's email newsletters and communications.

## Directory Structure

```
assets/
├── images/
│   ├── logo/
│   │   ├── orchestra-omaha-logo.png          # Main logo (200px width)
│   │   ├── orchestra-omaha-logo@2x.png       # High-res version (400px width)
│   │   └── orchestra-omaha-logo.svg          # Vector version
│   ├── newsletter/
│   │   ├── concert-photos/                   # Concert and rehearsal photos
│   │   ├── musician-spotlights/              # Musician profile photos
│   │   └── event-graphics/                   # Special event graphics
│   └── social/
│       ├── facebook/                         # Facebook-optimized images
│       ├── instagram/                        # Instagram-optimized images
│       └── twitter/                          # Twitter-optimized images
├── templates/
│   ├── newsletter-html.html                  # ConvertKit HTML template
│   └── email-signatures.html                 # Email signature templates
└── README.md                                 # This file
```

## Logo Usage

### Primary Logo URL for Newsletters
```
https://orchestraomaha.github.io/assets/images/logo/orchestra-omaha-logo.jpg
```

### Logo Specifications
- **File format:** JPG (for email compatibility and smaller file sizes)
- **Dimensions:** 200px width maximum
- **File size:** Under 100KB
- **Background:** White or transparent
- **Usage:** Email newsletters, ConvertKit templates, social media

### Available Logo Versions
- **Main logo:** `orchestra-omaha-logo.jpg` (primary logo for newsletters)
- **Note logo:** `orchestra-omaha-note-logo.jpg` (alternative logo with musical note)

## Newsletter Assets

### ConvertKit Template
- **Location:** `templates/newsletter-html.html`
- **Usage:** Copy HTML into ConvertKit custom template
- **Logo URL:** Replace `[YOUR_LOGO_URL]` with the primary logo URL above

### Image Guidelines
- **Concert photos:** 600px width maximum, JPG format
- **Musician spotlights:** 300px width, square aspect ratio, JPG format
- **Event graphics:** 800px width maximum, JPG format
- **File naming:** Use descriptive names with hyphens (e.g., `september-concert-2025.jpg`)

## Social Media Assets

### Facebook
- **Profile picture:** 170x170px
- **Cover photo:** 851x315px
- **Post images:** 1200x630px

### Instagram
- **Profile picture:** 110x110px
- **Post images:** 1080x1080px (square) or 1080x1350px (portrait)

### Twitter
- **Profile picture:** 400x400px
- **Header image:** 1500x500px
- **Post images:** 1200x675px

## File Management

### Upload Process
1. **Optimize images** for web (compress, resize)
2. **Use descriptive filenames** with hyphens
3. **Organize in appropriate subdirectories**
4. **Update this README** with new asset information

### Version Control
- **Commit changes** when adding new assets
- **Use descriptive commit messages** (e.g., "Add September concert photos")
- **Tag releases** for major asset updates

## Performance Optimization

### Image Optimization
- **Compress all images** before uploading
- **Use appropriate formats** (JPG for photos and logos, good compression)
- **Consider WebP format** for web use (with JPG fallback)

### CDN Benefits
- **GitHub Pages CDN** provides fast global delivery
- **Automatic caching** improves load times
- **HTTPS enabled** by default

## Usage Examples

### ConvertKit Newsletter
```html
<img src="https://orchestraomaha.github.io/assets/images/logo/orchestra-omaha-logo.jpg" 
     alt="Orchestra Omaha" 
     style="max-width: 200px; height: auto;">
```

### Social Media Post
```markdown
![Orchestra Omaha Concert](https://orchestraomaha.github.io/assets/images/newsletter/concert-photos/september-concert-2025.jpg)
```

### Email Signature
```html
<img src="https://orchestraomaha.github.io/assets/images/logo/orchestra-omaha-logo.jpg" 
     alt="Orchestra Omaha" 
     style="width: 150px; height: auto;">
```

## Maintenance

### Regular Tasks
- **Monthly:** Review and update concert photos
- **Quarterly:** Optimize and compress existing images
- **Annually:** Review and update logo versions

### Backup Strategy
- **Local backup** of all original files
- **Version control** through Git
- **Documentation** of all asset locations and usage

---

**Last updated:** [Current Date]
**Maintained by:** Orchestra Omaha Communications Team
