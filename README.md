# Reinforcement Learning with Black Jack

<br>

Introduction to Reinforcement Learning - **Monte-Carlo algorithm** - with Black Jack.

The project is a cool demonstration of an AI learning to play Black Jack by itself: learning from thousands of games through rewards & losses.

<br>



## Results

<br>

The script learns an Optimal Value Function, which gives us the expected reward over time:

<br>

![Optimal Value Function Heatmap](https://github.com/paulcourty/BlackJackRL/blob/main/Optimal%20Value%20Function%203D%20Heatmap.png)

<br>



## How to run

<br>

You can run the `BlackJackRL.ipynb` Notebook either **locally on your Laptop** or **online on Google Collaboratory**.

<br>

Online on **Google Collab** (_recommended_):

- Go to [https://colab.research.google.com/](https://colab.research.google.com/)
- Click on import from GitHub
- Type in the URL of this repository [https://github.com/paulcourty/BlackJackRL](https://github.com/paulcourty/BlackJackRL)
- Open `BlackJackRL.ipynb`

<br>

Locally on **Laptop**:

Clone this repository (`git` or manually downloading the folder), open a terminal, navigate to the cloned repository, and install the necessary Python dependencies:

For **Unix/macOS**:

```sh
python3 -m venv .env_BlackJackRL
source .env_BlackJackRL/bin/activate
pip install -r requirements.txt
```

For **Windows**:

```sh
py -m venv .env_BlackJackRL
call .env_BlackJackRL/Scripts/activate
pip install -r requirements.txt
```

<br>

Then, open the Jupyter environment:

```sh
jupyter lab
```

<br>

When the Jupyter web interface opens, navigate to `BlackJackRL.ipynb` to open & run the Notebook !