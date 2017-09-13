# Project_Vision

- **Building Rome in a Day**(2009)[[PDF](https://grail.cs.washington.edu/rome/rome_paper.pdf)][[Info](https://grail.cs.washington.edu/rome/)]
  - **Session 1**
    - Introduce
      - Search Image from website (flickr.com)
  - **Session 2**
    - PreProcessing and Feature Extraction
    ![](./img/pre-processing.png)
      + 유효한 이미지인지 확인한다.
      <br>(Verify that a valid image is valid.)
      + *[EXIF](https://sno.phy.queensu.ca/~phil/exiftool/TagNames/EXIF.html) 태그*를 확인하여 초점길이를 기록한다.
      <br>(Confirm the length of the focal point by checking the *[EXIF](https://sno.phy.queensu.ca/~phil/exiftool/TagNames/EXIF.html) tag*.)
      + 2 Mega-pixels 보다 큰 다운샘플링 이미지를 통해,종횡비를 유지하고 초점길이를 확장한다.
      <br>(Downsample images larger than 2 Mega-pixels,preserving aspect ratio and scaling focal lengths.)
      + 이미지를 그레이 스케일과 [SIFT](http://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_feature2d/py_sift_intro/py_sift_intro.html) 특징으로추출하고, 이를 추출한다. **[[도움](https://www.robots.ox.ac.uk/~vgg/research/affine/det_eval_files/lowe_ijcv2004.pdf)]**<br>(Converted to Grayscale and [SIFT](http://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_feature2d/py_sift_intro/py_sift_intro.html) features are extracted from here.) **[[help](https://www.robots.ox.ac.uk/~vgg/research/affine/det_eval_files/lowe_ijcv2004.pdf)]**
    - Matching
    - Geometric Estimation
  - **Session 3**
  - **Session 4**
  - **Session 5**
  
## 참고
- [README 쓰는 방법](https://stackedit.io/editor) (Stack_Edit)
