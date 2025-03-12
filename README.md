# Mixed-granularity Implicit Representation for Continuous Hyperspectral Compressive Reconstruction (MGIR)

Jianan Li, Huan Chen, Wangcai Zhao, Rui Chen, Tingfa Xu

**Abstract:** Hyperspectral Images (HSIs) are crucial across numerous fields but are hindered by the long acquisition times associated with traditional spectrometers. The Coded Aperture Snapshot Spectral Imaging (CASSI) system mitigates this issue through a compression technique that accelerates the acquisition process. However, reconstructing HSIs from compressed data presents challenges due to fixed spatial and spectral resolution constraints. This study introduces a novel method using Implicit Neural Representation for continuous hyperspectral image reconstruction. We propose the Mixed Granularity Implicit Representation (MGIR) framework, which includes a Hierarchical Spectral-Spatial Implicit Encoder for efficient multi-scale implicit feature extraction. This is complemented by a Mixed-Granularity Local Feature Aggregator that adaptively integrates local features across scales, combined with a decoder that merges coordinate information for precise reconstruction. By leveraging implicit neural representations, the MGIR framework enables reconstruction at any desired spatial-spectral resolution, significantly enhancing the flexibility and adaptability of the CASSI system. Extensive experimental evaluations confirm that our model produces reconstructed images at arbitrary resolutions and matches state-of-the-art methods across varying spectral-spatial compression ratios.

