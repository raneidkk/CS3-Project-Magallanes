##Requirements

Create a zodiacSectionLN.py file. This file will contain your solutions to the requirements below: a. Ask the user to enter a year of birth. The baseline year 1900. b. Validate user input that it should not be earlier than 1900. c. If the user enters an invalid year then display an appropriate message then stop or abort the program. Example: Enter your birth year: 1800 Invalid Year, it should not be earlier than 1900 d. Otherwise determine the chinese zodiac sign based on the following starting from 1900. Note: A zodiac sign will recur after each 12 years. i. Rat (凤/Shū) ii. Ox (牛/Niu) IIL Tiger (虎/Hū) IV. Rabbit (兔/Tù) V. Dragon (龙 /Lóng) We. Snake (蛇/Shé) vii. Horse (马/Mã) viii. Goat (羊/ Yáng) IX. Monkey (猴/Hóu) X Rooster (鸡/ Jī) xi. Dog (狗/Gõu) xii. Pig (猪/Zhū) e. CONSIDER only the year of birth. Example input and output: Enter your birth year: 2000 Your Chinese Zodiac Sign is: Dragon (龙/ Lóng)
Test and Run your code before submitting.
Document this graded exercise in your Github portfolio and save it in zodiac SectionLN.md. This .md will include the requirements for this coding exercise, your actual code and a screenshot of your output. Update also your README.md file to have the link to your files.
Commit your changes in your github account and submit the live code link to your teacher and also your .git repository link.
Refer to Annex D for Code Exercise Rubrics for Grading.

##Actual code

birth_year = int(input("Enter your birth year: "))

if birth_year < 1900:
    print("Invalid Year, it should not be earlier than 1900")
else:
    zodiac = (birth_year - 1900) % 12

    if zodiac == 0:
        print("Your Chinese Zodiac Sign is : Rat (鼠 / Shǔ)")
    elif zodiac == 1:
        print("Your Chinese Zodiac Sign is : Ox (牛 / Niú)")
    elif zodiac == 2:
        print("Your Chinese Zodiac Sign is : Tiger (虎 / Hǔ)")
    elif zodiac == 3:
        print("Your Chinese Zodiac Sign is : Rabbit (兔 / Tù)")
    elif zodiac == 4:
        print("Your Chinese Zodiac Sign is : Dragon (龍 / Lóng)")
    elif zodiac == 5:
        print("Your Chinese Zodiac Sign is : Snake (蛇 / Shé)")
    elif zodiac == 6:
        print("Your Chinese Zodiac Sign is : Horse (馬 / Mǎ)")
    elif zodiac == 7:
        print("Your Chinese Zodiac Sign is : Goat (羊 / Yáng)")
    elif zodiac == 8:
        print("Your Chinese Zodiac Sign is : Monkey (猴 / Hóu)")
    elif zodiac == 9:
        print("Your Chinese Zodiac Sign is : Rooster (雞 / Jī)")
    elif zodiac == 10:
        print("Your Chinese Zodiac Sign is : Dog (狗 / Gǒu)")
    else:
        print("Your Chinese Zodiac Sign is : Pig (豬 / Zhū)")

        ##Output
        <img width="439" height="529" alt="Screenshot 2026-08-18 151712" src="https://github.com/user-attachments/assets/06e2b0cf-ee40-4d4f-99a4-e227fe1f3d76" />

