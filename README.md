# LCAT-Net: Lightweight Context-Aware Deep Learning Approach for Teeth Segmentation in Panoramic X-rays

## Overview

LCAT-Net is a deep learning model designed to segment teeth in panoramic X-ray images accurately. By preserving both contextual and fine-grained details, LCAT-Net addresses challenges such as blurred interdental boundaries, noise variations, and overlapping dental structures. The model introduces a novel Multi-scale Context Fusion (MCF) block to effectively capture and fuse features from multiple scales, enabling more accurate segmentation of dental structures of varying sizes and orientations. Additionally, a dense skip connection module (DSM) allows each decoder layer to combine details from the symmetric encoder layer and all upper encoder layers.

## Access the Code

The implementation of LCAT-Net is available in the following Jupyter Notebook:
[LCAT-Net notebook (kaggle)](https://www.kaggle.com/code/kanouar/lcat-net-lightweight-context-aware-network)

This notebook provides a comprehensive walkthrough of the model architecture, training process, and evaluation metrics. Users can interact with the code, modify parameters, and visualize results directly within the notebook.

## Citation

If you find LCAT-Net useful in your research or applications, please consider citing our work:

```bibtex
@article{khaldi2024lcat,
  title={LCAT-Net: Lightweight Context-Aware Deep Learning Approach for Teeth Segmentation in Panoramic X-rays},
  author={Khaldi, Anouar and Khaldi, Belal and Aiadi, Oussama},
  journal={International Journal of Computational Intelligence Systems},
  volume={17},
  number={1},
  pages={1--17},
  year={2024},
  publisher={Springer}
}
```

For more details, you can access the full article [here](https://doi.org/10.1007/s44196-024-00703-5).

## License

This project is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License. This permits any non-commercial use, sharing, distribution, and reproduction in any medium or format, as long as appropriate credit is given to the original authors and source. For more details, please refer to the [license terms](https://creativecommons.org/licenses/by-nc-nd/4.0/).


For any questions or further information, please get in touch with the corresponding author:

**Anouar Khaldi**

Department of Computer Science and Information Technologies, Kasdi Merbah University, Ouargla, 30000, Algeria
Email: [kld.anouar@gmail.com](mailto:kld.anouar@gmail.com)

We appreciate your interest in LCAT-Net and welcome any feedback or contributions to enhance this work.
