# Product Roadmap

## Overview
This roadmap outlines the development phases for the Jogi Dokumentumok (Legal Documents) repository, from its current state to potential future enhancements.

---

## Phase 1: Foundation (Current State) ✅
**Status:** Complete  
**Timeline:** Established

### Objectives
- Establish core document repository structure
- Implement version control with Git
- Create multi-format document workflow

### Deliverables
- [x] Repository structure with organized folders (`md/`, `html/`, `pdf/`)
- [x] Markdown source files for all legal documents
- [x] HTML versions for web publishing
- [x] PDF versions for download
- [x] CHANGELOG.md with version history
- [x] README.md with documentation guidelines
- [x] Semantic versioning system (major.minor)

### Document Coverage
- [x] ÁSzF - Üzemeltetés (Operations Terms)
- [x] ÁSzF - Optimalizálás (Optimization Terms)
- [x] VKSz (Framework Agreement)

---

## Phase 2: Standardization
**Status:** Planned  
**Priority:** High

### Objectives
- Ensure consistency across all documents
- Improve documentation practices
- Establish clear workflows

### Deliverables
- [ ] Document template standardization
- [ ] Style guide for legal document formatting
- [ ] Conversion checklist (MD → HTML → PDF)
- [ ] Review process documentation
- [ ] Naming convention guidelines

### Success Criteria
- All documents follow consistent formatting
- Clear process documentation for document updates

---

## Phase 3: Automation (Future)
**Status:** Future Enhancement  
**Priority:** Medium

### Objectives
- Reduce manual effort in format conversion
- Minimize human error in document processing
- Streamline publishing workflow

### Potential Deliverables
- [ ] Automated MD → HTML conversion
- [ ] Automated MD → PDF generation
- [ ] Pre-commit hooks for validation
- [ ] CI/CD pipeline for document builds
- [ ] Automated changelog entry formatting

### Technology Considerations
- Pandoc for format conversion
- GitHub Actions or similar CI/CD
- Custom scripts for batch processing

---

## Phase 4: Enhanced Features (Future)
**Status:** Future Enhancement  
**Priority:** Low

### Objectives
- Improve document accessibility and usability
- Add advanced tracking capabilities

### Potential Deliverables
- [ ] Document comparison/diff viewer
- [ ] Version-specific document URLs
- [ ] Search functionality across documents
- [ ] Document validity tracking (effective dates)
- [ ] Notification system for document updates
- [ ] Multi-language support (if needed)

---

## Version History Tracking

| Version | Date | Phase | Key Changes |
|---------|------|-------|-------------|
| 16.0 | 2025-12-01 | Phase 1 | Added ÁSzF - Optimalizálás, restructured files |
| 15.0 | 2025-01-31 | Phase 1 | ÁSzF - Üzemeltetés updates |
| 14.0 | 2024-12-17 | Phase 1 | Added VKSz to repository |

---

## Notes
- Automation (Phase 3) is intentionally deferred to maintain simplicity
- Roadmap will be reviewed and updated as needs evolve
- Priority may shift based on team feedback and usage patterns

