# Telephone Number Validator

# 📝 Description

Telephone Number Validator project for freeCodeCamp <a href="https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/javascript-algorithms-and-data-structures-projects/palindrome-checker)">JavaScript Algorithms and Data Structures</a> certification.

# 🔧 Technologies

- <img align="center" alt="Yann-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg"> (ES6 & RegEx)

# ⭕️ Rules & Tasks

> Return true if the passed string looks like a valid US phone number.

> The user may fill out the form field any way they choose as long as it has the format of a valid US number. The following are examples of valid formats for US numbers (refer to the tests below for other variants):

555-555-5555</br>
(555)555-5555</br>
(555) 555-5555</br>
555 555 5555</br>
5555555555</br>
1 555 555 5555</br>

> For this challenge you will be presented with a string such as 800-692-7753 or 8oo-six427676;laskdjf. Your job is to validate or reject the US phone number based on any combination of the formats provided above. The area code is required. If the country code is provided, you must confirm that the country code is 1. Return true if the string is a valid US phone number; otherwise return false.

# ✅ Tests

telephoneCheck("555-555-5555") should return a boolean.</br>
Waiting:telephoneCheck("1 555-555-5555") should return true.</br>
Waiting:telephoneCheck("1 (555) 555-5555") should return true.</br>
Waiting:telephoneCheck("5555555555") should return true.</br>
Waiting:telephoneCheck("555-555-5555") should return true.</br>
Waiting:telephoneCheck("(555)555-5555") should return true.</br>
Waiting:telephoneCheck("1(555)555-5555") should return true.</br>
Waiting:telephoneCheck("555-5555") should return false.</br>
Waiting:telephoneCheck("5555555") should return false.</br>
Waiting:telephoneCheck("1 555)555-5555") should return false.</br>
Waiting:telephoneCheck("1 555 555 5555") should return true.</br>
Waiting:telephoneCheck("1 456 789 4444") should return true.</br>
Waiting:telephoneCheck("123**&!!asdf#") should return false.</br>
Waiting:telephoneCheck("55555555") should return false.</br>
Waiting:telephoneCheck("(6054756961)") should return false.</br>
Waiting:telephoneCheck("2 (757) 622-7382") should return false.</br>
Waiting:telephoneCheck("0 (757) 622-7382") should return false.</br>
Waiting:telephoneCheck("-1 (757) 622-7382") should return false.</br>
Waiting:telephoneCheck("2 757 622-7382") should return false.</br>
Waiting:telephoneCheck("10 (757) 622-7382") should return false.</br>
Waiting:telephoneCheck("27576227382") should return false.</br>
Waiting:telephoneCheck("(275)76227382") should return false.</br>
Waiting:telephoneCheck("2(757)6227382") should return false.</br>
Waiting:telephoneCheck("2(757)622-7382") should return false.</br>
Waiting:telephoneCheck("555)-555-5555") should return false.</br>
Waiting:telephoneCheck("(555-555-5555") should return false.</br>
Waiting:telephoneCheck("(555)5(55?)-5555") should return false.</br>
Waiting:telephoneCheck("55 55-55-555-5") should return false.</br>
Waiting:telephoneCheck("11 555-555-5555") should return false</br>
