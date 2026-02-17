# Elevation Protocol

Systematic process for refining visual output from functional to exceptional.

## Table of Contents
- [Overview](#overview)
- [Phase 1: Foundation](#phase-1-foundation)
- [Phase 2: Structure](#phase-2-structure)
- [Phase 3: Typography](#phase-3-typography)
- [Phase 4: Color](#phase-4-color)
- [Phase 5: Space](#phase-5-space)
- [Phase 6: Polish](#phase-6-polish)
- [Phase 7: Audit](#phase-7-audit)

---

## Overview

Every visual output goes through seven elevation phases. Each phase transforms a specific dimension. Complete all phases in order.

```
Functional → Foundation → Structure → Typography → Color → Space → Polish → Exceptional
```

Time allocation (for internal process):
- Phase 1-2: 20% (get it right structurally)
- Phase 3-5: 50% (core refinement)
- Phase 6-7: 30% (finishing touches)

---

## Phase 1: Foundation

**Goal**: Ensure content serves purpose before designing.

### Content Audit
1. What is the ONE thing this should communicate?
2. List all content elements. Rank by importance.
3. Identify: What can be cut entirely?
4. Identify: What can be combined?
5. Identify: What's missing that's essential?

### Hierarchy Definition
```
Level 1: Primary message (one thing)
Level 2: Supporting points (2-4 items)
Level 3: Details and data (as needed)
Level 4: Metadata and fine print (minimal)
```

### Action Clarification
- Primary action: What should user do?
- Secondary actions: What else might they do?
- No action: Is this purely informational?

### Exit Criteria
- [ ] Single clear purpose identified
- [ ] Content ruthlessly prioritized
- [ ] Actions defined and limited

---

## Phase 2: Structure

**Goal**: Establish bones of layout before applying style.

### Grid Selection
Choose base unit and grid:
```
Base unit: 8px (standard) or 4px (dense)
Grid: 12-column (flexible) or 6-column (simple)
Gutter: 16px (tight) to 32px (spacious)
```

### Layout Blocking
1. Sketch major regions (header, main, sidebar, footer)
2. Define content zones within regions
3. Establish visual flow direction
4. Identify focal point location

### Responsive Consideration
```
Breakpoints to consider:
- Mobile: 375px (single column)
- Tablet: 768px (two columns possible)
- Desktop: 1024px (full layout)
- Wide: 1440px+ (max-width containers)
```

### Exit Criteria
- [ ] Grid system chosen and documented
- [ ] Major sections blocked out
- [ ] Flow and focal point established
- [ ] Layout works at key breakpoints

---

## Phase 3: Typography

**Goal**: Create type system that establishes hierarchy and personality.

### Scale Selection
Choose and apply consistently:
```
Minimum contrast:
- Display: 48-72px
- Heading 1: 32-40px
- Heading 2: 24-28px
- Heading 3: 20-22px
- Body: 16-18px
- Small: 14px
- Caption: 12px
```

### Font Selection
1. Choose primary font (majority of text)
2. Consider secondary font (if contrast needed)
3. Verify: Web-safe or properly loaded?
4. Test: Readable at all intended sizes?

### Refinements
Apply these adjustments:
```
Headlines:
- Reduce letter-spacing (-0.02em to -0.04em)
- Tighten line-height (1.1-1.2)
- Consider: Weight, case, color

Body:
- Optimal line-length (45-75 characters)
- Comfortable line-height (1.5-1.6)
- Sufficient contrast (4.5:1 minimum)

Small text:
- Increase letter-spacing slightly (+0.01em)
- Ensure adequate size (never below 12px)
```

### Exit Criteria
- [ ] Type scale defined with clear hierarchy
- [ ] Font(s) selected and tested
- [ ] Spacing adjustments applied
- [ ] Readable at all sizes

---

## Phase 4: Color

**Goal**: Apply intentional, functional color that enhances meaning.

### Palette Definition
Start with constraints:
```
Primary: 1 color (brand/action)
Neutrals: 1 gray scale (5-7 values)
Accents: 0-2 colors (semantic or emphasis)
Background: 1-2 values (light, dark variants)
```

### Color Assignment
Map colors to functions:
```
Text primary: Darkest neutral
Text secondary: Medium neutral
Background: Lightest neutral or white
Borders: Light neutral (10-20% darker than bg)
Actions: Primary color
Success/Error/Warning: Semantic accents
```

### Contrast Verification
Check all text/background combinations:
```
Body text: 4.5:1 ratio minimum
Large text: 3:1 ratio minimum
UI components: 3:1 ratio minimum
```

### Temperature Alignment
Ensure consistency:
- Warm grays with warm accents
- Cool grays with cool accents
- All colors feel like same family

### Exit Criteria
- [ ] Palette limited and defined
- [ ] Every color has a purpose
- [ ] Contrast ratios verified
- [ ] Temperature is consistent

---

## Phase 5: Space

**Goal**: Create rhythm and breathing room through consistent spacing.

### Spacing Scale
Apply base-unit multiples:
```
With 8px base:
xs: 4px (tight, rare)
sm: 8px (related items)
md: 16px (standard gap)
lg: 24px (section separation)
xl: 32px (major divisions)
2xl: 48px (dramatic separation)
3xl: 64px+ (hero spacing)
```

### Density Adjustment
Based on content type:
```
Dense (data tables, dashboards): 8-16px
Standard (articles, forms): 16-24px
Spacious (marketing, heroes): 32-64px
```

### White Space Audit
1. Is there enough space around focal elements?
2. Can sections "breathe"?
3. Is density consistent throughout?
4. Would more space improve clarity?

### Alignment Verification
Check every element:
- Aligned to grid?
- Consistent with neighbors?
- Optical adjustments where needed?

### Exit Criteria
- [ ] Spacing scale applied consistently
- [ ] Density appropriate for context
- [ ] Generous white space in key areas
- [ ] All elements properly aligned

---

## Phase 6: Polish

**Goal**: Add refinements that elevate from good to exceptional.

### Depth & Shadow
Apply subtle dimension:
```
None: Flat design, borders only
Subtle: 0 1px 3px rgba(0,0,0,0.08)
Medium: 0 4px 6px rgba(0,0,0,0.1)
Prominent: 0 10px 25px rgba(0,0,0,0.15)
```

### Border & Corner
Establish consistent treatment:
```
Border: 1px solid [light neutral] or none
Radius: 0 (sharp) | 4px | 8px | full (pills)
Apply: Same radius to all similar elements
```

### Micro-Details
Consider these refinements:
- [ ] Icon weight matches text weight
- [ ] Dividers are subtle, not dominant
- [ ] Interactive elements have clear states
- [ ] Focus states are visible and consistent

### Animation (if applicable)
Keep functional and subtle:
```
Duration: 150-200ms for micro, 300ms for layout
Easing: ease-out (appear), ease-in-out (movement)
Properties: opacity, transform (scale, translate)
```

### Exit Criteria
- [ ] Depth applied consistently
- [ ] Corners and borders unified
- [ ] Details refined throughout
- [ ] Nothing feels unfinished

---

## Phase 7: Audit

**Goal**: Final verification against excellence standards.

### Visual Scan
View output at arm's length:
1. Is hierarchy immediately clear?
2. Does eye flow naturally?
3. Any element fighting for attention?
4. Anything feel out of place?

### Detail Review
Zoom in and verify:
1. Alignment pixel-perfect?
2. Spacing mathematically consistent?
3. Colors exactly as specified?
4. Typography properly refined?

### Checklist Verification
Run through interrogation-checklist.md:
- [ ] Typography ✓
- [ ] Color ✓
- [ ] Layout ✓
- [ ] Hierarchy ✓
- [ ] Content ✓
- [ ] Polish ✓

### Final Questions
Answer honestly:
1. Would a professional designer approve this?
2. Does it look hand-crafted, not generated?
3. Is every element intentional?
4. Does it serve its purpose excellently?

### Exit Criteria
- [ ] Visual scan passes
- [ ] Details verified
- [ ] Checklist complete
- [ ] Final questions answered "yes"

---

## Quick Elevation Checklist

For rapid passes, verify in order:

1. **Content**: Essential only, clear hierarchy
2. **Grid**: Consistent base unit, aligned
3. **Type**: Clear scale, refined spacing
4. **Color**: Limited palette, functional assignment
5. **Space**: Generous, rhythmic, consistent
6. **Details**: Shadows, borders, corners unified
7. **Overall**: Feels professional and intentional
