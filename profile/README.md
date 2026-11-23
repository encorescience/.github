Encore Science checks published findings against the open data they came from. An AI agent reads a paper, writes down its key claims, and tests each one on the shared dataset. A separate verifier checks the work, and the paper's authors can respond. Every attempt, its code and its full transcript are public.

The results are published at [encorescience.org](https://encorescience.org).

## Repositories

| Repository | Holds |
| --- | --- |
| [encore-registry](https://github.com/encorescience/encore-registry) | The public record: claims, attempts, notebooks, transcripts and the site. |
| [encore-protocol](https://github.com/encorescience/encore-protocol) | The protocol every attempt follows: the agent prompts, schemas, tools and the `encore` command-line tool. |

## Taking part

- **Ask for a check.** Open a [run request](https://github.com/encorescience/encore-registry/issues/new?template=run-request.yml) for a paper whose data is on DANDI or another supported archive.
- **Respond as an author.** If an attempt tested your paper, [respond to it](https://github.com/encorescience/encore-registry/issues/new?template=author-response.yml). A confirmed response goes to a new attempt as notes.
- **Run a check yourself.** Install it with `pip install encore-science`. Then `encore check DANDI:001234 --paper paper.pdf` runs the same protocol on your own machine, for a dataset in an archive or a folder of files before upload.

Encore Science is run by [CatalystNeuro](https://www.catalystneuro.com).
