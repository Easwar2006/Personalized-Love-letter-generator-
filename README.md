# Personalized-Love-letter-generator
def generate_informal_love_letter(your_name, her_name, special_memory, admired_quality, unique_trait, promise):
    letter = f"""
    Hey {her_name}!

    I just wanted to take a moment to tell you how awesome you are. Seriously, from the first time we met, I knew you were something special. I can’t help but smile when I think about {special_memory}. Those moments are the best!

    You have this amazing ability to {admired_quality}, and it just blows my mind. You make everything better, and I’m so grateful to have you in my life. 

    I love the way you {unique_trait}. It’s those little things that make you, well, you! You light up my world, and I feel super lucky to be your [boyfriend/partner].

    I just want you to know that {promise}. You deserve all the happiness, and I want to be right there with you, making memories and having fun.

    Thanks for being you and for letting me be a part of your life. I can’t wait for all the adventures we’re going to have together!

    Sending you all my love and a big virtual hug!  
    {your_name}
    """
    return letter

# Input details
your_name = input("Enter your name: ")
her_name = input("Enter her name: ")
special_memory = input("Enter a special memory you share: ")
admired_quality = input("Enter a quality you admire about her: ")
unique_trait = input("Enter something unique about her: ")
promise = input("Enter a promise you want to make to her: ")

# Generate and print the love letter
love_letter = generate_informal_love_letter(your_name, her_name, special_memory, admired_quality, unique_trait, promise)
print("\nYour Personalized Love Letter:\n")
print(love_letter)
