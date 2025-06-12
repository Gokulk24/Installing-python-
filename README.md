# Installing-python-

# weather_report.py
# This program asks the user for the temperature and prints a weather-based message.

def get_weather_message(temp_f):
    """Returns a message based on temperature in Fahrenheit."""
    if temp_f >= 90:
        return "It's extremely hot outside. Stay hydrated!"
    elif temp_f >= 70:
        return "Nice warm weather. Perfect for a walk!"
    elif temp_f >= 50:
        return "A bit chilly. You might need a sweater."
    elif temp_f >= 32:
        return "Cold weather. Make sure to wear a coat!"
    else:
        return "Freezing! Stay warm and maybe stay indoors."

def main():
    print("=== Weather Reporter ===")
    try:
        temp
