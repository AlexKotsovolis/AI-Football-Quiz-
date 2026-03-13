# AI Football Quiz ⚽🤖

A simple Python desktop quiz game that generates **yes/no questions about European football teams using AI**.

The application uses **Tkinter** for the graphical interface and **OpenAI's API** to dynamically generate football-related questions. Players answer using **YES/NO buttons**, and the game tracks their score across a short quiz round.

## Features

* ⚽ AI-generated football questions
* ✅ Simple YES/NO gameplay
* 📊 Score tracking and progress bar
* 🎉 Random positive feedback messages for correct answers
* 🔄 Automatic restart after each 5-question round
* 🖥️ Desktop GUI built with Tkinter and `ttkthemes`

## How It Works

1. The program requests a football-related yes/no question from the OpenAI API.
2. The question is displayed in the GUI.
3. The user answers using the **YES** or **NO** buttons.
4. The program checks the answer and updates the score.
5. After **5 questions**, the game resets and allows the player to restart.

## Technologies Used

* **Python**
* **Tkinter / ttk**
* **ttkthemes**
* **OpenAI API**
* **Random module**

## Requirements

Install the required packages:

```bash
pip install openai ttkthemes
```

## Running the Program

```bash
python main.py
```

Make sure to set your OpenAI API key as an environment variable:

```bash
export OPENAI_API_KEY="your_api_key_here"
```

## Screenshot

<img width="600" height="628" alt="well" src="https://github.com/user-attachments/assets/35332cb6-a9fa-471c-bd7a-6e0223bcf0c1" />


## Future Improvements

* Difficulty levels
* Multiple-choice questions
* Better UI styling
* Question history
* Sound effects

## License

This project is for educational purposes.

