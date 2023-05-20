# mtailor-edwin-ml-test
This is the Github repository for Mtailor for performing the task provided in pytorch

# To Re-train the Model
After uploading the notebook or collab or an IDE:

- Specify the path to the model weights in the line in the Testing Model section where the MODEL_PATH is the path to the uploaded model weights while the `best_model.pth` is the uploaded model weight
  - `model_weights = f"{MODEL_PATH}/best_model.pth"`
-  Run the notebook mainly the Model class and the section for continuing training the model and change the num of epochs for the model

# To Perform Inference with the saved weights

- Specify the path to the model weights in the line in the Testing Model section where the MODEL_PATH is the path to the uploaded model weights while the `best_model.pth` is the uploaded model weight
  - `model_weights = f"{MODEL_PATH}/best_model.pth"`
-  Run the notebook mainly the Model class and the mapping of the different encoded classes of the data
-  Run the visualization function and the predicted image will be drawn in addition to a dictionary of the output in the format
   -  `{
        "has_object": True,
        "cat_or_dog": "cat",
        "specie": "persian",
        "xmin": 10,
        "ymin": 10,
        "xmax": 10,
        "ymax": 10
    }`