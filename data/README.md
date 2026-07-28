# Dataset

This project uses the **Suicide_Ideation_Dataset (Twitter-based)** dataset obtained from Kaggle.

The dataset contains labeled tweets classified into two categories:

- Not Suicide Post
- Potential Suicide Post

## Dataset Source

The original dataset is available on Kaggle:

[Suicide Ideation Dataset (Twitter-based)](https://www.kaggle.com/datasets/aunanya875/suicidal-tweet-detection-dataset)

## License

The dataset is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)** license.

License information:

https://creativecommons.org/licenses/by-nc-sa/4.0/

The dataset is being used for educational and non-commercial purposes.

## Modifications

The dataset was modified for this machine learning project. The following preprocessing steps were performed:

- Removed rows with missing tweet text
- Removed duplicate tweets
- Removed leading and trailing whitespace from classification labels
- Converted text classification labels into numerical values

The original dataset was not modified at the source. The preprocessing described above was performed as part of this project.

## Target Variable

The original `Suicide` column contains two text labels:

- `Not Suicide post`
- `Potential Suicide post`

For machine learning, these labels were converted to:

- `0` = Not Suicide Post
- `1` = Potential Suicide Post

## Attribution

The dataset is attributed to its original creator and is used under the terms of the CC BY-NC-SA 4.0 license.

This project does not claim ownership of the original dataset.

## Disclaimer

This dataset and project involve sensitive content related to suicide ideation.

This project is intended for educational and machine learning purposes only. The resulting model should not be used as a diagnostic or clinical tool and should not be used to determine whether an individual is suicidal.
