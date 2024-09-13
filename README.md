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


## License

This project is licensed under the MIT License.

## Acknowledgements

- [Stable Baselines3](https://stable-baselines3.readthedocs.io/en/master/)
- [OpenAI Gym](https://www.gymlibrary.ml/)
