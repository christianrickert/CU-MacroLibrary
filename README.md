![imagej-icon](https://user-images.githubusercontent.com/19319377/120248289-bfaf7600-c233-11eb-92b1-7888bc28de61.png)

# CU-MacroLibrary
## ImageJ2 macro library with variables and functions
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4885048.svg)](https://doi.org/10.5281/zenodo.4885048)

### Software requirements
CU-MacroLibrary requires a recent version of the [Fiji](https://fiji.sc/) image processing package:
* ImageJ2 executable (>= 1.53e)
* Bio-Formats plugin (>= 6.4.0)

### Software installation
To install the CU-MacroLibrary with your copy of Fiji, simply copy the `Library.txt`
to `Fiji.app\macros\` and its content will be available to any executed or installed macro.
In addition, ImageJ2's macro editor will autocomplete function names from the library.

### Available macro functions (selection)
* [**`addRemainderRegion`**](https://github.com/christianrickert/CU-MacroLibrary/blob/01e090f27a5972f12068f66cdf5e228bba7889ec/Library.txt#L84): implements the missing `Substract` function for the ROI Manager.
* [**`endsWithEither`**](https://github.com/christianrickert/CU-MacroLibrary/blob/01e090f27a5972f12068f66cdf5e228bba7889ec/Library.txt#L144): simple test if a string ends with suffixes from a list.
* [**`getMedian`**](https://github.com/christianrickert/CU-MacroLibrary/blob/01e090f27a5972f12068f66cdf5e228bba7889ec/Library.txt#L182): calculates the median value within given threshold values.
* [**`getRoisFromMasks`**](https://github.com/christianrickert/CU-MacroLibrary/blob/01e090f27a5972f12068f66cdf5e228bba7889ec/Library.txt#L237): populates the ROI Manager with regions identified from a segmentation mask.
* [**`normalizePixelValues`**](https://github.com/christianrickert/CU-MacroLibrary/blob/01e090f27a5972f12068f66cdf5e228bba7889ec/Library.txt#L316): normalizes the pixel intensities of an image by its median value.
* [**`readImage`**](https://github.com/christianrickert/CU-MacroLibrary/blob/01e090f27a5972f12068f66cdf5e228bba7889ec/Library.txt#L346): reads image files with Bio-Format and labels the slices with the channel names.
* [**`rescalePixelValues`**](https://github.com/christianrickert/CU-MacroLibrary/blob/01e090f27a5972f12068f66cdf5e228bba7889ec/Library.txt#L424): rescales pixel intensities to a custom range, including `NaN` values.
* [**`setMasksFromRois`**](https://github.com/christianrickert/CU-MacroLibrary/blob/01e090f27a5972f12068f66cdf5e228bba7889ec/Library.txt#L488): creates a segmentation mask from available ROI Manager regions.
* [**`toggleBatchMode`**](https://github.com/christianrickert/CU-MacroLibrary/blob/01e090f27a5972f12068f66cdf5e228bba7889ec/Library.txt#L539): improves performance for image processing, selections, and ROI Manager updates.
* [**`waitForWindow`**](https://github.com/christianrickert/CU-MacroLibrary/blob/01e090f27a5972f12068f66cdf5e228bba7889ec/Library.txt#L632): halts the macro progression until a window with a specific title is available.

### Copyright notices
The [ImageJ2 image](https://github.com/imagej/imagej.github.io/blob/main/media/icons/imagej-shadow.png) is part of the [GitHub Pages for ImageJ](https://github.com/imagej/imagej.github.io).
