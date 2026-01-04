# Features Document

A mobile-friendly documentation that can be shared via GitHub Pages.

## Quick Start

### For GitHub Pages:

1. **Create a new repository** on GitHub (or use an existing one)

2. **Push the SupplyFlow directory** to your repository:
   ```bash
   cd SupplyFlow
   git init
   git add .
   git commit -m "Add SupplyFlow features documentation"
   git remote add origin https://github.com/[your-username]/[repo-name].git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository Settings
   - Navigate to Pages section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/docs" folder
   - Click Save

4. **Access your site** at:
   `https://[your-username].github.io/[repo-name]/`

### For Local Development:

```bash
cd SupplyFlow/docs
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000` in your browser.

## File Structure

```
docs/
├── _config.yml      # Jekyll configuration
├── Gemfile          # Ruby dependencies
├── index.md         # Main documentation content
└── README.md        # Setup instructions
```

## Mobile Optimization

The documentation is automatically optimized for mobile devices with:
- ✅ Responsive layout
- ✅ Touch-friendly interface
- ✅ Fast page loads
- ✅ Clean typography
- ✅ Easy navigation

## Customization

Edit `docs/index.md` to add or modify content. The Jekyll theme will automatically format it for web and mobile viewing.

