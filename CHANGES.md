# Changelog for django-sphinxdoc

## v2.0.1 – 2019-06-02:

- [BREAKING] Made it work with Django 4.0

## v2.0.0 – 2019-06-02:

- [BREAKING] Minimal supported Python version is 3.6
- [BREAKING] Minimal supported Django version is 2.0

## v1.5.1 – 2016-12-07:

- [FIX] Fix last release

## v1.5.0 – 2016-12-07:

- [CHANGE] Minimal supported Django version is 1.8
- [NEW] Tests with pytest and tox
- [FIX] Refactorings and clean-ups

## v1.4.2 – 2016-10-26:

- [CHANGE] Replaced string URLs with URL objects. Django no longer supports
  strings.

## v1.4.1 – 2016-09-18:

- [CHANGE] Removed support for Django < 1.6
- [CHANGE] Added migrations to ease future upgrades.
- [CHANGE] Updated README.txt with link to online documentation.
- [NEW] Setting SPHINXDOC_BASE_TEMPLATE in settings.py allows overriding
  of the base template used for documentation.
- [FIX] UnicodeDecodeError when editing or creating a new project.

## v1.4 – 2014-12-14:

- [NEW] Support for Python 3 (3.3 and above)

## v1.3 – 2014-03-05:

- [NEW] Projects can now be protected authentication.

## v1.2.1 – 2013-12-20:

- [NEW] Option `--all` to update docs for all projects
- [NEW] Filters for the project admin
- [NEW] Setting: `SPHINXDOC_CACHE_MINUTES`
- [NEW] Setting: `SPHINXDOC_BUILD_DIR`
- [FIX] Titles for generated domain indexes

## v1.2 – 2013-08-11:

- [NEW] I18n and l10n for Spanish and Basque, by Ales Zabala Alava
- [CHANGE] Use class-based views, by Josiah Klassen
- [CHANGE] Migration to Haystack 2, by Andres Riancho
- [FIX] Inclusion of search index template in package, by Mike Shantz

## v1.1 – 2012-04-19:

- [NEW] Support static and download files.
- [NEW] Additional context to search view so that project information is
  available in the template.
- [CHANGE] Updated some templates
- [FIX] Fixed a bug with the updatedoc command and `~` in paths.
- [FIX] Include all module index files.
- [FIX] Improved indexing behaviour
- [FIX] Improved behaviour when building the docs.

## v1.0.0 – 2010-09-11:

- [NEW] Documentation can be searched via Haystack. The new management command
  `updatedoc` imports the JSON files into the database and updates Haystack’s
  search index.
- [CHANGE] Renamed `App` to `Project`.

## v0.3.2 – 2010-03-14:

- [FIX] Fixed a bug in `setup.py`.

## v0.3.1 – 2010-03-11:

- [CHANGE] Repackaging

## v0.3 – 2010-01-06:

- [NEW] Views for images, sources and object inventory

## v0.2 – 2009-12-30:

- [NEW] Documentation, general index and module index work
- [NEW] Basic documentation written

## v0.1 – 2009-12-19:

- [NEW] Initial release
