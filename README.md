# OCR Dataset Classification for License Plate Recognition

This project was inspired by the [License-Plate-Recognition dataset](https://github.com/trungdinh22/License-Plate-Recognition), which contains thousands of Vietnamese vehicle images for license plate detection and recognition.

However, not all images are suitable for automatic OCR processing — many are blurry, low-resolution, or misaligned. This project aims to **automatically classify** the dataset into two categories:

- `standard/`: Images that can be processed directly with OCR engines like PaddleOCR.
- `blur/`: Images that require manual labeling.

From the original 3,066 images, 2,646 were successfully processed automatically. The remaining 420 need manual work.

This project showcases:
- **Data preprocessing & image classification using OCR confidence.**
- **Automation to reduce manual annotation workload.**
- A potential step toward building more robust OCR datasets.

🔧 Tools used: Python, PaddleOCR, Tesseract, LabelImg
 
## Folder Structure

- `standard/`: High-quality images for OCR.
- `blur/`: Challenging cases that need manual labeling.

## Use Case

The dataset was used in a pipeline to detect license plates and recognize characters using OCR, combining PaddleOCR and YOLOv8 for preprocessing.

## Author

Alex Tu
🔗 linkedin.com/in/tu-nguyen-1a995116b
📧 Email: nguyencongtu.tn@gmail.com
