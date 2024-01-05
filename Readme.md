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
