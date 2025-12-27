# Contributing to Awesome Learning

Thank you for considering contributing to Awesome Learning! This guide will help you add valuable resources to our curated collection.

## How to Contribute

### Adding a Resource

1. **Fork the repository** and create a new branch for your contribution
2. **Choose the appropriate file** from `docs/frameworks/` or `docs/languages/`
3. **Add your resource** following the format below
4. **Test locally** to ensure formatting is correct
5. **Submit a pull request** with a clear description

### Resource Format

Each resource should follow this format:

```markdown
- [Resource Name](URL) - Brief description of what this resource offers (8-25 words)
```

**Example:**
```markdown
- [Vite](https://vitejs.dev/) - Next generation frontend tooling with instant server start and lightning-fast HMR
```

### Resource Quality Standards

Resources should be:

- **Actively Maintained**: Updated within the last 12 months
- **Well Documented**: Has clear documentation or README
- **Community Adopted**: Popular in the community (good GitHub stars, npm downloads, etc.)
- **Production Ready**: Stable and suitable for real projects
- **Unique Value**: Offers something distinct from existing entries

### Category Guidelines

- Place resources in the most appropriate category
- If a resource fits multiple categories, choose the primary use case
- Suggest new categories in your PR if existing ones don't fit
- Keep resources within each category ordered from beginner-friendly to advanced

### Before Submitting

Run these commands to ensure your contribution meets our standards:

```bash
# Install dependencies
pnpm install

# Check formatting
pnpm run format:check

# Run linting
pnpm run lint

# Build CSS and test locally
pnpm run dev
```

### Pull Request Guidelines

- **Title**: Use descriptive titles like "Add Zustand to React state management"
- **Description**: Briefly explain why this resource is valuable
- **One PR per resource**: Keep PRs focused (unless adding multiple related items)
- **Check for duplicates**: Search existing content to avoid duplicates

## What We're Looking For

### High Priority
- Modern, actively maintained tools
- Official documentation and learning resources
- Popular community-recommended libraries
- Tools with excellent developer experience

### Lower Priority
- Deprecated or unmaintained projects
- Very niche tools with limited adoption
- Resources that duplicate existing entries
- Promotional or commercial-only content

## Suggesting Improvements

Beyond adding resources, you can also:

- Fix typos or formatting issues
- Improve descriptions for clarity
- Suggest reorganization of categories
- Report broken links
- Propose new technology categories

## Code of Conduct

Please note that this project follows a [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold this code.

## Questions?

If you have questions about contributing, feel free to:
- Open an issue for discussion
- Check existing issues and PRs for similar topics
- Reach out to maintainers

Thank you for helping make Awesome Learning better!
