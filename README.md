# part107quizzer
## Important

`quiz.html` is the canonical offline quiz app.

It is designed to open directly from the file system without a web server.

Do not reintroduce runtime CSV loading, `fetch()`, `parseCsv()`, or `fixQuestionRow()` into `quiz.html`.

Future changes should preserve the embedded `QUESTIONS` and `EXPLANATIONS` structure unless a deliberate build script is added and tested.

This note exists because previous versions corrupted question data by regenerating from malformed CSV rows.
