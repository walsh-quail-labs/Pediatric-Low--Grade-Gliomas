# Cell Type Visualization Tool For Pediatric-Low--Grade-Gliomas

This script generates overview figures of segmented cell nuclei overlaid with cell type color coding. It takes `.mat` files containing cell segmentation boundaries and cell type annotations, along with a color map Excel file, and outputs annotated PNG figures.

---

## Input Files

- **CellType/\***: MATLAB `.mat` files with `cellTypes` array
- **Segmentation/\***: MATLAB `.mat` files with `Boundaries` and `nucleiImage`
- **allCellTypesRGBMapping.xlsx**: Excel sheet mapping cell type names to RGB colors

---

## Output

For each sample, the script creates a composite figure with 3 panels:

1. Raw nuclei image
2. Nuclei with outlines
3. Cell type-colored image

---

## Usage

1. Place your input files in the appropriate folders:

   - `CellType/`
   - `Segmentation/`
   - `allCellTypesRGBMapping.xlsx` in the root directory
2. Run the notebook
