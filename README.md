# CatDetect: YOLOv8-based Object Detection for Snapchat Lens

Welcome to the CatDetect GitHub repository! CatDetect is a cutting-edge object detection model that leverages the power of YOLOv8, tailored specifically for identifying cats in images and videos. Developed during the Spring 2024 externship, this model is optimized for integration with Snapchat Lens Studio, enabling creators to bring to life engaging and interactive experiences with real-world cat detection capabilities.

![Cat2](https://github.com/rilozos/CatDetect/assets/112525112/ec02f396-bf7d-414b-ac88-de97aa9e6f0d)

## Features

- **High Accuracy**: Utilizes YOLOv8 for object detection precision on cat images.
- **Optimized for Snapchat**: Inlcudes exported .onnx file compatible with Snapchat Lens Studio for seamless integration.
- **Custom Cat Dataset**: Trained on a robust and diverse custom cat dataset provided by Roboflow, ensuring broad recognition capabilities across different cat breeds and environments.
- **Real-Time Performance**: Engineered for real-time cat detection in Snapchat Lenses

### Integrate with Snapchat

1. Open Snapchat Lens Studio and create a new project.
2. From command line, navigate to runs/detect/train3 and use: yolo export model=best.pt format=onnx  
3. Import the CatDetect model into your project using the best.onnx file.
4. Follow the [official Lens Studio documentation]([https://lensstudio.snapchat.com/guides/](https://docs.snap.com/lens-studio/references/templates/ml/custom-segmentation#importing-your-model)) to link the model output to your lens effects.
5. Test the lens in the Lens Studio preview or on your device.
