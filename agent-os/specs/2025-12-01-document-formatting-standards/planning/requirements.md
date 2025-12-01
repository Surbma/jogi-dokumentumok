# Spec Requirements: Document Formatting Standards

## Initial Description

The user wants to create uniform heading styling and text formatting standards across all legal documents in this repository. The reference document is `md/aszf-premiumwp-optimalizalas.md`.

The goal is to:
1. Analyze and document all syntax and formatting patterns used in the reference document
2. Create a comprehensive formatting standards guide
3. Add this guide to the README.md for future reference
4. Ensure all future modifications follow these standards

## Requirements Discussion

### First Round Questions

**Q1:** Section numbering style: The reference uses `1.` without parentheses. Should we standardize ALL documents to this format, removing the `)` from `aszf-premiumwp-uzemeltetes.md`?
**Answer:** Yes, remove all parentheses from numberings!

**Q2:** VKSz numbering: The `vksz-premiumwp.md` document uses unnumbered main sections. Should this document also be numbered (e.g., `## 1. A szerződés tárgya`), or is the unnumbered style intentional for this document type?
**Answer:** We will use numbering everywhere, so this document has to be fixed to use numbering.

**Q3:** Party terminology: The reference uses "Vállalkozó" and "Megrendelő" while `aszf-premiumwp-uzemeltetes.md` uses "Szolgáltató" and "Előfizető". Should these terms be standardized, or do they represent different legal relationships?
**Answer:** They represent different legal relationships, so keep them as is.

**Q4:** Date format trailing dot: The reference uses `2025.12.01.` with a trailing dot. Is this intentional and should be kept?
**Answer:** Yes, this is the normal date format in Hungary.

**Q5:** Are there any additional formatting rules you'd like to add that I may have missed (e.g., URL formatting, legal citation style, etc.)?
**Answer:** Not yet.

**Q6:** Is there anything from the list above that should be changed or removed from the final standards?
**Answer:** This is a very good starting point.

### Existing Code to Reference

**Q:** Are there existing templates, style guides, or previous formatting documentation we should reference?
**Answer:** There is no such guides or documents.

No similar existing features identified for reference.

## Visual Assets

No visual assets provided.

## Requirements Summary

### Functional Requirements

- Create comprehensive formatting standards documentation in README.md
- Standards based on `md/aszf-premiumwp-optimalizalas.md` as reference
- All documents must use numbered sections (no parentheses)
- Hungarian date format with trailing dot: `YYYY.MM.DD.`
- Party terminology varies by document type (legal relationship specific)

### Scope Boundaries

**In Scope:**
- Document the formatting standards in README.md
- Define rules for: headings, numbering, lists, dates, versions, spacing
- Provide examples for each rule

**Out of Scope:**
- Automatically fixing existing documents (separate task)
- URL formatting rules (not yet defined)
- Legal citation style (not yet defined)

### Technical Considerations

- Standards apply to all `.md` files in the `md/` folder
- Standards should be clear enough for both human editors and AI agents
- Must be compatible with Markdown-to-PDF conversion

