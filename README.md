# A simple script to greet the user and display the current time.
import datetime

def welcome_message(name):
    """
    This function generates a personalized welcome message.
    """
    print(f"Hello, {name}! Welcome to the GitHub repository.")

def display_current_time():
    """
    This function prints the current date and time.
    """
    now = datetime.datetime.now()
    print(f"The current date and time is: {now.strftime('%Y-%m-%d %H:%M:%S')}")

if __name__ == "__main__":
    welcome_message("user")
    display_current_time()
