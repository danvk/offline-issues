# offline-issues

Get your GitHub Issues offline! In Markdown and HTML.

![screenshot](screenshot.png)

## But how?

- Have [Node.js]() installed on computer.
- Install this module `npm install -g offline-issues`
- Authorize it by running `offline-issues` and following the commands
- Use it to save Issues as .md and .html!

### CLI

For one issue:

```bash
$ offline-issues USER/REPO#0
```

For all issues:

```bash
$ offline-issues USER/REPO
```

For multiple repositories or issues:

```bash
$ offline-issues USER/REPO USER/REPO#0
```

Example:

```bash
$ offline-issues jlord/offline-issues muan/github-gmail#4
```

Whatever directory you are in, it will create a `md` and `html` folder with the resulting files.

**TADA**

## Future times

Currently working at MVP level -- it gives you the issues you sepcify. But I want to add to it:

- some css so the html isn't so painfully raw
- more commandline options like getting 'all' or 'closed' or 'open' or by 'author' or 'mention'

Then maybe after that:

- serve up these files locally with a nice directory page
