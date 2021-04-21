# Drug Interaction Checker

## User stories

In scope

### Doctor/Pharmacist

- I want to enter a drug name in a field
- I want to enter another drug name in another field
- I want to click on a button to to check if both drugs interact
- I want to see a result with a clear message

Out of scope

### Developer

- I want to call an endpoint with two drug names
- I want to get a response with a clear message indicating whether the drugs interact or not

## User edge cases

### Doctor/Pharmacist

- I should see an error message if any of the drugs doesn't exist on the system
- The message must indicate which one

### Developer

- I must get an error message if a drug doesn't exist on the system
- The message must indicate which drug

Suggested idea (far out of scope)

### Telegram User stories

- I want to enter two drug names ot a telegram bot
- The bot should reply with a clear message if the drugs interact or not

### Telegram User Edge cases

- I should receive a clear message if a drug doesn't exist on the system
- The message must indicate which drug, by name

## System components

### Data Representation

- Represent the drugs with their commercial names and their effective materials inside the database alongside which drugs interacts with which.
- A GUI (Django admin) should show the entered data instances.

### Data Entry

Get the data programatically (preferred) or manually and put them into the system according to the data representation mentioned above.

### Web Interface

Show two simple input fields to enter two drug names and a submit button. A result should be shown on the same page.

### REST Endpoint

An endpoint which can be used by external developers to check if 2 drugs interact. This is to be used for the telegram bot, too.

### Telegram Bot

A simple telegram bot that gets two drug names and show a message if they interact or not.

## Team members

- [Ahmed Shahwan](https://github.com/shahwan42)
- [Mohamed Mostafa](https://github.com/mmostafa74)
- [Mohamed A Sattar](https://github.com/Mohamed-sattar)
- [Mohamed Samy](https://github.com/MuhammadSamy1)
- [Ziad Nabil](https://github.com/ziadnabil)
