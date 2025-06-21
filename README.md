# 🗑️ Garbage Classification - Week 1

A deep learning-based image classification project developed as part of an internship with **AICTE Edunet Foundation**. The goal is to automate waste segregation using a Convolutional Neural Network (CNN) trained on real-world garbage images.











## 🎯 Project Purpose

This project was undertaken as part of an internship with the **AICTE Edunet Foundation**, under the domain of **Artificial Intelligence & Machine Learning for Garbage Classification**.

The objective is to build an AI-powered system using deep learning techniques (CNNs) to classify images of waste into categories such as plastic, glass, metal, etc. This project supports smart city initiatives and promotes environmental sustainability through technology.







## 📌 Project Highlights

- **Objective**: Automatically classify garbage images into one of six categories.
- **Approach**: Transfer learning with EfficientNetV2B2 in TensorFlow/Keras.
- **Categories**: Cardboard, Glass, Metal, Paper, Plastic, Trash.
- **Tech Stack**: Python, TensorFlow, NumPy, Matplotlib, Seaborn, Scikit-learn, Gradio.
- **Environment**: Google Colab (GPU enabled)






## 🗂️ Dataset Download

The dataset is hosted on Google Drive due to GitHub size limitations.

📥 **[Download Dataset from Google Drive](https://drive.google.com/uc?export=download&id=1JRRR4mWA3jhSJl3GPeCY9ZxZ4pdEHQtT)**






project-root/
│
├── garbage_classification.ipynb





├── garbage_data/



 
│ └── Garbage classification/





│ └── Garbage classification/





│ ├── cardboard/





│ ├── glass/







│ ├── metal/







│ ├── paper/









│ ├── plastic/













│ └── trash/





##  Installation








Install the required dependencies:









pip install tensorflow numpy matplotlib seaborn scikit-learn gradio
or





pip install -r requirements.txt






🚀 Project Workflow (Progress)





Step	Status


Mount & extract dataset from Drive	       ✅ Done




Data loading and visualization	           ✅ Done




Model building with EfficientNetV2B2	   ⏳ In Progress




Evaluation and metrics	                   ⏳ To Do






Gradio interface for predictions	       ⏳ To Do







🧪 Sample Output (So Far)





(Displaying 12 sample images from training set)








plt.figure(figsize=(10, 10))









for images, labels in train_ds.take(1):







    for i in range(12):







    
        ax = plt.subplot(4, 3, i + 1)






        
        plt.imshow(images[i].numpy().astype("uint8"))







        
        plt.title(train_ds.class_names[labels[i]])








        
        plt.axis("off")







        
✅ What You Should Do Next









Task	                             Action




   
🧠 Train Model	               Complete training using EfficientNetV2B2







📈 Add Results	              Include accuracy/loss curves and confusion matrix








🌐 Deploy with Gradio     	  Build a user interface to classify new images










📝 Update Author Info	      Add your real name, GitHub, email, and LinkedIn











📦 Add requirements.txt    	  Use extracted libraries (already listed above)








🤝 Contribution Guidelines






Pull requests are welcome. For major changes, please open an issue first to discuss.









📄 License








Distributed under the MIT License. See LICENSE for more information.





🙋‍♂️ Author








Yerragudi Chaitanya








📧 Email: chaitanya222reddy@gmail.com









LinkedIn: https://www.linkedin.com/in/yerragudi-chaitanya-9730a0301/









GitHub:github.com/YerragudiChaitanya
 




    
