# SciOly API

This is a community ran Science Olympiad api. We are not affiliated nor endorsed by [Science Olympiad Inc.](https://www.soinc.org) in any way.

## How to add a problem to the database

1. Fork the [aakhilv/scioly](https://github.com/aakhilv/scioly/fork) master branch.
2. Add your problem to the [db.json](https://github.com/aakhilv/scioly/blob/main/db.json) file with the following format:

```json
{
  "source": "Specify the source here",
  "problem": "Insert question here?",
  "answer": "Insert answer here.",
  "image": "https://example.com/image.png", /* Only include this key if the problem you are submitting has an associating image. */
  "choices": ["A", "B", "C", "D"] /* If this problem is to be a to be a free/written response, do not include this key. If this problem is to be a true or false answer, only put two items in the array as ["true", "false"]. If this problem is to be a multiple choice answer, include two or more values in the array. */
}
```
