# Waveform Silhouette (LaughNet)

This repo includes the implementation of waveform silhouette that was used to train the LaughNet model described in the paper ["LaughNet: synthesizing laughter utterances from waveform silhouettes and a single laughter example", Hieu-Thi Luong, Junichi Yamagishi](https://arxiv.org/abs/2110.04946). The module is declared in [silhouette.py](silhouette.py).

![Waveform Silhouette](p270_163_silh.png)

The experiments described in the LaughNet paper were based on [HiFi-GAN Vocoder Source Code](https://github.com/jik876/hifi-gan) which was kindly made available on github by the authors. If there are some details about the experiment that were not mentioned in the LaughNet paper, they are most likely default settings of HiFi-GAN.

A more details instruction about waveform silhouette can be found in the [interactive notebook](notebook.ipynb)

## Acknowledgment
- This study is supported by JST CREST grant JPMJCR18A6 and by MEXT KAKENHI grant 21K19808.
- English natural audio sample is from the [VCTK corpus](https://datashare.ed.ac.uk/handle/10283/3443), which is made available by the Centre for Speech Technology Research (CSTR) of the University of Edinburgh under an [Attribution 4.0 International (CC BY 4.0) lisence](https://datashare.ed.ac.uk/bitstream/handle/10283/3443/license_text?sequence=3&isAllowed=y).

## License
[MIT License](LICENSE)