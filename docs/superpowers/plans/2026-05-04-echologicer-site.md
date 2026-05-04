# EchoLogicer Site Refresh Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Replace the current SingularityLaber marketing site with a distinct EchoLogicer studio website for iOS software and IAA monetization.

**Architecture:** Reuse the current static multi-page site structure, but replace the branding, rewrite page content, and redesign the global CSS into a bright editorial operations style. Keep the single shared stylesheet, shared JS, and test file structure.

**Tech Stack:** Static HTML, CSS, minimal browser JS, Node built-in test runner

---

### Task 1: Update Test Expectations

**Files:**
- Modify: `C:\Users\64998\Pictures\singularitylaber\tests\site.test.mjs`

- [ ] **Step 1: Update tests to expect EchoLogicer branding and contacts**
- [ ] **Step 2: Run `cmd /c npm test` and verify failures reflect old site content**

### Task 2: Rewrite Shared Brand and Content

**Files:**
- Modify: `C:\Users\64998\Pictures\singularitylaber\index.html`
- Modify: `C:\Users\64998\Pictures\singularitylaber\studio.html`
- Modify: `C:\Users\64998\Pictures\singularitylaber\services.html`
- Modify: `C:\Users\64998\Pictures\singularitylaber\monetization.html`
- Modify: `C:\Users\64998\Pictures\singularitylaber\contact.html`
- Modify: `C:\Users\64998\Pictures\singularitylaber\privacy.html`
- Modify: `C:\Users\64998\Pictures\singularitylaber\support.html`

- [ ] **Step 1: Replace brand name, positioning, and contact routes**
- [ ] **Step 2: Rewrite homepage and section copy around EchoLogicer themes**
- [ ] **Step 3: Rewrite privacy and support detail without shrinking coverage**

### Task 3: Redesign Shared Visual Language

**Files:**
- Modify: `C:\Users\64998\Pictures\singularitylaber\assets\css\styles.css`
- Modify: `C:\Users\64998\Pictures\singularitylaber\assets\js\site.js` (only if needed)

- [ ] **Step 1: Replace dark lab palette with warm editorial operations palette**
- [ ] **Step 2: Adjust layout treatments, card surfaces, type hierarchy, and section rhythm**
- [ ] **Step 3: Preserve responsive behavior and shared reveal interactions**

### Task 4: Verify Site Integrity

**Files:**
- Modify: `C:\Users\64998\Pictures\singularitylaber\tests\site.test.mjs` (if small fixes are needed)

- [ ] **Step 1: Run `cmd /c npm test`**
- [ ] **Step 2: Fix any failures until the full suite passes**
- [ ] **Step 3: Search for old brand/email remnants and remove them**

### Task 5: Commit and Push

**Files:**
- Modify: repository state only

- [ ] **Step 1: Stage changed site files only**
- [ ] **Step 2: Commit with a feature message for EchoLogicer**
- [ ] **Step 3: Push `main` to `origin`**
