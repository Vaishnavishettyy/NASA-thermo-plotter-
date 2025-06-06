# NASA Thermodynamic Species Plotter

This is a simple web-based tool that allows users to upload NASA thermodynamic data files and visualize the properties of chemical species over a temperature range. The tool plots Cp/R (heat capacity), H/RT (enthalpy), and S/R (entropy) using the NASA 7-coefficient polynomial equations.

## Features

- Upload `.dat`, `.txt`, `.csv`, or `.pdf` files containing NASA-format thermodynamic data
- Automatically detects and lists available species from the file
- Select a species and view its thermodynamic plots:
  - Cp/R vs Temperature
  - H/RT vs Temperature
  - S/R vs Temperature
- Download any chart as a PNG image
- Debug mode (press Ctrl + D) to view logs and parsing details
- No backend required – runs completely in the browser

## How to Use

1. Open the website.
2. Upload your NASA thermodynamic data file.
3. Choose a species from the dropdown.
4. View the plots for Cp/R, H/RT, and S/R vs Temperature.
5. Click "Save Plot" to download any graph.


