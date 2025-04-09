## Pop-K MIDI Dataset

The Pop-K MIDI Dataset is an open collection of modern pop melodies developed for training and testing symbolic music models in a constrained musical domain. The dataset contains 305,815 files augmented from a base dataset of 8-bar vocal lead, chords, and bass melody tracks. An accompanying model trained on this dataset can be found on GitHub.

The dataset was created to evaluate how limited training data can be scaled via augmentation to efficiently train a model to generate a specific musical style. Additionally, the melodies were transposed to C major and A minor, with timing information normalized to 120 BPM at a 96-tick resolution. This results in a total duration of approximately 1360 hours of musical notation.


## License

The Pop-K MIDI Dataset is licensed under the Creative Commons Attribution-NonCommercial [(CC BY-NC)](https://creativecommons.org/licenses/by-nc/4.0/deed.en) license. While efforts have been made to augment and transform the original melodies, some segments may still resemble the source material.


## Download

See examples folder to preview MIDI and mp3 demos.

Direct Download (56.2MB) [popk_dataset_300k_mid.tar.gz](https://zenodo.org/records/14791511/files/popk_dataset_300k_mid.tar.gz?download=1)


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14791511.svg)](https://doi.org/10.5281/zenodo.14791511)

## Citation

If you use this dataset for a research or development project, please cite the following references:
```bash
@misc{Pop-K MIDI Dataset,
publisher = {Patchbanks},
title = {Pop-K: Augmented MIDI Dataset for Learning Constrained Modern Pop Melodies},
year = {2025},
doi = {10.5281/zenodo.14791511},
url = {https://doi.org/10.5281/zenodo.14791511},
}
```
## Additional Info

For any questions or feedback please contact us.
