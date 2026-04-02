# foxxprompt 10x Improvement Design

## Overview

Transform foxxprompt from a basic form-to-markdown tool into a professional prompt engineering platform that generates AI-optimized prompts using proven frameworks.

## Design Decisions

### Framework: COSTAR + Context Injection

**Primary Structure:** Use COSTAR framework as backbone:
- **C**ontext - Background and situation
- **O**bjective - What to achieve
- **S**tyle - How to respond
- **T**one - Emotional register
- **A**udience - Who it's for
- **R**esponse Format - Output structure

**Enhancement:** Layer intelligent context injection - automatically add best-practice elements based on prompt type.

---

## Section 1: Visual & UX (10x Improvement)

### Changes:
- Modern dark theme with orange accent (keep fox theme)
- Animated gradients, subtle glow effects
- Card-based layout instead of plain sections
- Type selector as sleek toggle pills
- Real-time preview with syntax highlighting
- Smooth transitions between types
- Mobile responsive

### Layout:
- Left: Fixed sidebar with form (40% width)
- Right: Live preview panel (60% width)
- Floating action bar for copy/save/share

---

## Section 2: Features (10x Improvement)

### New Features:
1. **Preset Templates** - Pre-built prompts for common tasks
2. **One-click Examples** - Fill form with example values
3. **Variable System** - `{{variable}}` syntax for dynamic prompts
4. **Prompt History** - LocalStorage saves last 10 prompts
5. **Export Options** - Copy as markdown, JSON, or plain text
6. **Dark/Light Mode** - System preference detection

### Type-Specific Enhancements:

**Code:**
- Auto-inject: file headers, error handling, security, testing requirements
- Framework-specific templates (React, Node, Python, etc.)
- Code style options (functional, OOP, concise, detailed)

**Image:**
- Auto-inject: lighting specs, composition rules, negative prompts
- Aspect ratio presets (16:9, 1:1, 9:16, 4:3)
- Quality modifiers (8K, detailed, masterwork)

**Writing:**
- Auto-inject: readability level, structure templates
- Format presets (blog, docs, email, social)
- Tone presets (professional, casual, witty)

**Video:**
- Auto-inject: pacing guidelines, transition suggestions
- Duration presets (short, medium, long form)
- Platform presets (YouTube, TikTok, Instagram)

---

## Section 3: Output Quality (10x Improvement)

### Prompt Generation Algorithm:

```
1. COSTAR Base Structure
   - Context from user input + auto-injected defaults
   - Objective from main_idea
   - Style from type-specific best practices
   - Tone from user selection
   - Audience from input
   - Response Format from output needs

2. Intelligent Injection
   - Add type-specific best practices
   - Include "do/don't" constraints
   - Add quality checklist

3. AI-Optimized Formatting
   - Use clear delimiters (###, ---)
   - Structured bullet hierarchies
   - Explicit section markers
   - Include examples where helpful
```

### Quality Checklist Per Type:

**Code:**
- Modular, well-documented
- Error handling
- Security considerations
- Performance optimization
- Accessibility

**Image:**
- Composition balance
- Lighting coherence
- Style consistency
- High detail
- No artifacts

**Writing:**
- Clear structure
- Consistent tone
- Audience-appropriate
- All key points covered

**Video:**
- Clear narrative
- Smooth pacing
- Audio-visual sync
- Platform optimization

---

## Section 4: Implementation Details

### Files Changed:
- `foxxprompt.html` - Complete rewrite with all improvements

### Technical Approach:
- Single HTML file (no dependencies)
- Vanilla JavaScript
- LocalStorage for history
- CSS variables for theming
- No external fonts (system fonts only)

### Success Criteria:
1. Prompts follow COSTAR structure
2. Each type auto-injects relevant best practices
3. UI is visually stunning with smooth animations
4. Mobile responsive
5. Copy/save functionality works
6. History saves between sessions