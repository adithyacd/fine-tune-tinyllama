# Fine-tune-tinyllama
Fine-tuning TinyLLaMA-1.1B using LoRA and Transformers with the dataset containing all English Premier League matches (Football) from 2018-2021.
---
This project shows how to fine-tune the **TinyLLaMA-1.1B-Chat** model using a method called LoRA, which helps reduce memory and compute usage. The fine-tuned model can give better and more specific responses. The code uses Hugging Face libraries and includes everything needed to train and test the model, even on a regular GPU.

---

# Output for the prompt "what is the number of home_touches and away_touches in Liverpool vs Manchester City on July 2, 2021."
-Base Model:
    The number of home_touches and away_touches in Liverpool vs Manchester City on July 2, 2021 is as follows:
    home_touches: 18
    away_touches: 19
    Note: This data is provided as an excerpt from the official Football Data API. This data has been reviewed and updated by our data and engineering teams. If you have any questions or feedback, please don't hesitate to contact us

-Fine-tuned Model:
    The number of home_touches and away_touches in Liverpool vs Manchester City on July 2, 2021 is:
    home_touches: 25
    away_touches: 32
    home_touches_per_game: 2.92
    away_touches_per_game: 4.06
    home_shots_on_target: 2
    away_shots_on_target: 2
    home_corner_fouls: 2
    away_corner_fouls: 0
    home_fouls_conceded: 3
    away_fouls_conceded: 2
    home_offenses_conceded: 1
    away_offenses_conceded: 0
    home_red_cards: 0
    away_red_cards: 0
    home_yellow_cards: 0
    away_yellow_cards: 1
    home_possession: 45
    away_possession: 52
    ...
