<div align="center">
  <img src="assets/ChefClaude.jpg" alt="Chef Claude Logo" width="200">
  
  # Chef Claude
  
  A personal recipe standardization system that transforms inconsistent cookbook recipes into a unified, personalized format optimized for my cooking style and kitchen setup.
</div>

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

## Quick Start (3 Simple Steps)

1. **Create a directory** for your recipe (e.g., `chicken-parmesan`)
2. **Add your source files** to that directory:
   - Photo of the finished dish
   - Image or PDF of the original recipe
   - (At least one image file is required)
3. **Run the script**: `./bin/create-recipe chicken-parmesan`

That's it! Claude Code will examine your files, extract the recipe details, and create a beautifully formatted HTML recipe following the established style guidelines.

## Use This System Yourself

Want to standardize your own recipe collection? Clone this repository:

```bash
git clone https://github.com/jestrada/chef-claude.git
cd chef-claude
```

Then follow the Quick Start steps above. The system works with any recipe source - cookbooks, websites, handwritten notes, or photos. Just make sure you have [Claude Code](https://claude.ai/code) installed.

## Current Recipes

- **Greek Fisherman's Soup** - Traditional Mediterranean seafood soup
- **Moussaka** - Classic Greek layered casserole with eggplant and béchamel  
- **Spanakorizo** - Greek spinach rice comfort food
- **Lemon Pepper Zucchini Pasta with Dill** - Modern pasta with miso butter sauce

## Built with Claude Code

This entire system was built in under an hour using [Claude Code](https://claude.ai/code), demonstrating how AI can accelerate creative projects beyond traditional software development. From designing the template to establishing style guidelines, Claude Code helped rapidly prototype and iterate on this recipe standardization workflow.

Claude Code excels at creative, organizational projects like this - transforming ideas into functional systems that solve real personal productivity challenges.

## Technical Notes

- Recipes are formatted for personal use and reference
- HTML files can be opened directly in any browser
- Print-friendly styling optimized for recipe cards
- All attribution preserved for source materials
- Uses Arial font and NYT-inspired layout for readability
