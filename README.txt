Tic-Tac-Toe RL Agent

Methods

This project features an advanced Reinforcement Learning (RL) agent capable of playing the classic game of Tic-Tac-Toe. The core methodology employed in this agent is Value Iteration, a powerful technique in the realm of reinforcement learning. To address the complexity of Tic-Tac-Toe, we began by considering all possible combinations of 'X', 'O', and empty positions across the 9 cells of the Tic-Tac-Toe board. This comprehensive approach ensured that our agent learned from every conceivable board configuration.

Recognizing the importance of computational efficiency, state pruning was applied to eliminate redundant or unnecessary states from the learning process. This optimization helped streamline the agent's training phase, allowing for more rapid convergence to optimal strategies.

For each valid state, the agent evaluates a list of potential actions, mapping out the decision-making process in the context of the game. The implementation of Value Iteration in this project is unique as it incorporates aspects of the Min-Max algorithm. This combination allows our RL agent to effectively navigate the game's strategic complexities, simulating a thoughtful opponent that adapts its strategy based on the evolving game board.
How to Run the Project

To get started with this Tic-Tac-Toe RL agent, follow these simple steps:

    Install Dependencies:
        Open your terminal.
        Navigate to the project's directory.
        Run the command: pip install -r reqs.txt.
            

    Running the Notebook:
        Open play_against_AI.ipynb using Jupyter Notebook.
        Execute the cells in the notebook to interact with the trained RL agent.

Enjoy testing your Tic-Tac-Toe skills against a sophisticated and strategically trained AI!