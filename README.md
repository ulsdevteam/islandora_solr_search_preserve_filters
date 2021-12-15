# Islandora Solr Search Preserve Filters

## Overview

Enhances the [Islandora Solr Search module](https://github.com/Islandora/islandora_solr_search/) to force the "Advanced Search" option "Preserve Filters" to default as "on".

## Requirements

This module requires an [Islandora 7.x installation](https://islandora.ca/), and the Islandora Solr Search module.

## Description

In the Islandora Solr Search module, under the Advanced Search configuration, there is an option "Preserve Filters".  This presents a UI option to the user which allows the selected Solr filters to be preserved when the Advanced Search is edited and re-run.  This UI option is exposed to the user, with the default value as unset.

When enabled, this module changes the default value to set, turning *on* the functionality by default.

## Copyright and License

Copyright University of Pittsburgh.

Licensed under GPL v2 or later.
