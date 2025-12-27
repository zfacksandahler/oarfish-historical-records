# Oarfish Historical Records Database

A structured, version-controlled, and publicly accessible database that collates historical sightings of oarfish (*Regalecidae*), separating scientific observation details from associated folklore and legends.

## Purpose

This repository serves as a primary source for researchers, marine biologists, and folklorists interested in:
- Documenting verified and anecdotal oarfish sightings across history.
- Distinguishing between empirical scientific accounts and cultural narratives.
- Creating a collaborative, peer‑reviewed dataset that can be cited, extended, and analysed.

## Repository Structure

```
oarfish-historical-records/
├── README.md                           # This file
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── sighting_report.md          # Template for reporting new sightings
├── data/                               # Directory for individual sighting records
│   └── (each sighting as a separate Markdown file)
└── docs/                               # Supplementary documentation (optional)
```

## How to Contribute

1. **Report a new sighting** – Open a new issue using the [Sighting Report template](.github/ISSUE_TEMPLATE/sighting_report.md). Provide as much detail as possible, including sources and verification status.

2. **Add a verified record** – After discussion in the issue, create a new branch, write a structured Markdown file in `data/` (e.g., `arica_1868.md`), and submit a pull request.

3. **Review existing entries** – Comment on open issues and pull requests to help verify data, suggest improvements, or point out conflicting sources.

4. **Improve documentation** – Enhance the README, add metadata schemas, or create auxiliary documents in the `docs/` folder.

## Data Format

Each sighting record in the `data/` directory should be a Markdown file with the following sections:

- **Scientific Account** – Date, location, physical description, behaviour, environmental context, source references.
- **Local Legends** – Folklore, myths, or cultural interpretations linked to the sighting.
- **Verification Notes** – Assessment of reliability, conflicting accounts, links to the original issue.

## License

All textual content in this repository is made available under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/), unless otherwise noted.

## Contact

Maintained by a marine biologist specialising in deep‑sea creatures, particularly oarfish. For questions or collaboration, please open an issue in this repository.