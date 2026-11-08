# claude-d3js-skill

A Claude Code skill for building custom, interactive data visualizations with D3.js.

## Overview

D3.js provides fine-grained control over data-driven documents and SVG graphics. This skill helps create bespoke charts, network diagrams, geographic visualizations, interactive explorations, and animated graphics across vanilla JavaScript and modern frontend frameworks.

It is especially useful when a standard charting library cannot express the required visual encoding or interaction.

## Main Capabilities

- Bind structured data to DOM and SVG elements.
- Build custom chart types.
- Create network and graph visualizations.
- Implement hierarchical layouts.
- Build geographic maps and projections.
- Add pan, zoom, brush, and selection interactions.
- Create animated transitions.
- Integrate D3 with React, Vue, Svelte, or vanilla JavaScript.
- Select appropriate scales, axes, and color systems.

## When to Use D3

Use D3 when the visualization needs custom layout, visual encoding, interaction, or transitions. For standard dashboards with common charts, a simpler charting library may be faster to implement and maintain.

## Installation

Install D3 in the target JavaScript project:

```bash
npm install d3
```

Install the skill:

```bash
git clone https://github.com/Brajesh31/claude-d3js-skill.git ~/.claude/skills/d3js
```

## Usage

Invoke the skill for custom visualization work:

```text
/d3js
```

Provide the data schema, chart purpose, target framework, expected interactions, and display constraints.

## Core Workflow

1. Inspect the data and identify the intended visual question.
2. Choose an appropriate chart or layout.
3. Define scales and visual encodings.
4. Create SVG or canvas elements.
5. Bind data and render marks.
6. Add axes, labels, and legends.
7. Implement interactions and transitions.
8. Handle resizing and responsive behavior.
9. Validate accessibility and performance.
10. Test with realistic and edge-case data.

## Repository Assets

The repository includes reusable templates and reference material:

- `assets/chart-template.jsx`: Starting structure for chart components.
- `assets/interactive-template.jsx`: Starting structure for interactive visualizations.
- `assets/sample-data.json`: Sample data for experimentation.
- `references/d3-patterns.md`: Common D3 implementation patterns.
- `references/scale-reference.md`: Scale selection and configuration.
- `references/colour-schemes.md`: Color and palette guidance.

## Design Checklist

- Chart type matches the analytical question.
- Scales reflect the data distribution.
- Axes and labels are understandable.
- Color encodes meaning consistently.
- Interactions are discoverable and reversible.
- Tooltips provide useful context.
- Layout works at the intended viewport sizes.
- Large datasets are rendered efficiently.
- Empty, missing, and invalid values are handled.
- Visual output is checked with realistic data.

## Repository Contents

- `SKILL.md`: Main D3 visualization workflow.
- `assets/`: Chart templates and sample data.
- `references/`: Patterns, scales, and color guidance.
- `README.md`: Installation and visualization guidance.

## Practical Principle

Start with the analytical question, not the chart type. A visually impressive visualization is still a failure if it obscures the pattern users need to understand.
