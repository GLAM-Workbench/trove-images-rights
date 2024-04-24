# trove-images-rights-data

This dataset includes information about the application of licences and rights statements to images by Trove contributors.

These datasets were generated using notebooks in the [trove-images](https://github.com/GLAM-Workbench/trove-images/) repository.

For more information and documentation see the [Trove images rights data](https://glam-workbench.net/trove-images/trove-images-rights-data/) section of the [GLAM Workbench](https://glam-workbench.net).

## Dataset summary
- [rights-on-images.csv](https://github.com/GLAM-Workbench/trove-images-rights-data/raw/main/rights-on-images.csv) (19.6 kB, text/csv)
- [rights-on-out-of-copyright-photos.csv](https://github.com/GLAM-Workbench/trove-images-rights-data/raw/main/rights-on-out-of-copyright-photos.csv) (15.6 kB, text/csv)


## Dataset details

### [rights-on-images.csv](https://github.com/GLAM-Workbench/trove-images-rights-data/raw/main/rights-on-images.csv)

|                |                                                                                                                                                                                                                                                                           |
|:---------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| date harvested | 2024-04-24                                                                                                                                                                                                                                                                |
| file size      | 19.6 kB                                                                                                                                                                                                                                                                   |
| format         | text/csv                                                                                                                                                                                                                                                                  |
| created by     | <a href='https://github.com/GLAM-Workbench/trove-images/blob/master/rights-statements-on-images.ipynb'>The use of standard licences and rights statements in Trove image records</a> ([documentation](https://glam-workbench.net/trove-images/use-of-rights-statements/)) |
| number of rows | 217                                                                                                                                                                                                                                                                       |
| description    | This dataset lists the number of images with each rights statement from organisations contributing to Trove.                                                                                                                                                              |
| license        | [CC0 Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/)                                                                                                                                                                                        |

#### Columns

| name                               | type    | description                                        |
|:-----------------------------------|:--------|:---------------------------------------------------|
| `id`                               | string  | contributor identifier                             |
| `full_name`                        | string  | contributor name                                   |
| `Free/CC Public Domain`            | integer | Number of images with CC Public Domain declaration |
| `Free/CC BY`                       | integer | Number of images with CC BY licence                |
| `Free/CC0`                         | integer | Number of images with CC0 licence                  |
| `Free/RS NKC`                      | integer | Number of images with RS NKC rights statement      |
| `Free with conditions/CC BY-SA`    | integer | Number of images with CC BY-SA licence             |
| `Free with conditions/CC BY-NC`    | integer | Number of images with CC BY-NC licence             |
| `Free with conditions/CC BY-NC-ND` | integer | Number of images with CC BY-NC-ND licence          |
| `Free with conditions/CC BY-NC-SA` | integer | Number of images with CC BY-NC-SA licence          |
| `Free with conditions/InC-EDU`     | integer | Number of images with InC-EDU rights statement     |
| `Restricted/RS InC`                | integer | Number of images with RS InC rights statement      |
| `Restricted/RS InC-RUU`            | integer | Number of images with RS InC-RUU rights statement  |
| `Restricted/RS CNE`                | integer | Number of images with RS CNE rights statement      |
| `Restricted/RS UND`                | integer | Number of images with RS UND rights statement      |

### [rights-on-out-of-copyright-photos.csv](https://github.com/GLAM-Workbench/trove-images-rights-data/raw/main/rights-on-out-of-copyright-photos.csv)

|                |                                                                                                                                                                                                                                                                           |
|:---------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| date harvested | 2024-04-24                                                                                                                                                                                                                                                                |
| file size      | 15.6 kB                                                                                                                                                                                                                                                                   |
| format         | text/csv                                                                                                                                                                                                                                                                  |
| created by     | <a href='https://github.com/GLAM-Workbench/trove-images/blob/master/rights-statements-on-images.ipynb'>The use of standard licences and rights statements in Trove image records</a> ([documentation](https://glam-workbench.net/trove-images/use-of-rights-statements/)) |
| number of rows | 172                                                                                                                                                                                                                                                                       |
| description    | This dataset lists the number of out-of-copyright photographs with each rights statement from organisations contributing to Trove.                                                                                                                                        |
| license        | [CC0 Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/)                                                                                                                                                                                        |

#### Columns

| name                               | type    | description                                        |
|:-----------------------------------|:--------|:---------------------------------------------------|
| `id`                               | string  | contributor identifier                             |
| `full_name`                        | string  | contributor name                                   |
| `Free/CC Public Domain`            | integer | Number of images with CC Public Domain declaration |
| `Free/CC BY`                       | integer | Number of images with CC BY licence                |
| `Free/CC0`                         | integer | Number of images with CC0 licence                  |
| `Free/RS NKC`                      | integer | Number of images with RS NKC rights statement      |
| `Free with conditions/CC BY-SA`    | integer | Number of images with CC BY-SA licence             |
| `Free with conditions/CC BY-NC`    | integer | Number of images with CC BY-NC licence             |
| `Free with conditions/CC BY-NC-ND` | integer | Number of images with CC BY-NC-ND licence          |
| `Free with conditions/CC BY-NC-SA` | integer | Number of images with CC BY-NC-SA licence          |
| `Free with conditions/InC-EDU`     | integer | Number of images with InC-EDU rights statement     |
| `Restricted/RS InC`                | integer | Number of images with RS InC rights statement      |
| `Restricted/RS CNE`                | integer | Number of images with RS CNE rights statement      |
| `Restricted/RS UND`                | integer | Number of images with RS UND rights statement      |## Examples of use



----
Created by [Tim Sherratt](https://timsherratt.au) for the [GLAM Workbench](https://glam-workbench.net)