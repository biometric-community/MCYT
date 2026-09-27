# MCYT

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FMCYT-181717?logo=github)](https://github.com/biometric-community/MCYT)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](http://atvs.ii.uam.es/databases.asp)

**MCYT** — tbiom catalog packaging for `mcyt` (signature; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/MCYT
- **Upstream source**: http://atvs.ii.uam.es/databases.asp
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `mcyt` |
| Category | `signature` |
| Access | `register` |
| Upstream homepage | http://atvs.ii.uam.es/databases.asp |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: MCYT signature (ATVS / UAM).

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/MCYT.git
cd MCYT
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_mcyt.sh
```

Place licensed archives under `projects/datasets/mcyt/` (gitignored).

## Dataset structure

```text
MCYT/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: http://atvs.ii.uam.es/databases.asp
- Packaging: https://github.com/biometric-community/MCYT/issues
