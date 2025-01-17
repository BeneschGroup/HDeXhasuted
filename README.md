# HDeXhasuted
HDeXhausted visualizes amino acids that appear in statistically significant peptides identified by Deuteros on a protein structure (PDB). The tool processes filtered peptide data and generates a heatmap along with a PyMOL script for structural analysis.

How It Works
Export the "Filtered Peptides" table from Deuteros and place it in the same folder as HDeXhausted.
Run the script and provide:
Protein length (number of amino acids)
Protein name (as in the PDB file)
Exported Deuteros table name (including .csv)

HDeXhausted maps statistically significant peptides onto the structure by:
Checking which amino acids appear in these peptides (excluding the first residue of each peptide).
Averaging the RFU (Relative Fractional Uptake) values for each amino acid.

The output includes:
A statistically significant heatmap
A PyMOL script for each exposure time to visualize the protein structure colored by RFU values
This enables intuitive visualization of hydrogen-deuterium exchange data on the protein structure.
