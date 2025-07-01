#  Password Strength Evaluation

## Objective

The objective of this task is to understand the characteristics of a strong password, test different passwords using online tool, and learn about password-related attacks and best practices in securing authentication systems.

---

## Password Samples & Evaluation

I created and tested a set of passwords with different complexities. Below is the breakdown:

| Password Sample      | Complexity | Length | Components Used        | Tool Used                        | Strength | Notes                            |
|----------------------|------------|--------|-------------------------|----------------------------------|----------|----------------------------------|
| 123456            | Weak       | 6      |  numbers      | passwordmeter.com                | 4%      | Dictionary word, predictable     |
| KRUPAL2025          | Medium     | 10     | upper,  symbols   | passwordmeter.com                | 53%      | Better, but still guessable      |
| password123       | Medium     | 11     | symbols,  lower   | passwordmeter.com              | 43%  | Contains guessable word          |
| K@!rU9pL#54xYz!      | Strong     | 15     | all character types     | passwordmeter.com   | 100%     | Highly secure                    |
| Il0veC@ffe3!         | Strong     | 12     | passphrase style        | passwordmeter.com                | 85%      | Easy to remember, still strong   |


---

##  Password Strength Screenshots

###  Weak Password Test – `123456`
![Weak Password Screenshot](https://github.com/krupal-3009/password-security-analysis/blob/116c67853f91f6619487467bb08e9694fb4bb85f/weak_passwd.png)

###  Medium Password Test – `KRUPAL2025`
![Medium Password Screenshot](https://github.com/krupal-3009/password-security-analysis/blob/116c67853f91f6619487467bb08e9694fb4bb85f/medium.2_passwd.png)

###  Medium Password Test – `password123`
![](https://github.com/krupal-3009/password-security-analysis/blob/116c67853f91f6619487467bb08e9694fb4bb85f/medium.1_psswd.png)

###  Strong Password Test – `K@!rU9pL#54xYz!`
![Strong Password Screenshot](https://github.com/krupal-3009/password-security-analysis/blob/116c67853f91f6619487467bb08e9694fb4bb85f/strong_passwd.png)

---

##  Key Learnings & Best Practices

###  What Makes a Strong Password?
- At least 12–16 characters long
- Includes **uppercase**, **lowercase**, **numbers**, and **symbols**
- Avoids dictionary words or personal names
- Random and unpredictable or uses passphrases (e.g., `Sun!set#D@nce2024`)

###  Best Practices for Creating Passwords
- Use a **password manager** (e.g., Bitwarden, LastPass)
- Avoid reusing passwords across platforms
- Enable **multi-factor authentication (MFA)** wherever possible
- Prefer **passphrases** over complex but hard-to-remember strings

---

##  Common Password Attacks

| Attack Type         | Description |
|---------------------|-------------|
| Brute Force         | Tries every possible combination of characters until it succeeds |
| Dictionary Attack   | Tries a list of common or leaked passwords from dictionaries |
| Credential Stuffing | Uses previously breached credentials on multiple websites |

---


