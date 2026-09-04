# Contributing

Contributions to this catalogue are welcome. You may submit a mutation-testing tool or a related publication, article, video, tutorial, conference, reproduction package or practical resource.

Resources need not be new or actively maintained. Inactive and obsolete projects may still be valuable for education, research, historical reference or comparison with other tools.

## Before submitting

- Check that the resource is directly relevant to mutation testing.
- Search the repository for the resource name and URL to avoid duplicates.
- Prefer a stable, authoritative URL, such as the project's repository, the author's website, a [Digital Object Identifier (DOI)](https://www.doi.org/the-identifier/what-is-a-doi/) or the publisher's page.
- Confirm that the link is accessible at the time of submission.
- Place the entry in the most appropriate existing section. Propose a new section only when none of the existing sections is suitable.

## Entry formats

Follow the surrounding Markdown style and keep descriptions factual. Avoid promotional claims or comparisons that are not supported by the linked material.

### Tools

Place tools under their primary language or platform. Use the following format:

```markdown
* [Tool name](https://example.com/tool) - Concise description of its purpose or distinguishing feature.
```

Related documentation, publications, and reproduction packages may be nested beneath the tool:

```markdown
* [Tool name](https://example.com/tool) - Concise description.
  * [Related publication](https://doi.org/example)
```

A description is encouraged, particularly when the tool's purpose is unclear from its name, but is not required when reliable information is unavailable.

### Publications

List publications in reverse chronological order and include the authors, publication year, and complete title:

```markdown
* [Author One, Author Two (2025) _Complete publication title_](https://doi.org/example)
```

Prefer a DOI or publisher page. A repository copy of a paper may be added only if redistribution is permitted. Preserve the spelling of the published title, even when it differs from the repository's British English style.

### Articles and posts

List articles and posts in reverse chronological order:

```markdown
* [Article title (2025) • Author or organisation](https://example.com/article)
```

### Videos

List videos and recorded talks in reverse chronological order:

```markdown
* [Event or series: Talk title • Speaker](https://example.com/video)
```

Include the year if known. Written event reports belong under **Blogs/Posts**, while recordings belong under **Videos**.

### Other resources

For tutorials, conferences, examples and practical resources, use a descriptive link title and add a concise explanation when its relevance is not immediately apparent.

## Project status

Contributors are not expected to monitor or assess whether a project is maintained. Do not classify a project as inactive or abandoned merely because it has not had a recent release or commit.

When a project's maintainers have explicitly archived it, marked it as discontinued or identified a successor, include that information in the pull request. If its status is unclear, omit a status label. A project's status does not affect whether a relevant resource is eligible for inclusion.

## Unavailable links

When a link stops working:

* Prefer an official replacement URL or a link supplied by the original author or publisher.
* If a project has moved, update its URL rather than adding a duplicate entry.
* If no live source remains, an established web archive may be used when appropriate.
* Do not remove a historically useful entry solely because its original URL is unavailable; mention the unavailable source in the pull request so that alternatives can be considered.
* Do not replace an unavailable source with an unauthorised copy.

## Pull requests

Keep each pull request focused and explain what it adds or changes. For a new entry, briefly state its relevance to mutation testing. For a correction, provide a source when the reason is not evident from the change.

Links and contributions are reviewed manually. Maintainers may request changes to placement, formatting, or wording so that the catalogue remains consistent and neutral.
