# Starter Flask App - Choose Your Own Adventure

This repo is a starter flask app for teaching purposes.

This particular variant was made to demonstrate how to use flask to build a [Choose Your Own Adventure](https://en.wikipedia.org/wiki/Choose_Your_Own_Adventure) game.

For a more basic introduction, see [Starter Flask App](https://github.com/x/starter-flask-app).

## How to Clone This Repo

1. If you haven't already, [set up git](https://docs.github.com/en/get-started/getting-started-with-git/set-up-git).
2. Click the green "Code" button in the top right corner of this page.
3. Copy the URL in the dropdown.
4. Open your terminal and navigate to the directory where you want to clone this repo.
5. Run the following command:
   ```bash
   git clone <URL>
   ```
   ![](images_for_readme/image-0.png)


## How to Run the Flask App Locally

1. If you don't already, install python and pip. If you're not sure if you have python installed, try running it locally in your command line with `python --version`.
   ![](images_for_readme/image-1.png)

2. Navigate to the directory where you cloned this repo.
3. Run the following command to install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the following command to start the flask app defined in the `app.py` file:
   ```bash
   flask run
   ```
   ![](images_for_readme/image-2.png)

5. Open your browser and navigate to [http://127.0.0.1:5000](http://127.0.0.1:5000) to see the app running locally.
   ![](images_for_readme/image-3.png)


## Assignment

- Write your own text adventure. Build each chapter as a route in the flask app.
- Include at lease one win condition.
- Include at least one failure condition.
- Include at least one loop.

### Bonus

Add an item, such as a key, that is required to be found and carried to a particular room to unlock the ending.

Some things you might investigate:
- Flask's `g` special object
- Query parameters
- Sessions

Think about the pros and cons to the different approaches.
