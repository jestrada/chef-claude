# Chef Claude

A personal recipe standardization system that transforms inconsistent cookbook recipes into a unified, personalized format optimized for my cooking style and kitchen setup.

## Why This Project?

Too often, cookbooks present recipes in wildly different formats - some lack detail, others use inconsistent measurements, and many assume ingredients or techniques that don't match my kitchen reality. I love how NYT Cooking recipes are formatted, but even they sometimes need customization.

This system lets me take any recipe from any cookbook and reformat it to include:

- **Local ingredient availability** - swap items I can't find locally
- **Personal equipment context** - adjust for my specific tools and kitchen setup
- **Historical and cultural context** - add interesting background about the dish's origins
- **Detailed techniques** - include the level of instruction detail that works for me
- **Consistent formatting** - every recipe follows the same clear, printable layout

The result: an entire cookbook becomes accessible and usable, with my personal touches and references built right in.

## Structure

Each recipe is organized in its own folder containing:
- HTML file (main formatted recipe for viewing/printing)
- Original source files (PDFs, images, etc.)
- Any additional assets

## Template

Use `recipe-template.html` as a starting point for new recipes. The template provides:
- Clean, printable layout inspired by NYT Cooking
- Side-by-side title/image layout with full-width description
- Two-column format (ingredients + preparation)
- Responsive design for mobile viewing
- Arial font with optimized line spacing for readability

Follow the recipe writing guidelines in `CLAUDE.md` for consistent, high-quality recipes that include:
- Compelling headnotes with dish backstory
- Descriptive sensory cues for cooking success
- Practical timing and equipment details
- Named steps with time estimates
- Substitution suggestions and accessibility notes

## Current Recipes

- **Lemon Pepper Zucchini Pasta with Dill** - Modified version with added chicken
  - Based on Yewande Komolafe's NYT recipe
  - Added protein and cooking optimizations
  - Serves 4, ~35 minutes total time

## Workflow

1. **Collect**: Find a recipe from any cookbook, website, or source
2. **Extract**: Use the source material to gather ingredients and instructions
3. **Standardize**: Apply consistent formatting using the template and style guide
4. **Personalize**: Adapt ingredients, add context, adjust techniques for my kitchen
5. **Format**: Create clean HTML for easy viewing and printing

## Built with Claude Code

This entire system was built in under an hour using [Claude Code](https://claude.ai/code), demonstrating how AI can accelerate creative projects beyond traditional software development. From designing the template to establishing style guidelines, Claude Code helped rapidly prototype and iterate on this recipe standardization workflow.

Claude Code excels at creative, organizational projects like this - transforming ideas into functional systems that solve real personal productivity challenges.

## Technical Notes

- Recipes are formatted for personal use and reference
- HTML files can be opened directly in any browser
- Print-friendly styling optimized for recipe cards
- All attribution preserved for source materials
- Uses Arial font and NYT-inspired layout for readability
