# URL-Python
Code 
import pyshorteners

# Create an instance of the pyshorteners.Shortener class
s = pyshorteners.Shortener()

# Get the original URL from the user
url = input("Enter the URL to shorten: ")

# Shorten the URL using the TinyURL provider
shortened_url = s.tinyurl.short(url)

# Print the shortened URL
print("Shortened URL:", shortened_url)
