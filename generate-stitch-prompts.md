Here's the fully revised version of your `generate-Stich-prompt.md`:

---

# Stitch UI Design Prompt Generator Template

This template helps you generate comprehensive UI design prompts for [Stitch](https://stitch.withgoogle.com) by Google Labs, specifically crafted to avoid defaulting to Google's Material Design style. Fill in the **required** sections and any **optional** sections that apply to your project. The output will be a complete Stitch prompt ready to use.

**Why use this template?**
By default, Stitch tends to produce Material Design-style interfaces. This template helps you break free from that aesthetic and create truly unique designs aligned with your brand vision.

---

## Before You Start

**Prerequisites:**
- A clear idea of your app's purpose and main features
- Basic understanding of your target users
- 30-60 minutes to thoughtfully complete this template

**What you'll get:**
- A comprehensive design prompt for Stitch
- Consistent design direction for your development team
- A reference document for future design decisions

---

## PART 1: Project Foundation (Required)

### Basic Information
```markdown
APP_NAME: [Your app/website name]

PURPOSE: [What does your app do? 1-2 sentences]

PLATFORM: [Web / Mobile App / Desktop / Progressive Web App]

PRIMARY_VIEWPORT: [e.g., Mobile-first (375px) / Desktop-first (1440px) / Tablet (768px)]
```

### Core Functionality
```markdown
KEY_FEATURES: [List 3-7 main features users will interact with]
- Feature 1
- Feature 2
- Feature 3
...

USER_ACTIONS: [What are the primary actions users perform?]
- Action 1
- Action 2
- Action 3
...
```

### Required Screens
```markdown
SCREENS_TO_DESIGN: [List all screens/pages you need designed, minimum 3]
1. Screen Name - [Brief description of what happens on this screen]
2. Screen Name - [Brief description]
3. Screen Name - [Brief description]
...

Example:
1. Onboarding - User sets up account and provides initial configuration
2. Dashboard - Main interface showing overview of user data
3. Detail View - Deep dive into specific item with actions
```

---

## PART 2: Design Direction (Required)

### Brand Personality
```markdown
BRAND_ADJECTIVES: [Choose 3-5 adjectives that describe your brand]
Examples: Modern, Professional, Playful, Minimal, Bold, Trustworthy, Innovative, Friendly, Sophisticated, Approachable

Your choices:
- [Adjective 1]
- [Adjective 2]
- [Adjective 3]
...

TARGET_AUDIENCE: [Who will use this? Their characteristics]
Example: Tech-savvy professionals aged 25-45, mobile-heavy users, value efficiency
```

### Design Constraints
```markdown
MUST_AVOID: [What design styles/patterns to explicitly avoid]
- Material Design (Google's default style)
- [Any other styles to avoid]
...

MUST_INCLUDE: [Any non-negotiable design requirements]
Example: Accessibility compliance, dark mode, specific interaction patterns
- [Requirement 1]
- [Requirement 2]
...
```

---

## PART 3: Visual Identity (Optional but Recommended)

### Color Preferences
```markdown
COLOR_DIRECTION: [Optional - Describe your color preferences]
Examples:
- "Dark theme with vibrant accent colors"
- "Soft pastels with high contrast for readability"
- "Monochromatic with single bold accent"
- "Warm earth tones"

Your direction: [Fill in or leave empty]

SPECIFIC_COLORS: [Optional - Any specific colors to use or avoid]
- Primary: [Color or "surprise me"]
- Accent: [Color or "surprise me"]
- Background: [Color or "surprise me"]
- Avoid: [Colors to avoid, if any]
```

### Typography Preferences
```markdown
TYPOGRAPHY_STYLE: [Optional - What feeling should the text convey?]
Examples: "Clean and readable", "Bold and impactful", "Elegant and refined", "Technical and precise"

Your style: [Fill in or leave empty]

FONT_PREFERENCES: [Optional - Any specific direction for fonts?]
Examples: "Sans-serif only", "Mix of serif headings and sans body", "Monospace for technical feel"

Your preference: [Fill in or leave empty]
```

### Visual Style References
```markdown
DESIGN_INSPIRATION: [Optional - Reference other products/styles for inspiration]
NOTE: These are for inspiration only, not to copy. Format: "Product name - what aspect inspires you"

Examples:
- "Linear - clean, dark interface with subtle animations"
- "Stripe - professional, clear information hierarchy"
- "Notion - friendly, approachable, lots of white space"
- "Apple - minimal, elegant, focus on content"

Your references:
- [Reference 1 - what you like about it]
- [Reference 2 - what you like about it]
...
OR: [Leave empty for completely original design]
```

### Unique Visual Elements
```markdown
SIGNATURE_ELEMENTS: [Optional - Any unique visual motifs or metaphors?]
Examples: "Use data visualization as recurring motif", "Incorporate paper/document metaphors", "Audio waveforms throughout"

Your elements: [Fill in or leave empty]

INTERACTION_STYLE: [Optional - How should interactions feel?]
Examples: "Smooth and fluid", "Snappy and responsive", "Playful with micro-interactions", "Minimal and subtle"

Your style: [Fill in or leave empty]
```

---

## PART 4: Technical Specifications (Optional)

### Component Requirements
```markdown
SPECIAL_COMPONENTS: [Optional - Any complex UI components needed?]
Examples: "Data tables with sorting/filtering", "Real-time chat interface", "Audio/video player", "Interactive charts"

Your components:
- [Component 1]
- [Component 2]
...
OR: [Leave empty if standard components suffice]
```

### State Variations
```markdown
CRITICAL_STATES: [Optional - Important UI states to show]
Examples: Loading, empty states, error states, success confirmations

Your states:
- [State 1]
- [State 2]
...
OR: [Leave empty for standard states]
```

### Responsive Behavior
```markdown
BREAKPOINT_PRIORITIES: [Optional - If multi-device, specify adaptation priorities]
Example: "Mobile-first, desktop should show more data in parallel columns"

Your priorities: [Fill in or leave empty]
```

---

## PART 5: Output Preferences (Optional)

### Deliverables
```markdown
DESIGN_SYSTEM_NEEDED: [Yes / No / Optional]
If Yes, specify components needed:
- [Component 1]
- [Component 2]
...

ADDITIONAL_DELIVERABLES: [Optional - Anything else you need?]
Examples: "Icon set", "Illustration style guide", "Animation specifications", "Dark mode variants"

Your requests:
- [Deliverable 1]
- [Deliverable 2]
...
OR: [Leave empty for screens only]
```

---

## OUTPUT: Generated Stitch Prompt

Once you've filled in the template above, use this structure to generate your final prompt:

````markdown
You are designing the user interface for "[APP_NAME]", a [PLATFORM] application for [PURPOSE].

DESIGN CONSTRAINTS:
- Do NOT use Google Material Design or Material 3 styling
- Do NOT use standard Google color palettes, shadows, or component styles
- Create a unique, custom design system tailored to [APP_NAME]'s brand identity
- [PRIMARY_VIEWPORT] approach
- Avoid: [MUST_AVOID items]

BRAND DIRECTION:
- Brand personality: [BRAND_ADJECTIVES]
- Target audience: [TARGET_AUDIENCE]
- [If filled: COLOR_DIRECTION and SPECIFIC_COLORS]
- [If filled: TYPOGRAPHY_STYLE and FONT_PREFERENCES]
- [If filled: SIGNATURE_ELEMENTS and INTERACTION_STYLE]
- Must include: [MUST_INCLUDE items]

[If DESIGN_INSPIRATION is filled:]
STYLE REFERENCES (for inspiration, not copying):
[List each reference]

CORE FUNCTIONALITY:
The app enables users to:
[List KEY_FEATURES]

Primary user actions:
[List USER_ACTIONS]

SCREENS TO DESIGN:
[For each screen in SCREENS_TO_DESIGN, create detailed specification:]

[SCREEN_NUMBER]. [SCREEN_NAME]
- [Screen description]
- Key elements:
  * [Element 1 - derived from features/actions]
  * [Element 2]
  * [Element 3]
- [If SPECIAL_COMPONENTS applies to this screen, list them]
- [If CRITICAL_STATES applies to this screen, specify states to show]
- [PRIMARY_VIEWPORT]-optimized layout

[Repeat for all screens]

DESIGN SYSTEM REQUIREMENTS:
- Define 2-3 primary brand colors [If SPECIFIC_COLORS filled: incorporate those preferences]
- Typography scale (headings, body, captions) [If TYPOGRAPHY_STYLE filled: following [style]]
- Button styles: Primary, Secondary, Tertiary
- Input field styling
- Card/container styling with subtle shadows
- Icon style (outline or filled, but consistent)
- Loading/animation style [If INTERACTION_STYLE filled: that feels [style]]
- Success/error/warning state colors and patterns
- [PRIMARY_VIEWPORT] touch target sizes (minimum 44px for mobile)
- [If DESIGN_SYSTEM_NEEDED: include component library]

UNIQUE VISUAL ELEMENTS TO INCLUDE:
- [SIGNATURE_ELEMENTS if filled]
- Smooth micro-interactions and transitions
- [If COLOR_DIRECTION or TYPOGRAPHY_STYLE filled: incorporate those]
- Custom illustrations for empty states
- Unique iconography related to [app domain]
- [Any style from DESIGN_INSPIRATION that makes sense]

AVOID:
- Google's Material Design ripple effects
- Standard Material elevation/shadow system
- Google Fonts defaults (Roboto, Product Sans)
- Google's primary colors (#4285F4, etc.)
- Material icon set (use custom or alternative icon system)
- [Any additional items from MUST_AVOID]

[If BREAKPOINT_PRIORITIES filled:]
RESPONSIVE BEHAVIOR:
[Detail the responsive priorities]

GENERATE:
High-fidelity mockups for all [number] screens optimized for [PRIMARY_VIEWPORT], with annotations for [other viewport] adaptations. Show [light/dark/both] mode designs. [If DESIGN_SYSTEM_NEEDED: Include a design system component library sheet showing all UI elements used.]

[If ADDITIONAL_DELIVERABLES filled:]
ADDITIONAL DELIVERABLES:
[List each deliverable]

Focus on creating a memorable, unique visual identity that stands apart from typical Google products while maintaining excellent usability and accessibility.
````

---

## Quick Start Checklist

Before generating your prompt, ensure you have:

**Required:**
- [ ] Filled in APP_NAME and PURPOSE
- [ ] Specified PLATFORM and PRIMARY_VIEWPORT
- [ ] Listed KEY_FEATURES (minimum 3)
- [ ] Listed USER_ACTIONS (minimum 3)
- [ ] Defined SCREENS_TO_DESIGN (minimum 3)
- [ ] Selected BRAND_ADJECTIVES (3-5)
- [ ] Described TARGET_AUDIENCE
- [ ] Listed items for MUST_AVOID
- [ ] Listed items for MUST_INCLUDE

**Optional but Recommended:**
- [ ] Defined COLOR_DIRECTION
- [ ] Specified TYPOGRAPHY_STYLE
- [ ] Added DESIGN_INSPIRATION references
- [ ] Described SIGNATURE_ELEMENTS

**Advanced (Optional):**
- [ ] Listed SPECIAL_COMPONENTS
- [ ] Defined CRITICAL_STATES
- [ ] Specified BREAKPOINT_PRIORITIES
- [ ] Requested DESIGN_SYSTEM_NEEDED
- [ ] Added ADDITIONAL_DELIVERABLES

---

## Tips for Best Results

1. **Be Specific in Purpose**: Instead of "task management app", say "collaborative task management for remote teams with real-time updates"

2. **Brand Adjectives Matter**: These heavily influence the final design. "Professional, Trustworthy, Corporate" will yield very different results from "Playful, Bold, Creative"

3. **Visual References Work**: Even 1-2 good references help Stitch understand the aesthetic you're aiming for

4. **Screen Descriptions**: The more detail you provide about what happens on each screen, the better the UI layout will be

5. **Color Direction**: Even vague guidance like "dark theme" or "warm colors" significantly improves results over leaving it blank

6. **Start Simple**: Fill only required fields first, generate, then iterate with optional fields for refinement

7. **Avoid Contradictions**: If you say "minimal" but list 20 features per screen, the results will be confused. Align your adjectives with your requirements

8. **Iterate Based on Results**: Don't expect perfection on first generation. Use Stitch's edit features to refine, or generate new prompts based on what worked/didn't work

9. **Save Your Bananas**: Stitch uses "Nano Bananas 🍌" as credits. Generate strategically rather than repeatedly generating similar prompts

---

## Common Mistakes to Avoid

1. **Being Too Vague**
   - ❌ Bad: "Make it look modern"
   - ✅ Good: "Modern, minimal aesthetic inspired by Linear's clean dark interface with bold accent colors"

2. **Contradictory Requirements**
   - ❌ Bad: Brand adjectives say "minimal" but you list 15 features per screen
   - ✅ Good: Align your feature density with your aesthetic goals

3. **Forgetting the User Flow**
   - ❌ Bad: Listing screens without considering how users navigate between them
   - ✅ Good: "From Task List, users tap a task to see Detail view, then can tap 'Edit' to modify"

4. **Skipping States**
   - ❌ Bad: Only showing the "happy path" with data
   - ✅ Good: Include empty states, loading, errors, and edge cases

5. **Ignoring Platform Conventions**
   - ❌ Bad: Desktop-style interactions on mobile screens
   - ✅ Good: Mobile-first with appropriate touch targets and gestures

---

## Complete Example: TaskFlow App

See how all sections come together for a real project:

### Part 1: Project Foundation

```markdown
APP_NAME: TaskFlow

PURPOSE: A collaborative task management tool for remote teams with real-time updates and minimal friction

PLATFORM: Progressive Web App

PRIMARY_VIEWPORT: Mobile-first (375px)

KEY_FEATURES:
- Create and assign tasks to team members
- Real-time status updates across devices
- File attachments and threaded comments
- Due date tracking with smart notifications
- Visual progress tracking

USER_ACTIONS:
- Create new task with quick-add option
- Assign task to colleague(s)
- Mark task as complete or in-progress
- Add comments and files with drag-drop
- Filter tasks by status, assignee, or due date
- Set reminders and due dates

SCREENS_TO_DESIGN:
1. Task List - Shows all tasks with filters, status indicators, and quick actions
2. Task Detail - Full task view with description, comments, files, and assignment options
3. Create Task - Streamlined form for adding new task with all relevant fields
4. Team Overview - Dashboard showing team members and their current task load
5. Notifications - Central hub for updates and mentions
```

### Part 2: Design Direction

```markdown
BRAND_ADJECTIVES:
- Efficient
- Clean
- Professional
- Collaborative
- Approachable

TARGET_AUDIENCE: Remote teams (5-50 people), project managers, and knowledge workers aged 25-45 who value simplicity over feature bloat. Mobile-heavy users who switch between devices frequently.

MUST_AVOID:
- Material Design (Google's default style)
- Overly colorful or playful aesthetics
- Complex enterprise software appearance
- Skeuomorphic design elements

MUST_INCLUDE:
- Clear status indicators for at-a-glance understanding
- WCAG 2.1 AA accessibility compliance
- Mobile-friendly touch targets (minimum 44px)
- Dark mode support
```

### Part 3: Visual Identity

```markdown
COLOR_DIRECTION: 
Clean dark theme with a single, bold accent color for CTAs and important status indicators. High contrast for readability in various lighting conditions.

SPECIFIC_COLORS:
- Primary: Deep navy or charcoal (not pure black)
- Accent: Vibrant blue or teal (for CTAs and active states)
- Background: Dark gray with subtle texture
- Avoid: Google's standard blue (#4285F4), bright reds (too alarming)

TYPOGRAPHY_STYLE: 
Clean and highly readable with clear hierarchy. Modern sans-serif that feels professional but not corporate.

FONT_PREFERENCES: 
Sans-serif only. Avoid Roboto or Product Sans. Consider Inter, Plus Jakarta Sans, or similar modern alternatives.

DESIGN_INSPIRATION:
- Linear - Clean, dark interface with excellent information hierarchy
- Height - Professional but approachable, great use of white space
- Notion - Friendly, clear interaction patterns
- Slack - Effective use of color for channels/sections

SIGNATURE_ELEMENTS: 
Use subtle gradient overlays on cards for depth. Incorporate circular progress indicators as a recurring motif for task completion.

INTERACTION_STYLE: 
Smooth and fluid with purposeful micro-interactions. Nothing gratuitous—every animation should provide feedback or guide attention.
```

### Part 4: Technical Specifications

```markdown
SPECIAL_COMPONENTS:
- Drag-and-drop task reordering
- Real-time collaboration indicators (showing who's viewing/editing)
- File preview thumbnails
- Inline comment threads
- Smart date picker with natural language input

CRITICAL_STATES:
- Empty state (new user, no tasks yet)
- Loading skeleton screens
- Error states with actionable recovery options
- Success confirmations (task created, assigned, completed)
- Offline mode indication

BREAKPOINT_PRIORITIES: 
Mobile-first design. Desktop version should utilize extra space for multi-column layout (task list + detail view side-by-side) rather than just scaling up mobile design.
```

### Part 5: Output Preferences

```markdown
DESIGN_SYSTEM_NEEDED: Yes

Components needed:
- Buttons (primary, secondary, tertiary, icon)
- Input fields (text, textarea, select, date picker)
- Cards and containers
- Status badges and tags
- Avatar components
- Navigation elements
- Modal and drawer patterns
- Toast notifications

ADDITIONAL_DELIVERABLES:
- Custom icon set for task types and actions
- Dark mode variants for all screens
- Empty state illustrations
- Loading animation specifications
```

---

## Troubleshooting

**Problem**: Stitch still uses Material Design
**Solution**: Add more items to MUST_AVOID, include DESIGN_INSPIRATION references to non-Google products, emphasize "unique visual identity" in your descriptions

**Problem**: Design feels generic
**Solution**: Fill in SIGNATURE_ELEMENTS, add DESIGN_INSPIRATION, be more specific with BRAND_ADJECTIVES (instead of "modern", say "futuristic" or "vintage-inspired")

**Problem**: Too many screens to describe
**Solution**: Group similar screens (e.g., "List views for Projects, Tasks, and Team—all follow the same layout pattern but with different data")

**Problem**: Not sure about color/typography
**Solution**: Leave those sections empty first, generate, then iterate with specific requests based on what Stitch produces

---

## Next Steps

Once you've generated your Stitch mockups:

1. ✅ Export as `.zip` file (includes HTML and images)
2. ✅ Create a `docs/mockups/` folder in your project repository
3. ✅ Extract the Stitch files there
4. ✅ Follow the [main guide](README.md) for setting up Claude Code with your mockups

Your AI coding agent will use these designs as the foundation for development.

---

## License & Attribution

[Add your license here]

When sharing designs generated from this template, attribution to this guide is appreciated but not required.

---

**Version**: 1.0  
**Last Updated**: January 4, 2026  
**Maintained by**: [@RizzoG99](https://github.com/RizzoG99)

---

Perfect! This revised version includes all the improvements we discussed. The guide is now more comprehensive, easier to follow, and provides better practical examples. Ready to commit to your repository! 🚀
