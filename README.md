IronSight: Weapon Detection Using Computer Vision


Introduction
IronSight is a computer vision-based weapon detection system designed to enhance public safety in high-risk environments such as airports, schools, and malls. By leveraging YOLOv7 for object detection, IronSight aims to proactively identify threats and facilitate timely intervention.

Project Mission
The primary goal of this project is to develop a real-time, accurate, and scalable weapon detection system that can assist in mitigating security risks before they escalate.

Data Source
Dataset: DaSCI dataset, containing annotated images classified into two categories: guns and human objects.
Size: <1GB, making it lightweight and efficient for processing.
Preprocessing: Images are resized to 500 pixels for faster model inference.

Model Training
Framework: Python-based YOLOv7 (You Only Look Once), a state-of-the-art object detection model.
Approach:
Image annotation with bounding boxes.
Confidence threshold tuning for accuracy.
Iterative testing to refine detection capabilities.


Testing & Performance Evaluation
The model is validated using multiple testing approaches.
Performance metrics include precision, recall, and confidence levels.
Edge cases are handled through data augmentation and model fine-tuning.

Deployment
The project is open-source and available on GitHub for further enhancement.
Potential applications include academic research, law enforcement, and public surveillance systems.

Deliverable
Final Output: An efficient weapon detection model that visually identifies firearms in public spaces.
The system utilizes a pre-trained Haar Cascade Object Detection Model for additional verification.
Visualization: The detected weapon is highlighted with bounding boxes in real-time.

How to Run the Project
Clone the repository:
git clone (https://github.com/deeptiagrawal19/visual-ai-hack)
cd ironsight

Install dependencies:
pip install -r requirements.txt

Run the detection script:
python detect.py --source test_images/


Contributors
Urvansh Jignesh Shah
Cameron Murrill
Saanvi Kakde
Esther Abel
Deepti Ashok Agrawal
Sherwin Robinson Lobo
Ayan Sharma
Dharmik Rakeshkumar Shah

License
This project is released under the MIT License.

Acknowledgments
We appreciate the Voxel51 Hackathon for providing this platform and the DaSCI dataset for making this project possible.
Thank You!


For more details, visit our GitHub repository.
