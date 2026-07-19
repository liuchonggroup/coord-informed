# Processed Data Archives

This directory contains the processed datasets released with the manuscript.

The archived files are deposited on Zenodo:

DOI: 10.5281/zenodo.21386870

## Files

| File | Description | SHA256 |
| --- | --- | --- |
| `SclogK_with_cb.tar.gz` | Processed single-complex log beta dataset with coordination-bond annotations. | `1b99be12383f6c244a288447ee5a4770c1190da14d463d5de3d8ae8d5c3d797c` |
| `mono_ml_pair.tar.gz` | Processed mono-metal-ligand pair dataset. The archive may also be provided as ten upload parts in `mono_ml_pair_split_10/`. | `c697111015cb8ec291962ee78a30365ad8a08bcf3e39fa18a1ebdff5259e0bc5` |
| `GibbsBeta.tar.gz` | Processed GibbsBeta data archive. | `254c74b1f96b8ebbc3a21cb0545c1111536ec9596085a33092fa1af0763ef403` |

## Cloud Locations

| File | Zenodo location |
| --- | --- |
| `SclogK_with_cb.tar.gz` | `https://zenodo.org/records/21386870/files/SclogK_with_cb.tar.gz` |
| `mono_ml_pair.tar.gz` | `https://zenodo.org/records/21386870/files/mono_ml_pair.tar.gz` |
| `GibbsBeta.tar.gz` | `https://zenodo.org/records/21386870/files/GibbsBeta.tar.gz` |

## Split Upload for `mono_ml_pair`

For upload stability, `mono_ml_pair.tar.gz` is also split into ten parts:

```text
mono_ml_pair_split_10/mono_ml_pair.tar.gz.part_00.part
mono_ml_pair_split_10/mono_ml_pair.tar.gz.part_01.part
mono_ml_pair_split_10/mono_ml_pair.tar.gz.part_02.part
mono_ml_pair_split_10/mono_ml_pair.tar.gz.part_03.part
mono_ml_pair_split_10/mono_ml_pair.tar.gz.part_04.part
mono_ml_pair_split_10/mono_ml_pair.tar.gz.part_05.part
mono_ml_pair_split_10/mono_ml_pair.tar.gz.part_06.part
mono_ml_pair_split_10/mono_ml_pair.tar.gz.part_07.part
mono_ml_pair_split_10/mono_ml_pair.tar.gz.part_08.part
mono_ml_pair_split_10/mono_ml_pair.tar.gz.part_09.part
```

The original archive can be reconstructed with:

```bash
cat mono_ml_pair_split_10/mono_ml_pair.tar.gz.part_*.part > mono_ml_pair.tar.gz
```

The split-file checksums are listed in `mono_ml_pair_split_10/SHA256SUMS`.

## Verification

After downloading the archives, the checksums can be verified with:

```bash
sha256sum SclogK_with_cb.tar.gz mono_ml_pair.tar.gz GibbsBeta.tar.gz
```

The local archive files are large and are not intended to remain in the Git repository after deposition.
