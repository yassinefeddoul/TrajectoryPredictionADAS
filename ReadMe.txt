The aim of this project is to track moving objects in order to predict their trajectories.
You'll find a report summarizing the work we've done and our practical realization in the attached file.
In the Code_Prediction folder you'll find all the tools needed to test the program and its realization.
We've used transfer learning in the first part, where you'll find 'weights' used in the weights folder. If you want to redo the work, you'll need to transform the weights into a .tf file in extension using the code available in the convert weights to tf.ipynb file, otherwise you'll find the transformed file in the weights file.
Files available in the deep_sort and tools folders are necessary modules to be imported into the main code, so they must be in the same folder to avoid import errors.
In the Prediction.ipynb code file you'll find part:
- Part One is devoted to generating and structuring the data to encapsulate the prediction model, using various SVR, MLP Regressor and linear regression models we've recorded.
- Part Two, where we implemented data structuring to predict the trajectories of moving objects in real time.
- In Part 3, we connected the camera of a mobile phone to its IP, ensuring that any camera could be connected to our algorithm for either real-time tracking or real-time prediction.

Developed by:
FEDDOUL YASSINE
