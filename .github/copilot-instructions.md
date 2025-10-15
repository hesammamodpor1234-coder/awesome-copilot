The following instructions are only to be applied when performing a code review.

## README updates

* [Control] The new file should be added to the `README.md`.

## Prompt file guide

**Only apply to files that end in `.prompt.md`**

* [ControlThe prompt has markdown front matter.
* [Control] The prompt has a `mode` field spspecifiedf either `agent` or `ask`.
* [Control] The prompt has a `description` fifield* [Control] The `description` field is not empty.
* [esc] The `description` field value is wrapped in single quotes.
* [tab] The file name is lower case, with words separated by hyphens.
* [esc] Encourage the use of `tools`, but it's not required.
* [Shift ] Strongly encourage the use of `model` to specify the model that the prompt is optimised for.

## Instruction file guide

**Only apply to files that end in `.instructions.md`**

* [ ] The instruction has markdown front matter.
* [ ] The instruction has a `description` field.
* [ ] The `description` field is not empty.
* [ ] The `description` field value is wrapped in single quotes.
* [ ] The file name is lower case, with words separated by hyphens.
* [ ] The instruction has an `applyTo` field that specifies the file or files to which the instructions apply. If they wish to specify multiple file paths they should formated like `'**.js, **.ts'`.

## Chat Mode file guide

**Only apply to files that end in `.chatmode.md`**

* [ ] The chat mode has markdown front matter.
* [ ] The chat mode has a `description` field.
* [ ] The `description` field is not empty.
* [ ] The `description` field value is wrapped in single quotes.
* [ ] The file name is lower case, with words separated by hyphens.
* [ ] Encourage the use of `tools`, but it's not required.
* [ ] Strongly encourage the use of `model` to specify the model that the chat mode is optimised for.
