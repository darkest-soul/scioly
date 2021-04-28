![SciOly API](https://user-images.githubusercontent.com/65052071/116440264-ebdf6d80-a815-11eb-8616-276a29558474.png)

![Uptime](https://img.shields.io/uptimerobot/ratio/7/m787980980-78325a4e551f1aad9a2d3911?color=2E66B6&label=Uptime&style=flat-square) ![Pull Requests](https://img.shields.io/github/issues-pr-raw/aakhilv/scioly?color=2E66B6&label=Pull%20Requests&style=flat-square) ![Contributors](https://img.shields.io/github/contributors/aakhilv/scioly?color=2E66B6&label=Contributors&style=flat-square) ![Commits](https://img.shields.io/github/commit-activity/m/aakhilv/scioly?color=2E66B6&label=Commits&style=flat-square)

This is a community run Science Olympiad api. We are not affiliated nor endorsed by [Science Olympiad Inc.](https://www.soinc.org) in any way.

---

## Adding a problem to the database

### Step 1

Fork the [aakhilv/scioly](https://github.com/aakhilv/scioly/fork) master branch if you haven't already.

### Step 2

Add your problem to the [db.json](https://github.com/aakhilv/scioly/blob/main/db.json) file with the following format:

```json
{
  "category": "Specify the category here",
  "problem": "Insert question here?",
  "answer": "Insert answer here.",
  "image": "https://example.com/image.png",
  "choices": ["A", "B", "C", "D"]
}
```

* Only include the `image` key if the problem you are submitting has an associating image.
* If the problem is to be a to be a free/written response, do not include the `choices` key. If the problem is to be a true or false answer, only put two items in the array as `["true", "false"]`. If the problem is to be a multiple choice answer, include two or more items in the array.

### Step 3

Submit a [pull request](https://github.com/aakhilv/scioly/compare) from your fork's master branch to this repo's master branch.

### Step 4

Once accepted, your problem will start showing up in the [api](https://scioly.js.org/api) within a few hours. Additionally, please make sure to check the pull request every so often in case we require any changes from your end.

---

## Category codes

|Category|Code|
|---|---|
|Anatomy and Physiology|`anap`|

---

## Terms of Service

Coming soon!
