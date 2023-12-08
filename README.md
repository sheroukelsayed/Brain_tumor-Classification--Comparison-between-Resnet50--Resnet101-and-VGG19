# Brain_tumor-Classification--Comparison-between-Resnet50--Resnet101-and-VGG19
Data file: Read Dataset and label them :
Sure, here are the steps without code:

1. **Mount Google Drive:**
   - Connect Google Drive to your Colab notebook for file access.

2. **Set Paths:**
   - Define the paths for the training and testing datasets.

3. **Create DataFrames:**
   - Initialize empty DataFrames for both training and testing data.

4. **Load File Lists:**
   - Retrieve lists of files in the training and testing directories.

5. **Create Training Data:**
   - Generate a data frame for training data, incorporating image paths and labels.

6. **Map Labels:**
   - Convert labels into numeric values.

7. **Create Testing Data:**
   - Form a DataFrame for testing data with image paths and labels.

8. **Map Labels for Testing Data:**
   - Assign numeric values to labels in the testing data.

9. **Display DataFrame Information:**
   - Show information about the structure of the dataframes.

10. **Save DataFrames to CSV:**
    - Save the training and testing dataframes as CSV files.

11. **Display a Sample Image Path:**
    - Present an example image path from the testing dataframe.
   
Training File : Training Resnet50, Resnet101, and VGG19 on datasets and evaluate validation and training data:
1. **Mount Google Drive:**
   - Connect Google Drive to Colab for file access.

2. **Load DataFrames:**
   - Load training and testing data into DataFrames.

3. **Shuffle Training Data:**
   - Shuffle the training DataFrame for better model training.

4. **Read Testing Data:**
   - Read the testing data into a DataFrame.

5. **Preprocess Images:**
   - Use OpenCV to read, resize, and preprocess images from both training and testing datasets.

6. **Convert Data to Numpy Arrays:**
   - Convert image and label lists to numpy arrays.

7. **Map Labels:**
   - Map categorical labels to numerical values.

8. **Split Data:**
   - Split the dataset into training and validation sets.

9. **Load Pre-trained Model:**
   - Load a pre-trained ResNet101 model and freeze its layers.

10. **Build Custom Classifier:**
    - Add a custom classifier on top of the ResNet101 model.

11. **Compile and Train Model:**
    - Compile and train the model using training data.

12. **Save Model:**
    - Save the trained model.

13. **Repeat for ResNet50 and VGG19:**
    - Repeat steps 9-12 for ResNet50 and VGG19.

14. **Evaluate Models on Validation Data:**
    - Use validation data to evaluate accuracy and F1-score for each model.

15. **Bar Chart for Validation Metrics:**
    - Create a bar chart to compare validation accuracy and F1-score across models.

16. **Evaluate Models on Test Data:**
    - Use test data to evaluate accuracy and F1-score for each model.

17. **Bar Chart for Test Metrics:**
    - Create a bar chart to compare test accuracy and F1-score across models.

18. **Display Comparative Charts:**
    - Display all comparative charts for both validation and test metrics.

