---
id: 574c93ab-31ca-4579-b6b8-a481b7b4364f
title: Onboarding
desc: ''
updated: 1609522891977
created: 1609519616762
---

## Keyboard shortcuts

### Navigation

- `ctrl` + `l`: Open lookup bar / notes creation
- `cmd` + `tab`: switch tabs
  - Navigate tabs: `cmd` + `shift` + `[` or `]`
- Markdown links: let you show graph of backlinks
- Keyboard shortcuts for
  - Creating bullet points
  - Adding URLs
  - Converting pasted tables into markdown tables
  - Context menu for any others you may have forgotten
- Learn shortcut for creating snippets, e.g. for weekly recap emails

### Editing

- opt up/down to shuffle lines and blocks, esp if reprioritizing stuff
- Deletion for unwanted note (shift cmd d)


### Creation

- Copy reference to notes to embed elsewhere
  - ctrl shift r (remapped to avoid collision)
- Create new scratch note with no home:
  - cmd shift s


## Top level concepts

- You don't need to worry about the order of files at creation time: write everything now, assign categories later.
- Applying some hierarchy is needed for high note volume
- Refactor hierarchy to restructure as needed
  - Example: move python.md top level to lang.python.
  - When context switching: now copy/outline mental model from Python to Ruby, and now you can translate each example as needed!
  - You can search with wildcards in hierarchy, like `lang.*.data` to search across languages
  - Use this as a cache of solutions to programming problems he runs into
    - Me: link to markdown bash issue


### Inline References

- You can reference other notes, including sections
((ref: [[dendron.onboarding]]#navigation:#creation))



### Snippets

dendron. etc keyboard expand

## Onboarding note details

- ID hashes map to URLs, which let you rearrange hierarchy freely
- You can go to backlinks, fulltext appears inside of hover
  - [[dendron]] takes you to the workspace root
  - Goto definition mapped to `cmd` + `enter`
  - If you navigate to a file that doesn't exist yet, dendron will create it.
- Tree view appears in Dendron "backlinks" and "tree view" sections.

### Example task list

- Create initial task list
- Break into smaller chunks using "scratch" nodes, and clean up on demand

You can create todos, clicking box in preview modifies the MD file.

- [x] Intro (Link to a scratch note) [[scratch.2021.01.01.115340]]
- [ ] Refactor, etc

### Advantage to developing in VScode

- Using "screencast mode" in VSCode: shows what keyboard items you're pressing, helps people who are learning keyboart shortcuts
- Shuffling line order: (keyboard shortcut)

### Paste images

- Paste image command: take picture from clipboard for adding media readily, saves it to your repository.

### Vscode inline tags

- Use #star or other tags to find related items on the same page when doing search,
  - use vscode scoped by "day" to find all journal entries with matching lines

### Typechecking hierarchy

- https://dendron.so/notes/c5e5adde-5459-409b-b34d-a0d75cbb1052.html
- lookup or create
  - `shift + cmd + l`: add lang file
  - In video, the error was the template was listed as a list rather than a key
- When done, reload your index

### Publishing

- Manually specify which hierarchies to publish (private etc)
- Use pods to export to Github
