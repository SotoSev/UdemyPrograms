## 🎬 Movie Recommendation System using Restricted Boltzmann Machines (RBM)

This project implements a movie recommendation system using a Restricted Boltzmann Machine (RBM) built with PyTorch. The goal is to predict whether a user will like or dislike a movie based on historical rating data.

### 📌 Project Overview

The model is trained on the MovieLens dataset, which contains user–movie ratings. By learning latent features from user preferences, the RBM can recommend movies a user is likely to enjoy.

The ratings are converted into a binary preference system:
  - 1 → Liked (rating ≥ 3)

  - 0 → Not liked (rating 1–2)

  - -1 → Unrated / Missing data
    
This approach allows the RBM to focus on preference patterns rather than exact rating values.

### 📊Dataset

- MovieLens 1M & 100K datasets

- Files used:

    - movies.dat
    
    - users.dat
    
    - ratings.dat
    
    - u1.base (training set)
    
    - u1.test (test set)
 
- Each user is represented as a vector where:

    - Rows → Users
    
    - Columns → Movies
    
    - Values → Binary ratings
 
### 🧠 Model Architecture

  - Model type: Restricted Boltzmann Machine (RBM)

  - Visible units (nv): Number of movies

  - Hidden units (nh): 100

  - Batch size: 100

  - Training method: Contrastive Divergence (CD-10)

### ⚙️ Training Process

  - The model is trained for 10 epochs

  - Missing ratings are ignored during loss computation

  - Loss is calculated using mean absolute error on known ratings only

Progress is displayed after each epoch with the current training loss.

### 🧪 Testing

After training, the model is evaluated on a separate test set to measure how well it predicts unseen user preferences.
