# Antway Dependency Map

A standalone, GitHub Pages-ready interactive visualization of the Antway Singapore project's task dependencies and delay causality analysis.

## Features

- **Bilingual Support**: Toggle between English (EN) and Japanese (JP)
- **Interactive Visualization**: SVG-based task dependency graph with critical path highlighting
- **Delay Analysis**: Summary statistics showing total delays, maximum delays, critical tasks, and newly added tasks
- **Task Details**: Comprehensive task list with status indicators, assignees, and delay information
- **7-Phase Project Timeline**:
  - Phase 0: Handover & Regulatory Approval
  - Phase 1: Demolition & Removal
  - Phase 2: Floor Works (Critical Path)
  - Phase 3: Walls, Ceiling & Doors
  - Phase 4: MEP Systems
  - Phase 5: Plumbing & Electrical
  - Phase 6: Kitchen Equipment
  - Phase 7: Finishing & Handover

## Technology Stack

- **React 18**: From unpkg.com CDN
- **React DOM 18**: From unpkg.com CDN
- **Babel Standalone**: For JSX transformation in the browser
- **Vanilla CSS**: Minimal styling with dark theme

## File Structure

```
antway-dependency-map/
├── index.html          # Standalone, self-contained application
└── README.md           # This file
```

## How to Use

### Local Development
1. Open `index.html` directly in a modern web browser
2. No build process or server required
3. All dependencies are loaded from CDN

### GitHub Pages Deployment
1. Push this directory to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Select the root directory as the source
4. Access your site at `https://yourusername.github.io/antway-dependency-map/`

## Project Data

The visualization includes:
- **28 Tasks** spanning 7 project phases
- **Realistic delay data** comparing January 12 and February 6 timelines
- **Critical path** highlighting to identify blocking dependencies
- **Root cause analysis** for delays across multiple dimensions

### Delay Summary (JAN12 → FEB6)
- Total Project Delay: 324 days
- Maximum Single Task Delay: 17 days (Chiller Installation)
- Critical Delay Tasks: 5 tasks
- Newly Added Tasks: 8 tasks since JAN12

### Root Causes (Top 3)
1. Floor works chain cascade
2. 3rd-party contractor dependency
3. Scope expansion (+8 tasks)

## Task Status Indicators

- **Green**: Done
- **Blue**: In Progress
- **Orange**: Delayed
- **Red**: Critical Delay
- **Gray**: Not Started

## Language Support

Click the language toggle button in the top-right corner to switch between:
- **English (EN)**: Project details, phases, and task names in English
- **日本語 (JP)**: Full Japanese translation including all UI elements

## Browser Compatibility

Works on all modern browsers that support:
- ES6+ JavaScript
- React 18
- SVG rendering
- CSS Grid and Flexbox

## File Size

- `index.html`: ~23 KB (fully self-contained)
- No external asset files required

## Notes

- All data is embedded directly in the HTML file
- No database or backend required
- All React components are defined inline
- CDN dependencies ensure consistent performance

## License

Internal project documentation for Antway Singapore.

---

**Project**: 28 Tai Seng Ave #04-03
**Generated**: February 2025
**Analysis Period**: JAN12 → FEB6
