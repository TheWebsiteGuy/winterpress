# WinterPress

A custom WinterCMS starter template that includes additional plugins for a more WordPress like experience out-of-the-box.

## Winter Plugins

This theme installs some first party plugins provided by the Winter team:

- [Winter.Pages](https://github.com/wintercms/wn-pages-plugin) - Client friendly static page management.
- [Winter.Blog](https://github.com/wintercms/wn-blog-plugin) - Robust blogging platform.
- [Winter.Blocks](https://github.com/wintercms/wn-blocks-plugin) - Provides a "block based" content management experience.
- [Winter.Search](https://github.com/wintercms/wn-search-plugin) - Full-text search integration based on Laravel Scout.
- [Winter.SEO](https://github.com/wintercms/wn-seo-plugin) - Easily manage SEO metadata.
- [Winter.Sitemap](https://github.com/wintercms/wn-sitemap-plugin) - Manages sitemap.xml definitions.

## How to install

From root of project, run:

1. Download theme
```bash
composer require thewebsiteguy/wn-winterpress-theme
```

2. Install dependencies
```bash
php artisan vite:install
````

3. Run build to create dist
```bash
php artisan vite:compile theme-winterpress
````

### Vite watch

When devoloping, run vite watch to monitor changes and hot reload in browser
```bash
php artisan vite:watch theme-winterpress
````