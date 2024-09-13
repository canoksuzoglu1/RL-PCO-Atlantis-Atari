# RL-PCO-Atlantis-Atari

This project involves training and evaluating a Proximal Policy Optimization (PPO) agent to play the Atari game **Atlantis** using Stable Baselines3. The agent is trained with a Convolutional Neural Network (CNN) policy and evaluated for its performance in the game.

## Project Overview

1. **Library Imports**: Import necessary libraries including Gym and Stable Baselines3.
2. **Environment Setup**: Configure the Atari environment and stack frames.
3. **Model Initialization**: Initialize the PPO model with a CNN policy and configure logging.
4. **Training the Model**: Train the PPO model for 2 million timesteps.
5. **Model Saving and Loading**: Save the trained model and reload it for evaluation.
6. **Evaluation and Rendering**: Evaluate the trained model and render the environment to visualize performance.
7. **Real-Time Interaction**: Use the trained model to interact with the environment in real-time.

## Requirements

- Python 3.7+
- Gym
- Stable Baselines3
- TensorBoard
- Other dependencies can be installed via `requirements.txt`.


## Project Structure

The project directory is organized as follows:

- **`Atlantis RL PCO .ipynb`**: Jupyter notebook containing the main code and experiments.
- **`README.md`**: This file, providing an overview and instructions for the project.
- **`requirements.txt`**: File listing the required Python packages.
- **`Training/`**: Directory containing training logs and saved models.
  - **`Logs/`**: Subdirectory for TensorBoard logs.
  - **`Saved Models/`**: Subdirectory for storing trained models.
    - **`PPO_Atlantis_1MT.zip`**: Trained model saved after 1 million timesteps.
    - **`PPO_Atlantis_2MT.zip`**: Trained model saved after 2 million timesteps.

## Usage

1. **Jupyter Notebook**: Open and run the Jupyter notebook `Atlantis RL PCO .ipynb` to explore and execute the main code and experiments. You can interactively train, evaluate, and visualize the PPO agent's performance within the notebook.

2. **Training the Model**: Inside the Jupyter notebook, you can find cells for training the PPO model. Execute these cells to train the model with the desired configurations. 

3. **Evaluating the Model**: Similarly, use the evaluation cells in the notebook to assess the trained model's performance. You can visualize the results and analyze how well the model performs on the Atari Atlantis game.

4. **Real-Time Playback**: To run the trained model in real-time and see the agent playing the game, you can add code within the notebook to load a saved model and render the gameplay.

5. **Model Files**: After training, the model files will be saved in the `Training/Saved Models/` directory. You can use these files for later evaluation or real-time playback. The available models are:
    - **`PPO_Atlantis_1MT.zip`**: Model trained for 1 million timesteps.
    - **`PPO_Atlantis_2MT.zip`**: Model trained for 2 million timesteps.

6. **Dependencies**: Install the required Python packages using the `requirements.txt` file:
    ```bash
    pip install -r requirements.txt
    ```


## License

This project is licensed under the MIT License.

## Acknowledgements

- [Stable Baselines3](https://stable-baselines3.readthedocs.io/en/master/)
- [OpenAI Gym](https://www.gymlibrary.ml/)
