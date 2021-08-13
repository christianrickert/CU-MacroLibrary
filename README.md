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
* [**`addRemainderRegion`**](https://github.com/christianrickert/CU-MacroLibrary/blob/34c62135ba6d890f0f8053c3e8fdcbc58522738b/Library.txt#L85): implements the missing `Substract` function for the ROI Manager.
* [**`endsWithEither`**](https://github.com/christianrickert/CU-MacroLibrary/blob/34c62135ba6d890f0f8053c3e8fdcbc58522738b/Library.txt#L145): simple test if a string ends with suffixes from a list.
* [**`getMedian`**](https://github.com/christianrickert/CU-MacroLibrary/blob/34c62135ba6d890f0f8053c3e8fdcbc58522738b/Library.txt#L183): calculates the median value within given threshold values.
* [**`getRoisFromMasks`**](https://github.com/christianrickert/CU-MacroLibrary/blob/34c62135ba6d890f0f8053c3e8fdcbc58522738b/Library.txt#L250): populates the ROI Manager with regions identified from a segmentation mask.
* [**`normalizePixelValues`**](https://github.com/christianrickert/CU-MacroLibrary/blob/34c62135ba6d890f0f8053c3e8fdcbc58522738b/Library.txt#L347): normalizes the pixel intensities of an image by its median value.
* [**`readImage`**](https://github.com/christianrickert/CU-MacroLibrary/blob/34c62135ba6d890f0f8053c3e8fdcbc58522738b/Library.txt#L377): reads image files with Bio-Format and labels the slices with the channel names.
* [**`rescalePixelValues`**](https://github.com/christianrickert/CU-MacroLibrary/blob/34c62135ba6d890f0f8053c3e8fdcbc58522738b/Library.txt#L455): rescales pixel intensities to a custom range, including `NaN` values.
* [**`setMasksFromRois`**](https://github.com/christianrickert/CU-MacroLibrary/blob/34c62135ba6d890f0f8053c3e8fdcbc58522738b/Library.txt#L519): creates a segmentation mask from available ROI Manager regions.
* [**`toggleBatchMode`**](https://github.com/christianrickert/CU-MacroLibrary/blob/34c62135ba6d890f0f8053c3e8fdcbc58522738b/Library.txt#L588): improves performance for image processing, selections, and ROI Manager updates.
* [**`waitForWindow`**](https://github.com/christianrickert/CU-MacroLibrary/blob/34c62135ba6d890f0f8053c3e8fdcbc58522738b/Library.txt#L681): halts the macro progression until a window with a specific title is available.

### Copyright notices
The [ImageJ2 image](https://github.com/imagej/imagej.github.io/blob/main/media/icons/imagej-shadow.png) is part of the [GitHub Pages for ImageJ](https://github.com/imagej/imagej.github.io).
