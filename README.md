# 🎵 RNN Music Generator

## Project Overview

Welcome to the fascinating world of music generation using advanced machine learning techniques! In this project, I've crafted a sophisticated recurrent neural network (RNN) model capable of generating musical notes. Leveraging a rich dataset consisting of enchanting piano MIDI files sourced from the prestigious MAESTRO dataset, this model is trained to predict the subsequent note in a sequence, empowering it to compose beautiful melodies autonomously. Moreover, it can extend its creations by conjuring longer sequences of notes, mesmerizing listeners with its harmonic prowess.
👉 [Check this project on Kaggle](https://www.kaggle.com/code/zulqarnainalipk/rnn-music-generator) 👈
## Setup 🛠️

Prepare your environment with the following dependencies to embark on this musical journey:

```bash
sudo apt install -y fluidsynth

pip install --upgrade pyfluidsynth

pip install pretty_midi
```


## Usage 📝

Unlock the secrets of the dataset with ease:

```python
data_dir = pathlib.Path('data/maestro-v2.0.0')
if not data_dir.exists():
  tf.keras.utils.get_file(
      'maestro-v2.0.0-midi.zip',
      origin='https://storage.googleapis.com/magentadata/datasets/maestro/v2.0.0/maestro-v2.0.0-midi.zip',
      extract=True,
      cache_dir='.', cache_subdir='data',
  )
```

## Exploratory Data Analysis (EDA) 📈

Embark on a voyage of discovery as we unravel the mysteries hidden within the dataset. Explore mortality rates by ethnicity through captivating visualizations such as bar plots and pie charts. Uncover trends over time and delve into the intricate relationships between variables, painting a vivid portrait of insights waiting to be uncovered.

- **Bar Plots for Mortality Rates by Ethnicity**: Visualize the tapestry of mortality rates across diverse ethnicities, revealing patterns that resonate with the rhythms of life.
- **Pie Chart for Ethnicity Distribution**: Dive into the kaleidoscope of ethnic diversity, capturing the essence of multiculturalism in a single glance.
- **Line Plot for Infant Mortality Rate Over Time**: Traverse the epochs of time as you chart the trajectory of infant mortality rates, witnessing the ebb and flow of life's symphony.
- **Bar Plot of Average Yearly Deaths by Ethnicity**: Peer into the annals of history, where each bar tells a story of triumphs and tragedies, echoing through the corridors of time.
- **Bar Plot of Average Yearly Live Births by Ethnicity**: Witness the miracle of life unfold before your eyes, as each bar represents the dawn of a new beginning.
- **Scatter Plot for Infant Mortality Rate vs. Number of Live Births**: Explore the intricate dance between life and death, as data points weave a narrative of hope and resilience.



👉 [Visit my Profile](https://www.kaggle.com/zulqarnainalipk) 👈

[GitHub]( https://github.com/zulqarnainalipk) |
[LinkedIn]( https://www.linkedin.com/in/zulqarnainalipk/)

## Share Your Thoughts! 🙏

Your feedback is invaluable! Your insights and suggestions drive our ongoing improvement. If you have any comments, questions, or ideas to contribute, please feel free to reach out.

📬 Contact me via email: [zulqar445ali@gmail.com](mailto:zulqar445ali@gmail.com)

I extend my sincere gratitude for your time and engagement. Your support inspires me to create even more valuable content.
Happy coding and best of luck in your data science endeavors! 🚀


