# Tech Stack

## Overview
The Jogi Dokumentumok repository uses a simple, maintainable technology stack focused on document management and version control.

---

## Current Stack

### Source Format
| Technology | Purpose | Notes |
|------------|---------|-------|
| **Markdown** | Source document format | Simple, readable, version-control friendly |

### Output Formats
| Format | Purpose | Generation Method |
|--------|---------|-------------------|
| **Markdown (.md)** | Source files, developer access | Native format |
| **HTML (.html)** | Web publishing | Manual conversion |
| **PDF (.pdf)** | Download, printing, archival | Manual conversion |

### Version Control
| Technology | Purpose | Notes |
|------------|---------|-------|
| **Git** | Version control | Complete change history |
| **GitHub/Remote** | Remote repository | Backup and collaboration |

### Conversion Tools
| Tool | Purpose | URL |
|------|---------|-----|
| **markdowntopdf.com** | MD → PDF conversion | https://www.markdowntopdf.com/ |
| **Manual process** | MD → HTML conversion | Custom formatting for web |

---

## File Structure

```
Jogi-dokumentumok/
├── md/                          # Markdown source files
│   ├── aszf-premiumwp-optimalizalas.md
│   ├── aszf-premiumwp-uzemeltetes.md
│   └── vksz-premiumwp.md
├── html/                        # HTML for web publishing
│   ├── aszf-premiumwp-optimalizalas.html
│   ├── aszf-premiumwp-uzemeltetes.html
│   └── vksz-premiumwp.html
├── pdf/                         # PDF for download
│   ├── aszf-premiumwp-optimalizalas.pdf
│   ├── aszf-premiumwp-uzemeltetes.pdf
│   └── vksz-premiumwp.pdf
├── CHANGELOG.md                 # Version history
├── README.md                    # Documentation
└── agent-os/                    # AI agent configuration
    ├── config.yml
    ├── commands/
    └── product/
```

---

## Document Workflow

```
┌─────────────────┐
│  Edit Markdown  │
│   Source File   │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ Update Version  │
│   & Changelog   │
└────────┬────────┘
         │
    ┌────┴────┐
    ▼         ▼
┌───────┐ ┌───────┐
│ HTML  │ │  PDF  │
│ Export│ │ Export│
└───────┘ └───────┘
         │
         ▼
┌─────────────────┐
│   Git Commit    │
│    & Push       │
└─────────────────┘
```

---

## Naming Conventions

### File Naming Pattern
```
{document-type}-{company}-{service}.{extension}
```

**Examples:**
- `aszf-premiumwp-optimalizalas.md` - ÁSzF for Optimization service
- `aszf-premiumwp-uzemeltetes.md` - ÁSzF for Operations service
- `vksz-premiumwp.md` - Framework Agreement

### Document Types
| Abbreviation | Hungarian | English |
|--------------|-----------|---------|
| `aszf` | Általános Szerződési Feltételek | General Terms and Conditions |
| `vksz` | Vállalkozási Keretszerződés | Framework Agreement |

---

## Versioning System

### Semantic Versioning
- **Major version (X.0)**: Content changes affecting meaning, terms, or conditions
- **Minor version (X.Y)**: Stylistic, formatting, or typo corrections

### Version Location
- Global version in CHANGELOG.md
- Document-specific version in document header

---

## Future Tech Considerations

When automation becomes a priority, consider:

### Conversion Automation
| Tool | Purpose |
|------|---------|
| **Pandoc** | Universal document converter |
| **wkhtmltopdf** | HTML to PDF conversion |
| **marked** | Markdown to HTML |

### CI/CD Options
| Platform | Use Case |
|----------|----------|
| **GitHub Actions** | Automated builds on commit |
| **Local scripts** | Batch conversion |

### Validation
| Tool | Purpose |
|------|---------|
| **markdownlint** | Markdown syntax validation |
| **Custom scripts** | Version number consistency checks |

---

## Dependencies

### Current (None required)
The repository has no software dependencies - all tools are external services or manual processes.

### Development Environment
- Any text editor with Markdown support
- Git client
- Web browser (for conversion service)

