# outage-atlas

A searchable, structured library of public software postmortems that engineers can question, filter, and subscribe to. Scattered incident write-ups become structured records, and answers cite the original reports.

**Status:** planning. Application code is added in upcoming changes.

## What it demonstrates

- Data pipelines over a real, changing dataset of public postmortems
- LLM-based extraction of structured fields from unstructured incident reports
- Retrieval, with answers that cite the reports they draw from
- Measured evaluation of extraction and answer quality

## Scope

Outage Atlas needs no access to a user's code or repositories. Users describe what they care about in plain text.

## Standards

Work in this repository follows [CONTRIBUTING.md](CONTRIBUTING.md) and the shared standards in [`docs/standards/`](docs/standards), synced from [engineering-standards](https://github.com/nathan-a-reed/engineering-standards). Shared AWS accounts, deployment roles, and DNS come from [aws-foundation](https://github.com/nathan-a-reed/aws-foundation).

## License

[MIT](LICENSE)
