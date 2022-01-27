<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->
# Awesome Dendron

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![lint](https://github.com/dendronhq/awesome-dendron/actions/workflows/lint.yaml/badge.svg)](https://github.com/dendronhq/awesome-dendron/actions/workflows/lint.yaml)

<!-- subtitle -->

The most up to date list of Dendron docs, talks, tools, examples, articles, extensions, vaults, showcases, and more that the internet has to offer.  

<!-- image -->

<a href="" target="_blank" rel="noopener noreferrer">
  <img src="https://org-dendron-public-assets.s3.amazonaws.com/images/dendron-banner.png" />
</a>

<!-- description -->

[![dendronhq on Twitter](https://img.shields.io/twitter/follow/dendronhq?style=social)](https://link.dendron.so/twitter)
[![Dendron on YouTube](https://img.shields.io/youtube/channel/subscribers/UC8GQLj4KZhN8WcJPiKXtcRQ?style=social)](https://link.dendron.so/youtube)
[![Discord](https://img.shields.io/discord/717965437182410783?color=blueviolet&label=Discord&style=flat-square)](https://link.dendron.so/discord)
[![VS Code Installs of Dendron](https://img.shields.io/visual-studio-marketplace/i/dendron.dendron?label=VS%20Code%20Installs%20of%20Dendron&color=blue&style=flat-square)](https://link.dendron.so/vscode)

[Dendron](https://www.dendron.so) is an **open-source, local-first, markdown-based, note-taking tool**. It's a personal knowledge management solution (PKM) built specifically for developers and integrates natively with IDEs like [VS Code](https://code.visualstudio.com/) and [VSCodium](https://vscodium.com/).


</div>

## Dendron Official Public Vaults

> Official public vaults by Dendron. Feel free to use and contribute to them!

- Dendron Documentation | [Source](https://github.com/dendronhq/dendron-site) |  [Published Site](https://wiki.dendron.so/)
- Dendron Developer Documentation | [Source](https://github.com/dendronhq/dendron-docs) | [Published Site](https://docs.dendron.so/)
- The Open PKM Catalogue | [Source](https://github.com/dendronhq/catalogue-open-pkm) | [Published Site](https://pkm.dendron.so/)
- The Open AWS Catalogue | [Source](https://github.com/dendronhq/seeds.aws) | [Published Site](https://aws.dendron.so/)
- TLDR | [Upstream Source](https://github.com/tldr-pages/tldr) | [Source](https://github.com/kevinslin/seed-tldr) | [Published Site](https://tldr.dendron.so/)
- Dendron Templates | [Source](https://github.com/dendronhq/templates/)
- Dendron Schema Library | [Source](https://github.com/dendronhq/schema-library)

## Community Public Vaults

> Public vaults from the Dendron community. Feel free to use and contribute to them!

- [Bassman/dendron-schemas](https://github.com/Bassmann/Dendron-schemas): Collection of Dendron schema and template files

## Dendron Official VS Code / VSCodium Extensions

> Official extensions by Dendron

- [Dendron](https://marketplace.visualstudio.com/items?itemName=dendron.dendron): The official extension that does it all!
- [Dendron Nightly/Preview](https://marketplace.visualstudio.com/items?itemName=dendron.dendron)
- [Dendron Paste Image](https://github.com/dendronhq/dendron-paste-image)
- [Dendron Markdown Shortcuts](https://marketplace.visualstudio.com/items?itemName=dendron.dendron-markdown-shortcuts)
- [Dendron Snippet Maker](https://marketplace.visualstudio.com/items?itemName=dendron.dendron-snippet-maker)

### Archived / Not Recommended

> These official extensions are no longer recommended, or may cause unintended and unexpected behavior, when using Dendron

- [Dendron Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=dendron.dendron-markdown-preview-enhanced)
- [Dendron Markdown Links](https://marketplace.visualstudio.com/items?itemName=dendron.dendron-markdown-links)

## Community VS Code / VSCodium Extensions

> Community extensions from the marketplace can potentially have conflicts (settings, shortcuts, etc.) with the official Dendron extensions, leading to unexpected behavior.

### Markdown Enhancers

- [Markdown Writer Theme](https://marketplace.visualstudio.com/items?itemName=mgmeyers.markdown-writer-theme): VS Code theme emphasizing markdown over code
- [Markdown All-In-One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
  - May cause instability or general problems with using VS Code snippets
  - Shortcuts that clash, and may need to be reassigned
    - Toggle heading (downlevel): `Ctrl + Shift + [` || `Dendron: Go Previous Sibling` (`Ctrl + Shift + [`)
    - Toggle heading (uplevel): `Ctrl + Shift + ]` || `Dendron: Go Next Sibling` (`Ctrl + Shift + ]`)
- [Todo+](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-todo-plus)
- [Projects+ Todo+](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-projects-plus-todo-plus)
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
- [Excel to Markdown table](https://marketplace.visualstudio.com/items?itemName=csholmq.excel-to-markdown-table): Converts Excel and Google Docs spreadsheet data to Markdown table formats
- [Advanced Table Functionality](https://marketplace.visualstudio.com/items?itemName=RomanPeshkov.vscode-text-tables): Do more with markdown tables
- [vscode-reveal](https://marketplace.visualstudio.com/items?itemName=evilz.vscode-reveal): This extension lets you display a [reveal.js](https://revealjs.com/) presentation directly from an opened markdown document

### Spellcheck, Linters, and Style Guides

- [Spell Right](https://marketplace.visualstudio.com/items?itemName=ban.spellright): Multilingual, Offline and Lightweight Spellchecker
  - Will flag `id:` values in YAML frontmatter as misspellings. Fix: `"spellright.ignoreRegExps": ["/id: .*/ig"],`
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Write Good Linter](https://marketplace.visualstudio.com/items?itemName=travisthetechie.write-good-linter)
- [Vale](https://marketplace.visualstudio.com/items?itemName=errata-ai.vale-server)
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml): Validation for YAML file, such as `dendron.yml`

### Git

- [Git Automator](https://marketplace.visualstudio.com/items?itemName=ivangabriele.vscode-git-add-and-commit): one command to commit and push all changes
- [GitDoc](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.gitdoc): Automatically commit/push/pull changes on save, so you can edit a Git repo like a multi-file, versioned document.
- [Gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens): Repository/File/Line history and annotations of all your files
- [GitGraph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph): View a Git Graph of your repository, and easily perform Git actions from the graph. Configurable to look the way you want.
- [Path AutoComplete](https://github.com/ionutvmi/path-autocomplete): Path autocomplete for Visual Studio Code

### Vim bindings and more

- [VSCode Vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim): Vim key bindings 😍
- [VSCode NeoVim](https://marketplace.visualstudio.com/items?itemName=asvetliakov.vscode-neovim) - an alternative to VSCodeVim
- [Learn Vim](https://marketplace.visualstudio.com/items?itemName=vintharas.learn-vim): Learn Vim right within VSCode. Use this extension to learn and practice your Vim skills and become a more awesome developer.

### Coding

- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)

### Other

- [Auto Run Command](https://marketplace.visualstudio.com/items?itemName=gabrielgrinberg.auto-run-command): an extension that automatically runs commands after VS Code startup (e.g. `dendron.sync`)
- [Macros](https://marketplace.visualstudio.com/items?itemName=geddski.macros): Define custom macros 
- [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks): Bookmark lines within File
- [Vertical Limit](https://marketplace.visualstudio.com/items?itemName=generik.vertical-limit): Work with multiple cursors and blocks of text
- [CodeUI](https://marketplace.visualstudio.com/items?itemName=ryanraposo.codeui): Easier customization of every part of the VSCode UI
- [Open in Typora](https://marketplace.visualstudio.com/items?itemName=cyberbiont.vscode-open-in-typora&utm_source=VSCode.pro&utm_campaign=AhmadAwais): Open note in Typora
- [Profile Switcher](https://marketplace.visualstudio.com/items?itemName=aaronpowell.vscode-profile-switcher): Create different set of extension profiles
- [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager): Easier navigation UX between projects, directories, and workspaces
-  [Open in External App](https://marketplace.visualstudio.com/items?itemName=YuTengjing.open-in-external-app): When you want to edit your files in Typora, iAWriter or some other tool
- [Read Time](https://marketplace.visualstudio.com/items?itemName=johnpapa.read-time): Extension that provides estimated read times for your notes/docs

## Dendron Enhancers

> Scripts, tools, and repos dedicated to leveling up your Dendron powers

- [Export and Publish Draw.io Diagrams](https://github.com/LukeCarrier/dendron-publish-drawio): Use this tool to embed [draw.io / diagrams.net](https://www.diagrams.net/) diagrams in your published Dendron notes and documentation
- [`dendron-pandoc`](https://github.com/mivanit/dendron-pandoc): Run specialized [pandoc](https://pandoc.org/) filters for making Dendron links work properly, a script for adding bibliography information (or other data) to all markdown files in a vault, and more
- [`joplin2dendron`](https://github.com/chmac/joplin2dendron): Helper script to copy the correct dates from Joplin files into Dendron when migrating.

## Browser Extensions

> Extensions and add-ons for your favorite web browsers that make note taking, sharing, organizing, and collecting knowledge easier in Dendron workflows

### Web Clippers

- [MarkDownload - Markdown Web Clipper](https://github.com/deathau/markdownload): This extension works like a web clipper, but it downloads articles in markdown format. Works on: `Chrome/Chromium` / `Firefox` / `Edge` / `Safari`
- [Web Clipper](https://chrome.google.com/webstore/detail/web-clipper/mhfbofiokmppgdliakminbgdgcmbhbac): Another markdown-format web clipper. Universal open source web clipper for Notion, OneNote, Joplin, Yuque,Bear, GitHub and more notes.
- [Convert a Website Table to Markdown](https://tabletomarkdown.com/convert-website-table-to-markdown/): A website that helps you convert HTML tables from websites into Markdown formatted pipe tables

## Dendron Showcase

> Websites published with Dendron. These users get the **Planter** [Discord role badges](https://wiki.dendron.so/notes/7c00d606-7b75-4d28-b563-d75f33f8e0d7/).

- [Kevin Lin's Garden](https://kevinslin.com/) | Discord: `@kevins8#0590`
- [Luke Carrier's Garden](https://luke.carrier.im/) | Discord: `@lukecarrier#2081`
- [Ian Jones' Garden](https://garden.ianjones.us/) | Discord: `@ianjones#3696`
- [Kevin Cunningham's Garden](https://garden.kevincunningham.co.uk/) | Discord: `@dolearning (Kevin)#3551`
- [Cameron Yik's Garden (serendipidata)](https://notes.serendipidata.com/) | Discord: `@cameron#9185`
- [Derek Ardolf's Garden (icanteven)](https://icanteven.io/) | Discord: `@icanteven#0264`
- [Adam's Garden (glucknotes)](https://glucknotes.com/) | Discord: `@glucinater21#0869`

## Other awesome lists of interest

> Awesome lists and other collections of topics related to the Dendron stack, or otherwise of interest to dendronites. These may also be candidates for pulling into a future `awesome-list` Dendron vault.

- [The Book of Secret Knowledge](https://github.com/trimstray/the-book-of-secret-knowledge)
- [Awesome git](https://github.com/dictcp/awesome-git)
- [Awesome Shell](https://github.com/alebcay/awesome-shell)
  - [Modern Unix](https://github.com/ibraheemdev/modern-unix)
- [Awesome VS Code](https://github.com/viatsko/awesome-vscode)
- [GitHub Cheat Sheet](https://github.com/tiimgreen/github-cheat-sheet)
- [Awesome GitHub Actions](https://github.com/sdras/awesome-actions)
- [Awesome TypeScript](https://github.com/dzharii/awesome-typescript)
- [Awesome Node.js](https://github.com/sindresorhus/awesome-nodejs)
- [Awesome Electron](https://github.com/sindresorhus/awesome-electron)
- [Structured Text Tools](https://github.com/dbohdan/structured-text-tools)
- [Second Brain](https://github.com/KasperZutterman/Second-Brain)
- [Digital Gardeners](https://github.com/MaggieAppleton/digital-gardeners)

## Follow on Social Media

> Accounts and lists to follow on social media when it comes to apps, tools for thought, personal knowledge management, and other backgrounds of interest.

### Dendron Twitter Lists

- [Mobile Markdown Notes](https://twitter.com/i/lists/1452712294438289422?s=20&t=9JKcKO8S3BY2-DdNZYeQUQ) - Apps mentioned in the Dendron blog article, [Best Mobile Note-Taking Apps for Markdown](https://blog.dendron.so/notes/fDCVPEo3guCFWPdxokXHU/), and other related accounts.
- [PKM / Tools for Thought](https://twitter.com/i/lists/1484255825413619712?s=20&t=9JKcKO8S3BY2-DdNZYeQUQ) - Accounts tweeting about second brains, tools for thought, personal knowledge management (PKM), etc.

## Contributing

Contributions of any kind welcome, just follow the [contributing guide](contributing.md).

### Contributors

Thanks to [these contributors](https://github.com/dendronhq/awesome-dendron/graphs/contributors) for the continued growth of this awesome list!
