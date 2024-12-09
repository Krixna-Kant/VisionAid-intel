VisionAid is a Diabetic Retinopathy diagnosis model and multimodal user interface that is custom trained from an initial 69% accuracy to utilizing the Intel AI PC's NPU preprocess and train a transfer learning model of Resnet50 finetuned on a kaggle Diabetic Retinopathy dataset. 


6 different components of the OpenVINO ecosystem are utilized in the project. Qwen 2.5–0.6b-instruct is used as the natural language LLM, pulled from the OpenVINO repository toolkit, Intel's NPU Acceleration Library is utilized for preprocessing, Optimum is utilized for model export, TensorFlow and Pytorch OpenVINO integrations are utilized for the transfer learning.
