# OpenMonitor Science

Reusable notebooks, readers, and short guides for working with selected
OpenMonitor exports.

OpenMonitor provides web tools for exploring scientific data, journals,
research profiles, and opportunities. This repository helps researchers,
students, and collaborators reopen exported results, inspect the metadata, make
quick plots, and cite OpenMonitor-derived products in a reproducible way.

## Start Here

Most people arrive here from an OpenMonitor tool. Use the kit linked by the
page that generated your export.

Current public kit:

- [Solar AIA ROI light curves](kits/solar/aia-roi-lightcurves): open AIA ROI
  light-curve exports in Google Colab or local Python, inspect ROI metadata,
  read FITS/CSV files, and compare runs.

## What You Can Do

- Open an OpenMonitor export in Colab.
- Read exported CSV, FITS, JSON, or metadata files.
- Check column meanings and units.
- Recreate quick-look plots from downloaded results.
- Compare selected runs, such as multiple AIA wavelengths for the same flare.
- Copy citation and methods text for reports, posters, or papers.

## Repository Map

The repository is organized by OpenMonitor domain so each tool has a stable
home for examples and readers.

- `kits/solar/`: Solar Lab export readers and examples.
- `kits/atmospheric-electricity/`: atmospheric-electricity and geospace data
  examples.
- `kits/journals/`: journal and paper-search export readers.
- `kits/peers/`: Peers catalog export readers.
- `kits/calls/`: Calls and opportunity export readers.
- `docs/`: citation, data policy, and reproducibility notes.

Only the kits with a README and notebook are ready for use. Other folders are
reserved for future public examples as OpenMonitor exports mature.

## Data Policy

This repository is intentionally lightweight. It does not mirror large provider
archives or server-side caches. The notebooks read small OpenMonitor exports or
download selected derived artifacts through public OpenMonitor links.

Underlying observations remain with their official providers. OpenMonitor
exports should be cited together with the relevant data provider.

## License

- Code and notebooks: MIT, see [LICENSE](LICENSE).
- Tiny sample data: CC0 1.0, see [LICENSE-DATA.md](LICENSE-DATA.md).
- Documentation: CC BY 4.0 unless noted otherwise.

## Citation

See [CITATION.cff](CITATION.cff) and [docs/citation.md](docs/citation.md).
