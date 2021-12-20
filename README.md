## OCR Benchmarks

State-of-art OCR papers.

## Scene Text Detection

**Scene Text Detection** is a task to detect text regions in the complex background and label them with bounding boxes.

- `*CODE` means official code .
- F-Measure as metrics .

| Model                 | input | Date | Paper                                                        | IC-13 | IC-15 | Total-Text | CTW-1500 | FPS  | S.C.                                             |
| --------------------- | ----- | ---- | ------------------------------------------------------------ | ----- | ----- | ---------- | -------- | ---- | ------------------------------------------------ |
| DB-ResNet50           | 1152  |      |                                                              |       | 87.2  |            |          | 12   | [*pytorch](https://github.com/MhLiao/DB)         |
| DB-ResNet50           | 736   |      |                                                              |       | 85.4  | 84.6       |          |      | [*pytorch](https://github.com/MhLiao/DB)         |
| DB-ResNet18           | 736   | 2019 | [DB](https://arxiv.org/pdf/1911.08947v2.pdf)                 |       | 82.3  | 82.9       |          |      | [*pytorch](https://github.com/MhLiao/DB)         |
| TextFuseNet-ResNet50  |       | 2020 | [TextFuseNet](https://www.ijcai.org/Proceedings/2020/0072.pdf) | 92.2  | 90.1  | 85.3       | 85.4     | 7.7  | [pytorch](https://github.com/ying09/TextFuseNet) |
| TextFuseNet-ResNet101 |       | 2020 | [TextFuseNet](https://www.ijcai.org/Proceedings/2020/0072.pdf) | 94.3  | 92.1  | 87.1       | 86.6     | 4.0  | [pytorch](https://github.com/ying09/TextFuseNet) |



## Scene Text Recognition

- `*CODE` means official code .
- `*None` means empty official rep without code .

| Model                       | Date | Paper                                                        | IC03 | IC13  | IC15  | SVT   | S.C                                                          |
| --------------------------- | ---- | ------------------------------------------------------------ | ---- | ----- | ----- | ----- | ------------------------------------------------------------ |
| CRNN                        | 2015 | [CRNN](https://arxiv.org/pdf/1507.05717v1.pdf)               | 89.4 | 86.7  |       | 80.8  | [*torch](https://github.com/bgshih/crnn)  [pytorch](https://github.com/meijieru/crnn.pytorch) |
| DAN                         | 2019 | [DAN](https://arxiv.org/pdf/1912.10205v1.pdf)                | 95.0 | 93.9  | 74.5  | 89.2  | [*pytorch](https://github.com/Wang-Tianwei/Decoupled-attention-network) |
| CDistNet                    | 2021 | [CDistNet](https://arxiv.org/abs/2111.11011)                 | -    | 97.67 | 86.25 | 93.82 | [*None](https://github.com/simplify23/CDistNet) [pytorch](https://github.com/chibohe/CdistNet-pytorch) |
| Yet Another Text Recognizer | 2021 | [Why You Should Try the Real Data for the Scene Text Recognition](https://arxiv.org/pdf/2107.13938v1.pdf) | 97.1 | 96.8  | 80.2  | 94.7  | [*OpenVINO](https://github.com/openvinotoolkit/training_extensions) |



## refence

1. [awesome-deep-text-detection-recognition](https://github.com/hwalsuklee/awesome-deep-text-detection-recognition)

2. [Scene Text Detection](https://paperswithcode.com/task/scene-text-detection)

   