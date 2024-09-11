# **Project Overview:** Synthetic Data Generation Using TimeGAN
This project demonstrates the use of TimeGAN to generate synthetic time series data. The workflow involves several key steps to preprocess the data, train the model, and produce new, realistic samples.

# **Key Steps:**
**Data Preprocessing:**

The data is normalized using MinMaxScaler to ensure consistent scaling of features. Necessary transformations are applied to convert categorical values into numeric formats for model compatibility.

**Model Training:**

The preprocessed data is reshaped into sequences and fed into a TimeGAN model, which is configured with GRU layers. The model learns the temporal patterns of the data and is trained over 2,000 epochs to capture realistic sequences.

**Synthetic Data Generation:**

Once trained, the model generates synthetic time series samples. The generated data is then rescaled back to its original range and saved in CSV format for further analysis.
