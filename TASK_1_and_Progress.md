The repository contains files from task 2, 3, 4 and 5. The task 5 follows usage of a binary and multiclass classification for a classical and a quantum solution for the entire dataset. We compare the results between the classical and quantum models to benchmark our work using the mentioned techniques.
Link of the dataset - https://drive.google.com/drive/folders/1suyH11AeLU66MSm2XM-6QFK-EKMrCZ8d?usp=sharing
In TASK-5 :
We have performed 9 models and run on the entire dataset of train images (5370) and test images as (27) in train folder and the model is entirely run on the test folder dataset. We have labled them -
{'170906-113317-Al 2mm-part3': 1,
 '170906-144958-Al 2mm': 1,
 '170904-141730-Al 2mm-part2': 2,
 '170904-151845-Al 2mm-part2': 2,
 '170906-153326-Al 2mm-part2': 2,
 '170904-141232-Al 2mm-part2': 2,
 '170913-151508-Al 2mm-part2': 2,
 '170904-150144-Al 2mm-part1': 2,
 '170913-143933-Al 2mm-part2': 2,
 '170913-152931-Al 2mm-part2': 2,
 '170906-141809-Al 2mm-part2': 2,
 '170815-134756-Al 2mm': 2,
 '170904-115959-Al 2mm': 2,
 '170815-133921-Al 2mm': 2,
 '170904-112347-Al 2mm': 2,
 '170904-145718-Al 2mm-part2': 4,
 '170904-141730-Al 2mm-part3': 4,
 '170905-110711-Al 2mm-part2': 4,
 '170904-141232-Al 2mm-part3': 4,
 '170913-155806-Al 2mm-part2': 4,
 '170904-152301-Al 2mm-part1': 4,
 '170904-113012-Al 2mm-part2': 4,
 '170904-154202-Al 2mm-part2': 4,
 '170904-155523-Al 2mm': 4,
 '170913-140725-Al 2mm': 4,
 '170913-152931-Al 2mm-part1': 0,
 '170913-151508-Al 2mm-part1': 0,
 '170913-143933-Al 2mm-part1': 0,
 '170904-141730-Al 2mm-part1': 0,
 '170904-145718-Al 2mm-part1': 0,
 '170913-142501-Al 2mm': 0,
 '170905-114307-Al 2mm': 0,
 '170905-115602-Al 2mm': 0,
 '170913-155806-Al 2mm-part1': 0,
 '170906-114912-Al 2mm': 0,
 '170906-141809-Al 2mm-part1': 0,
 '170906-120346-Al 2mm': 0,
 '170905-110711-Al 2mm-part1': 5,
 '170904-113012-Al 2mm-part1': 5,
 '170906-153326-Al 2mm-part1': 5,
 '170904-115503-Al 2mm': 5,
 '170904-141232-Al 2mm-part1': 5,
 '170904-151845-Al 2mm-part1': 5,
 '170906-150010-Al 2mm': 3,
 '170906-151353-Al 2mm': 3,
 '170906-150801-Al 2mm': 3}

 The 9 models that we performed are-
 1. Classical Convolutional Neural Network model and did binary classification (Train and test notebooks)
 2. Quantum Convolutional Neural Network model and did binary classification (Train and test notebooks)
 3. Classical Convolutional Neural Network model and did Multiclass classification (Train and test notebooks)
 4. Quantum Convolutional Neural Network model and did Multiclass classification (Train and test notebooks)
 5. Better pennylane train - An attempt has made to improvide the Quanvolutional Neural Network but the outputs took 2 hours to run but wasn't printable.
