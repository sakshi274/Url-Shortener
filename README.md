# URL Shortener

This is a simple URL shortener implemented in Python. It allows you to generate short URLs for long web addresses, making them easier to share and remember.

## Features

- Generates short URLs for long web addresses.
- Retrieves the original URL for a given short URL.

## Getting Started

To get started with the URL shortener, follow these steps:

1. Clone the repository:

# Url-Shortener

2. Navigate to the project directory:


3. Install the required dependencies. (No external dependencies are needed for this code.)

4. Run the `main.py` script:


5. Follow the instructions in the console to shorten and retrieve URLs.

## Usage

To shorten a URL, create an instance of the `URLShortener` class and call the `shorten_url()` method, passing the original URL as an argument. It will return a shortened URL.

```python
shortener = URLShortener()

original_url = "https://www.example.com/very/long/url"
short_url = shortener.shorten_url(original_url)
print("Shortened URL:", short_url)
retrieved_url = shortener.get_original_url(short_url)
print("Retrieved URL:", retrieved_url)
