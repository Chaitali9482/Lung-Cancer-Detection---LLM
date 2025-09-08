
colab link - https://colab.research.google.com/drive/1KIHaHtwpfgfa68eYx6qRypJkMsiy0ZGR?usp=sharing
 
 
 
 
 
 This project looks at different methods to detect lung cancer from chest
 X-rays. I began with a simple CNN, then used transfer learning with frozen and fine
tuned models, and finally tested a feature-based method with Isolation Forest. The
 f
 ine-tuned model gave the best accuracy, while the feature-based approach made the
 results easier to explain. The work also included preprocessing (grayscale, denoising,
 CLAHE), performance metrics, and confusion-matrix analysis. Overall, the study shows
 the trade-off between accuracy and explainability, and suggests that combining both can
 be useful for research and education.


  Dataset
 The dataset followed a simple folder structure with two classes:
 • Normal– chest X-rays without signs of cancer.(from Kaggle)
 • Cancer– chest X-rays with abnormal regions.(from Kaggle)

<img width="1057" height="295" alt="Screenshot 2025-09-08 223105" src="https://github.com/user-attachments/assets/4ef3963a-dce1-4f1e-b4e9-8532ed6f8e8f" />



 <img width="653" height="737" alt="image" src="https://github.com/user-attachments/assets/3ad1b57c-872c-4ab3-bc42-f77abcbdb358" />



<img width="576" height="788" alt="image" src="https://github.com/user-attachments/assets/222abf59-7a36-42a5-8d68-ab7896fc9d8d" />
