![SciOly API](https://user-images.githubusercontent.com/65052071/116440264-ebdf6d80-a815-11eb-8616-276a29558474.png)

![Uptime](https://img.shields.io/uptimerobot/ratio/7/m787980980-78325a4e551f1aad9a2d3911?color=2E66B6&label=Uptime&style=flat-square) ![Pull Requests](https://img.shields.io/github/issues-pr-raw/aakhilv/scioly?color=2E66B6&label=Pull%20Requests&style=flat-square) ![Contributors](https://img.shields.io/github/contributors/aakhilv/scioly?color=2E66B6&label=Contributors&style=flat-square) ![Commits](https://img.shields.io/github/commit-activity/m/aakhilv/scioly?color=2E66B6&label=Commits&style=flat-square)

This is a community run Science Olympiad api. We are not affiliated nor endorsed by [Science Olympiad Inc.](https://www.soinc.org) in any way.

## Adding a problem to the database

### Step 1

Fork the [aakhilv/scioly](https://github.com/aakhilv/scioly/fork) master branch if you haven't already.

### Step 2

Add your problem to the [db.json](https://github.com/aakhilv/scioly/blob/main/db.json) file with the following format:

```json
{
  "category": "Specify the category code here",
  "problem": "Insert question here?",
  "answer": "Insert answer here.",
  "image": "https://example.com/image.png",
  "choices": ["A", "B", "C", "D"]
}
```

> The `category` value should be the corresponding code from the [chart](https://github.com/aakhilv/scioly#category-codes) below.

> Only include the `image` key if the problem you are submitting has an associating image.

> If the problem is to be a to be a free/written response, do not include the `choices` key.\
> If the problem is to be a true or false answer, only put two items in the array as `["true", "false"]`.\
> If the problem is to be a multiple choice answer, include two or more items in the array.

### Step 3

Submit a [pull request](https://github.com/aakhilv/scioly/compare) from your fork's master branch to this repo's master branch.

### Step 4

Once accepted, your problem will start showing up in the [api](https://scioly.js.org/api) within a few hours. Additionally, please make sure to check the pull request every so often in case we require any changes from your end.

## Category codes

|Category|Code|
|---|---|
|Anatomy and Physiology|`anap`|
|Disease Detectives|`dd`|
|Heredity|`heredity`|
|Ornithology|`orni`|
|Water Quality|`waqua`|
|Dynamic Planet|`dp`|
|Fossils|`fossils`|
|Meteorology|`meteo`|
|Reach for the Stars|`rfts`|
|Road Scholar|`road`|
|Circuit Lab|`circuit`|
|Crime Busters|`crime`|
|Density Lab|`density`|
|Food Science|`foodsci`|
|Machines|`machines`|
|Boomilever|`boomi`|
|Elastic Launched Gliders|`elg`|
|Mission Impossible|`mi`|
|Mousetrap Vehicle|`mtv`|
|Experimental Design|`exd`|
|Game On|`game`|
|Ping Pong Parachute|`ppp`|
|Write It Do It|`widi`|
|Designer Genes|`genes`|
|Astronomy|`astro`|
|GeoLogic Mapping|`geomap`|
|Chem Lab|`chem`|
|Forensics|`forensics`|
|Protein Modeling|`promod`|
|Sounds of Music|`music`|
|Detector Building|`detbuild`|
|Gravity Vehicle|`gravity`|
|Wright Stuff|`wright`|
|Codebusters|`code`|

## Api endpoints

### All Categories

```sh
GET https://scioly.js.org/api
```

### Anatomy and Physiology

```sh
GET https://scioly.js.org/api/anap
```

### Disease Detectives

```sh
GET https://scioly.js.org/api/dd
```

### Heredity

```sh
GET https://scioly.js.org/api/heredity
```

### Ornithology

```sh
GET https://scioly.js.org/api/orni
```

### Water Quality

```sh
GET https://scioly.js.org/api/waqua
```

### Dynamic Planet

```sh
GET https://scioly.js.org/api/dp
```

### Fossils

```sh
GET https://scioly.js.org/api/fossils
```

### Meteorology

```sh
GET https://scioly.js.org/api/meteo
```

### Reach for the Stars

```sh
GET https://scioly.js.org/api/rfts
```

### Road Scholar

```sh
GET https://scioly.js.org/api/road
```

### Circuit Lab

```sh
GET https://scioly.js.org/api/circuit
```

### Crime Busters

```sh
GET https://scioly.js.org/api/crime
```

### Density Lab

```sh
GET https://scioly.js.org/api/density
```

### Food Science

```sh
GET https://scioly.js.org/api/foodsci
```

### Machines

```sh
GET https://scioly.js.org/api/machines
```

### Boomilever

```sh
GET https://scioly.js.org/api/boomi
```

### Elastic Launched Gliders

```sh
GET https://scioly.js.org/api/elg
```

### Mission Impossible

```sh
GET https://scioly.js.org/api/mi
```

### Mousetrap Vehicle

```sh
GET https://scioly.js.org/api/mtv
```

### Experimental Design

```sh
GET https://scioly.js.org/api/exd
```

### Game On

```sh
GET https://scioly.js.org/api/game
```

### Ping Pong Parachute

```sh
GET https://scioly.js.org/api/ppp
```

### Write It Do It

```sh
GET https://scioly.js.org/api/widi
```

### Designer Genes

```sh
GET https://scioly.js.org/api/genes
```

### Astronomy

```sh
GET https://scioly.js.org/api/astro
```

### GeoLogic Mapping

```sh
GET https://scioly.js.org/api/geomap
```

### Chem Lab

```sh
GET https://scioly.js.org/api/chem
```

### Forensics

```sh
GET https://scioly.js.org/api/forensics
```

### Protein Modeling

```sh
GET https://scioly.js.org/api/promod
```

### Sounds of Music

```sh
GET https://scioly.js.org/api/music
```

### Detector Building

```sh
GET https://scioly.js.org/api/detbuild
```

### Gravity Vehicle

```sh
GET https://scioly.js.org/api/gravity
```

### Wright Stuff

```sh
GET https://scioly.js.org/api/wright
```

### Codebusters

```sh
GET https://scioly.js.org/api/code
```
