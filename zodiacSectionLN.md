## Submission requirements
Test and run your program before submission.
Create zodiacSectionLN.md containing:
Problem requirements
Your source code
Screenshot of the output
Update your README.md with links to the activity files.
Commit and push your work to GitHub.
Submit both:
Live code link
Git repository link



##Source code
by = int(input("Enter your birth year:"))
z = by - 1900
if by < 1900:
    print("Invalid Year, it should not be earlier than 1900")
elif z % 12 == 0:
    print("Your Chinese Zodiac Sign is: Rat (鼠 / Shǔ)")
elif z % 12 == 1:
    print("Your Chinese Zodiac Sign is: Ox (牛 / Niú)")
elif z % 12 == 2:
    print("Your Chinese Zodiac Sign is: Tiger (虎 / Hǔ)")
elif z % 12 == 3:
    print("Your Chinese Zodiac Sign is: Rabbit (兔 / Tù)")
elif z % 12 == 4:
    print("Your Chinese Zodiac Sign is: Dragon (龙 / Lóng)")
elif z % 12 == 5:
    print("Your Chinese Zodiac Sign is: Snake (蛇 / Shé)")
elif z % 12 == 6:
    print("Your Chinese Zodiac Sign is: Horse (马 / Mǎ)")
elif z % 12 == 7:
    print("Your Chinese Zodiac Sign is: Goat (羊 / Yáng)")
elif z % 12 == 8:
    print("Your Chinese Zodiac Sign is: Monkey (猴 / Hóu)")
elif z % 12 == 9:
    print("Your Chinese Zodiac Sign is: Rooster (鸡 / Jī)")
elif z % 12 == 10:
    print("Your Chinese Zodiac Sign is: Dog (狗 / Gǒu)")
else:
    print("Your Chinese Zodiac Sign is: Pig (猪 / Zhū) ")
## Screenshots of the output



