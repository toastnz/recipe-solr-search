## Silverstripe Recipe Solr search

[![CI](https://github.com/silverstripe/recipe-solr-search/actions/workflows/ci.yml/badge.svg)](https://github.com/silverstripe/recipe-solr-search/actions/workflows/ci.yml)
[![Silverstripe supported module](https://img.shields.io/badge/silverstripe-supported-0071C4.svg)](https://www.silverstripe.org/software/addons/silverstripe-commercially-supported-module-list/)

This Silverstripe CMS Recipe is designed to enable Solr-based fulltext search. It's specifically designed to work with Silverstripe Cloud Platforms, but may be functional in other environments as well. It's the successor of [`cwp/cwp-recipe-search`](https://github.com/silverstripe/cwp-recipe-search).

This includes the following core Silverstripe modules:

 * [cwp/cwp-search](https://github.com/silverstripe/cwp-search): CWP fulltextsearch integration module
 * [silverstripe/fulltextsearch](https://github.com/silverstripe/silverstripe-fulltextsearch): Adds external full text
   search engine support to SilverStripe, specically with Solr in a CWP context
 * [symbiote/silverstripe-queuedjobs](https://github.com/symbiote/silverstripe-queuedjobs): A module that provides
   interfaces for scheduling jobs for certain times

You can also opt in to install the following suggested (not required) modules:

 * [silverstripe/textextraction](https://github.com/silverstripe/silverstripe-textextraction): Text Extraction API for
   Silverstripe CMS (mostly used with 'fulltextsearch' module)

This can be either added to an existing project or used as a project base for creating a Silverstripe CMS install.

## Get started

You can create a project using Composer:

```
composer create-project silverstripe/recipe-solr-search ./myproject ^2
```

## Alternative

This recipe is still supported. However, you may wish to explore the [`silverstripe/silverstripe-search-service`](https://github.com/silverstripe/silverstripe-search-service) module which uses a _search-as-a-service_ approach compatible with providers such as Elastic or Algolia.

## More information

See the [recipe plugin](https://github.com/silverstripe/recipe-plugin) page for instructions on how
Silverstripe recipes work.
