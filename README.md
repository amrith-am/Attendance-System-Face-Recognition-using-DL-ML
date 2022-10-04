
# Attendance System Face Recognition using DL & ML


## Block Diagram

Here we are using cafe and pytorh frameworks, using that we detect and extract the features and covert into blob file
. I explaint the code in line by line in the code files.

for get more accurate use more images

![Untitled](https://user-images.githubusercontent.com/61175452/193825720-69990246-d8b8-4973-84f8-35416339fb3f.png)

## Installing Libraries

sklearn
```bash
  pip install sklearn

```
    
## Creating Face Dataset & Registering Name and Roll Number in CSV file 

Run the 1_datasetCreation.py file

And put the Name, Role Number and it will create Dataset

![Untitled](https://user-images.githubusercontent.com/61175452/193837830-81d67370-312a-45f9-bdfe-107bdd7b1500.png)

## Preprocessing & Extracting features of Dataset as Embeddings using DL

Run the 2_preprocessingEmbeddings.py file

![Untitled](https://user-images.githubusercontent.com/61175452/193845399-d2e5f488-81e5-4d40-ac06-9b43ee1bcdad.png)

## Training with ML

Then run 3_trainingFaceML.py file

![Untitled](https://user-images.githubusercontent.com/61175452/193850637-f052493c-bebf-4cba-92d3-efc6b98817ed.png)


## Training with ML

Finaly run the 4_recognizingPerson.py file

![Untitled](https://user-images.githubusercontent.com/61175452/193852011-92d6f9e3-ae13-41e2-9dbe-435846e308c5.png)


Done! It's Successfully  Detected
