# Automated Drowning Detection

This repository presents a comprehensive solution for automated drowning detection leveraging deep learning models and advanced methodologies. Our work focuses on revolutionizing drowning incident response systems by swiftly identifying distress situations in aquatic environments.

## Methodology Highlights

Our approach involved rigorous model refinement to achieve accurate drowning detection:
- **Initial Model Training:** We initially trained the YOLO v8 architecture on a [dataset](https://universe.roboflow.com/object-detection-model/drowning-detection-wqiom) but encountered suboptimal detection results.
- **Dataset Analysis:** Recognizing the limitations, we integrated a secondary dataset, [Team Burraq via Roboflow Universe](https://universe.roboflow.com/team-burraq/drowning-detection-main), to augment our model's understanding of varied drowning scenarios.
- **Fine-Tuning for Enhanced Precision:** To address the limitations observed in initial detection, we subjected the previously trained model to a further 20 epochs of fine-tuning on the new dataset. This refined training significantly improved detection accuracy and sensitivity, evident in the detection images included.

## Key Features
- **Dataset Collection and Cleaning:** Curated diverse datasets from reputable sources, ensuring comprehensive coverage of drowning scenarios.
- **Model Selection and Fine-Tuning:** Employed YOLO v8 architecture, fine-tuning it exclusively for drowning instances to enhance accuracy and sensitivity.
- **Integration and Refinement:** Integrated secondary datasets to further refine the model's understanding of varied drowning scenarios.
- **Code Implementation:** Utilized Ultralytics library for seamless model loading and image analysis, facilitating efficient drowning instance detection.
- **Coordinate Calculation Methodology:** Incorporated coordinate calculation to precisely determine spatial coordinates of detected objects, enhancing object localization.
- **Integration with Real-Life Pool Cameras and Depth Estimation Sensors:** Worked towards integrating the detection system with pool cameras and depth estimation sensors for real-time spatial analysis.
- **Conclusion and Future Recommendations:** Summarized findings, highlighting accuracy improvements and proposed future enhancements for real-time drowning detection systems.

## Dataset Used
- **First Dataset:** [Roboflow Universe](https://universe.roboflow.com/object-detection-model/drowning-detection-wqiom)
- **Second Dataset:** [Team Burraq via Roboflow Universe](https://universe.roboflow.com/team-burraq/drowning-detection-main)

## Sample Detection Images
![WhatsApp Image 2023-12-10 at 12 38 25 PM (1)](https://github.com/Hasibwajid/Automated-Drowning-Detection-YOLOV8/assets/72168225/1796c6c3-e36c-4866-8a0e-97053717981e)
![WhatsApp Image 2023-12-10 at 12 37 08 PM](https://github.com/Hasibwajid/Automated-Drowning-Detection-YOLOV8/assets/72168225/2c4c93ac-497e-497d-bbec-58fda3de8b8c)

## Usage
Detailed instructions and code implementation for automated drowning detection are provided in this repo.
