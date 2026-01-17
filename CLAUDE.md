# Shopware 6 Category Duplicator

## Project Overview

A Shopware 6 plugin that allows duplicating full category subtrees via right-click context menu in the admin panel.

## Tech Stack

- PHP (Shopware 6 plugin)
- Shopware 6.6.x (use 2.x branch for Shopware 6.4)
- PSR-4 autoloading under `iMidiCategoryDuplicator` namespace

## Project Structure

- `src/` - Plugin source code
- `composer.json` - Plugin dependencies and metadata

## Development

### Installation

```bash
composer require imi/shopware6-category-duplicator
bin/console plugin:refresh
bin/console plugin:install -a iMidiCategoryDuplicator
```

### Testing

After making changes, rebuild SEO URL indices at `/admin#/sw/settings/cache/index`.

## Notes

- SEO URLs are not automatically generated for copied categories
- Check GitHub issues for known problems
