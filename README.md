# 3D Data Visualization with Matplotlib

A Python script demonstrating how to render three-dimensional visualizations using mpl_toolkits.mplot3d, matplotlib, and numpy.

---

## Key Features
### 3D Surface Plotting:

* Generates a smooth mathematical surface plot based on the function $Z = \sin(\sqrt{X^2 + Y^2})$.
* Utilizes custom color mapping (viridis) with adjusted transparency (alpha=0.85) and custom camera angles (view_init).
* Includes a integrated colorbar to map numerical values to visual colors dynamically.

<img src="visualisations/3D Surface: sin(√(x²+y²)).png" alt="3D Surface: sin(√(x²+y²))" width="600"/>

### 3D Scatter Plotting:

* Displays multidimensional random data points in 3D space.
* Maps a fourth dimension of data to the color spectrum using the plasma colormap.
* Adjusts point size (s=30) and opacity (alpha=0.7) for clearer data point density visualization4
  
<img src="visualisations/3D Scatter Plot.png" alt="3D Scatter Plot" width="600"/>


### Modular 3D Axis Setup:
Leverages Matplotlib's projection='3d' capability to easily extend standard 2D figures into fully interactive 3D spaces.

## Requirements
Ensure you have the following Python libraries installed:

pip install matplotlib numpy

### Quick Start

1. Clone this repository:

    git clone https://github.com/your-username/your-repo-name.git
   
    cd your-repo-name

3. Run the Python script:

    python main.py

## Example Visualisations
  The script outputs two distinct figures:

1. 3D Surface Plot: Displays a continuous mathematical wave pattern with custom camera perspectives and labeled axes.

2. 3D Scatter Plot: Renders 200 randomly distributed points with color-coded intensity values.
