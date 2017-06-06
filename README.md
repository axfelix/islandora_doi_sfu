# Islandora DOI DataCite Resource Types

## Overview

Module that customizes the Islandora DOI DataCite module by providing a select list of DataCite 'resourceType' values. Originally written at the request of the managers of Simon Fraser University's [Radar Research Data Repository](https://researchdata.sfu.ca/).

This module is not an Islandora DOI Framework submodule, it simply implements standard Drupal API techniques (specifically, `hook_form_alter()` and a custom theme preprocess override) to allow a user to select a value instead of having the value assigned automatically.

## Requirements

* [Islandora DOI Framework](https://github.com/mjordan/islandora_doi_framework)
* [Islandora DOI DataCite](https://github.com/mjordan/islandora_doi_framework/tree/7.x/modules/islandora_doi_datacite)

## Installation

Same as for any other Drupal module.

## Configuration

This module does not have any configuration options.

## Maintainer

* [Mark Jordan](https://github.com/mjordan)

## Development and feedback

Pull requests are welcome, as are use cases and suggestions. Please open an issue in this Github repository.

## License

 [GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)

