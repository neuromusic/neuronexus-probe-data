# neuronexus-probe-data
database of NeuroNexus probe files from NiPOD database

## CSV Files

- `NiPOD-ProbeSpec-denormalized.csv` contains the geometry info for each of the probes

Each of the other CSV files is a table from the NiPOD database

## Notebooks

- `getting the geometries.ipynb` generates klustakwik prb files for each of probes in `NiPOD-ProbeSpec-denormalized.csv`
- `denormalizing.ipynb` merges the CSV files together to create `NiPOD-ProbeSpec-denormalized.csv`
- `getting electrode geometries.ipynb` accesses the NiPOD database and dumps the data into CSV files


