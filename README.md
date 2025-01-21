# Flappy Bird AI

A Python-based implementation of the classic Flappy Bird game with an AI agent trained using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm. This project leverages `pygame` for game rendering and `neat-python` for neural network evolution.

---

## Features

- **Classic Flappy Bird Gameplay**: Recreates the experience of the original Flappy Bird.
- **AI Integration**: Uses the NEAT algorithm to evolve neural networks capable of playing the game autonomously.
- **Data Visualization**: Includes visualization tools to track fitness progression and neural network structures.
- **Customizability**: Configurable NEAT settings to tune AI behavior and evolution.

---

## Project Structure

- **`flappy_bird.py`**: Main script to run the game and train the AI.
- **`visualize.py`**: Functions to visualize NEAT statistics and neural network structures.
- **`requirements.txt`**: Dependencies required for the project.
- **`config-feedforward.txt`**: Configuration file for NEAT algorithm parameters.
- **`replit.txt`**: Configuration file for running the project on Replit.
- **`gitpod.yml`**: Configuration file for running the project on Gitpod.
- **`best.pickle`**: Serialized file to store the best-performing genome.

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the game:
   ```bash
   python flappy_bird.py
   ```

---

## How It Works

1. **Game Mechanics**:
   - The game is built using `pygame` and follows the mechanics of the original Flappy Bird game.
   - Players (or AI agents) must navigate through pipes without collision.

2. **AI Training**:
   - The NEAT algorithm evolves neural networks to control the bird.
   - Fitness is calculated based on the distance traveled and pipes passed.

3. **Visualization**:
   - Use `visualize.py` to plot fitness trends and view neural network structures during or after training.

---

## Configuration

### NEAT Parameters
- Modify parameters in `config-feedforward.txt` to adjust the behavior of the NEAT algorithm, including:
  - Population size
  - Activation functions
  - Connection weights

### Replit/Gitpod
- Pre-configured files (`replit.txt` and `gitpod.yml`) allow you to run the project in cloud-based environments seamlessly.

---

## Dependencies

The project requires the following Python libraries:

- `numpy`
- `pygame`
- `neat-python`
- `graphviz`
- `matplotlib`

Install them using:
```bash
pip install -r requirements.txt
```

---

## Usage

### Training the AI
Run the `flappy_bird.py` script to train the AI:
```bash
python flappy_bird.py
```

The training process will display progress and fitness statistics in the terminal.

### Visualizing Results
Use the `visualize.py` module to generate visualizations:
```python
import visualize
# Example: visualize.plot_stats(statistics)
```

---

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. See `LICENSE` for more details.

---

## Acknowledgments

- **Tech With Tim**: Original inspiration for the Flappy Bird AI implementation.
- **NEAT-Python**: Library for neuroevolution algorithms.

---
