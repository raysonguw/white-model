# White Model
Ray Song 
2022 Fall

## Description
What would you do with a white paper? Will you write something on it? Or will you fold it into geometric shapes? 

The installation asks the audience to use their own creativity to change the position of the white paper, lights and camera, and the AI will understand the audience's creation and output a text in English and Chinese. The audience will experience the importance of white paper as a symbol of representation in the current Chinese social environment, and how audience participation can promote the use of this symbol not only in Chinese contexts, but also in a wider range of applications.

## Workflow
1. The audience folds and places a whilte paper, moves the light and the camera.
2. The camera will take a picture when the user clicks the button on the monitor. 
3. The picture taken by the camera will be sent to COCO model to generate a summary of the picture using GPT-2. 
4. Then the summary will be sent to GPT-3 to generate text to extend the summary.

## Hardware
- Webcam: [Logitech C925e](https://www.logitech.com/en-us/products/webcams/c925e-business-webcam.960-001075.html)
- Box: Home Depot
- Lights & Monitor Provided by DXARTS
- White Papers Provided by White Paper Movement on the UW campus

## Software
- Interface: [Gradio](https://gradio.app/)
- Image Dataset: [COCO](https://cocodataset.org/#home)
- AI Model: [GPT-2 & GPT-3](https://openai.com/)
- Programming Language: Python

## Images
<img width=60% src="https://github.com/raysonguw/white-model/blob/main/white_model.jpg" alt="White Model">
<img width=60% src="https://github.com/raysonguw/white-model/blob/main/white_model_cam_lights.jpg" alt="Cam and Lights">
<img width=60% src="https://github.com/raysonguw/white-model/blob/main/white_model_monitor.jpg" alt="Monitor">

### Reference
* [Memes, Puns and Blank Sheets of Paper: China’s Creative Acts of Protest](https://www.nytimes.com/2022/11/28/world/asia/china-protests-blank-sheets.html)
* [Blank sheets of paper become symbol of defiance in China protests](https://www.reuters.com/world/china/blank-sheets-paper-become-symbol-defiance-china-protests-2022-11-27/)
* [Image to Text Summary by Muhammad Sohaib](https://huggingface.co/spaces/sohaibcs1/Image-to-Text-Summary)
* [GPT3 API](https://openai.com/api/)
* [COCO Dataset](https://cocodataset.org/#home)
