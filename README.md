# SciOly API

This is a community run Science Olympiad api. We are not affiliated nor endorsed by [Science Olympiad Inc.](https://www.soinc.org) in any way.

## How to add a problem to the database

1. Fork the [aakhilv/scioly](https://github.com/aakhilv/scioly/fork) master branch.
2. Add your problem to the [db.json](https://github.com/aakhilv/scioly/blob/main/db.json) file with the following format:

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

3. Submit a [pull request](https://github.com/aakhilv/scioly/compare) from your fork's master branch to this repo's master branch.
4. Once accepted, your problem will start showing up in the [api](https://scioly.js.org/api) within a few days.
