# Tabularia for Cursor

Use [Tabularia](https://tabularia.app), the writing studio, from Cursor. The plugin connects Cursor's agent to your Tabularia account and brings skills for the editing jobs a writer actually asks for, from a developmental read to a query letter.

## Use it

Install Tabularia from the Cursor Marketplace. The first time the agent reaches for a manuscript, Cursor opens Tabularia's sign-in page in your browser; approve the connection there and come back. Then ask for what you need:

| Skill                | Ask for                                                                 |
| -------------------- | ----------------------------------------------------------------------- |
| `structural-read`    | "Does my structure work?" "Does the middle drag?"                       |
| `continuity-check`   | "Have I contradicted myself?" "Is the timeline consistent?"             |
| `line-edit`          | "Tighten this chapter." "Fix the grammar in this scene."                |
| `prose-read`         | "How does this read?" "Am I repeating myself?"                          |
| `natural-voice`      | "Make this sound less like AI." "Write it the way I would."             |
| `review-triage`      | "What's waiting for me?" "Where did I leave off?"                       |
| `story-thread-draft` | "Revise this thread across the book in a draft."                        |
| `story-sheets`       | "Make me a character list." "Update my character sheets from the book." |
| `synopsis-and-query` | "Write my synopsis." "Draft a query letter."                            |
| `opening-pages`      | "Would an agent keep reading?" "Does my first chapter hook?"            |
| `finish-the-book`    | "Add a title page and drop caps." "Make it look like a real book."      |
| `nonfiction-read`    | "Does my argument hold?" "Is my proposal ready?"                        |
| `article-edit`       | "Improve this blog post." "Is my headline working?"                     |
| `screenplay-read`    | "Give me coverage." "Is my script formatted right?"                     |

Nothing the agent writes touches your text until you say so. By default its changes go into a draft of its own, which you open in Tabularia beside your version and merge however much of it you want. Ask for a change to your text itself and Tabularia takes a Snapshot before the agent makes it.

## Data

This plugin is text and configuration: skill files, a manifest, and a logo. It runs no code on your machine and reads no credentials from it. Cursor stores the token Tabularia issues when you approve the connection.

The hosted server at `mcp.tabularia.app` acts only for the account that signed in. It reads that account's manuscripts and writes the drafts, comments, and edits you ask for, and the only time it fetches anything from outside Tabularia is a picture you request from Wikimedia Commons, Unsplash, or Flickr. Tabularia does not train on your writing; how Cursor handles your sessions is set by Cursor's own privacy settings. See Tabularia's [privacy policy](https://tabularia.app/privacy).

## License

The contents of this repository are licensed under the [Apache License 2.0](LICENSE). Tabularia itself, including the service at `mcp.tabularia.app`, is proprietary and is not covered by this license.
