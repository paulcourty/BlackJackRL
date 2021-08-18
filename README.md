<h1>Black Jack Reinforcement Learning</h1>

<br/>

Introduction to Reinforcement Learning (Monte-Carlo algorithm) with Black Jack.

The project is a cool demonstration of an AI learning to play Black Jack by itself: learning from thousands of games through rewards & losses.

<br/>

You can run the `BlackJackRL.ipynb` Notebook by simply cloning this repository (`git` or manually downloading the folder). Then, go into a terminal, navigate to the cloned repository, and install the necessary Python dependencies:

For **Unix/macOS**:

```sh
python3 -m venv .env_BlackJackRL
source .env_BlackJackRL/bin/activate
pip install -r requirements.txt
```

For **Windows**:

```sh
py -m venv .env_BlackJackRL
cd .env_BlackJackRL\Scripts
activate
pip install -r requirements.txt
```

Then, open the Jupyter environment:

```sh
jupyter lab
```

And in the web interface that just opened, navigate to `BlackJackRL.ipynb` to open & run the Notebook !

<br/>

The script learns an Optimal Value Function, which tells us the expected rewards over time considering the dealer's hand and yours:

![Optimal Value Function Heatmap](https://github.com/paulcourty/BlackJackRL/blob/main/Optimal%20Value%20Function%203D%20Heatmap.png)