# Local integration modifications

This Core Flight Executive tree contains modifications maintained by banderson777 for
https://github.com/banderson777/bpsec-bplib-integration .
Original upstream: https://github.com/nasa/cFE
Upstream base commit: `84ef3d2ae9bb440d9f0511d27126a61ed3c43ee2`

Original copyright/license notices are retained. Modified file notices and this
manifest identify local work; commit history records the exact changes. Detailed
fix reviews, regression tests and validation evidence live in the main integration
repository's docs/ directory. This branch supports the native integration lab.

## Modified and added source/configuration

- `modules/es/fsw/src/cfe_es_start.c`

`LOCAL_CHANGES.md` is also added for attribution. Source changes were reviewed and
tested in the integration project; recorded historical validations refer to their
pinned source snapshots. Publication adds attribution notices and Git packaging
without changing the tested program logic.
