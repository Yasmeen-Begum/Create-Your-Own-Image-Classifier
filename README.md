# Create-Your-Own-Image-Classifer
# Image Classifier - Part 1 - Development

-Developing an Image Classifier with Deep Learning

--sanity-check

![Screenshot (286)](https://github.com/Yasmeen-Begum/Create-Your-Own-Image-Classifier/assets/91931504/b06e7f6e-4f65-448a-be1b-fad8922288d3)

--predicting the image

![Screenshot (287)](https://github.com/Yasmeen-Begum/Create-Your-Own-Image-Classifier/assets/91931504/e1f4badf-b6d8-4ee1-94fc-585cd3a08c0e)



# Image Classifier - Part 2 - Command Line App

- Building the command line application

--for train.py

python train.py flowers --learning_rate 0.01 --epochs 5

Train Loss: 4.43

Valid Loss: 4.22

Accuracy: 10.88%

model saved to ../saved_models/checkpoint.pth

--For predict.py

python predict.py './flowers/test/63/image_05882.jpg' --top_k 5 '../saved_models/checkpoint.pth'  --gpu

Predictions:

#0   petunia                   Prob: 2.73%

#1   rose                      Prob: 2.16%

#2   water lily                Prob: 1.96%

#3   lotus lotus               Prob: 1.90%

#4   cyclamen                  Prob: 1.81%

