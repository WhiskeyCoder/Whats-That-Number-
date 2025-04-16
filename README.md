# 📞 whats_that_number.py

**Description:**
A hilariously overengineered script written for one very specific (and slightly unhinged) use-case: ordering pizza when you only remember part of the phone number. It brute-forces all possible combinations for the missing digits and checks which numbers are valid using a free API. Will definitely get you flagged by someone, somewhere.

---

## 🔧 Features
- Brute-forces 4-digit combinations to complete a phone number.
- Sends each guess to a phone number verification API.
- Outputs all valid numbers to `valid_phone_numbers.txt`.
- Originally used once to order pizza. Never again.

---

## 📦 Requirements
- `requests`
- A free API key from [apilayer's number verification API](https://apilayer.com/marketplace/number_verification-api)

```bash
pip install requests
```

---

## 💻 Usage
1. Replace `API KEY FOR NUMBER VERIFICATION ITS FREE` with your actual API key.
2. Update the phone format inside `all_combinations_as_strings_with_wild_card`. The example in the script assumes the phone number format is:

```
7175XXXX1924
```
Where `XXXX` are the unknown digits.
3. Run the script:

```bash
python whats_that_number.py
```

4. Valid phone numbers will be saved in `valid_phone_numbers.txt`

---

## ⚠️ Disclaimer
- Use responsibly.
- Don’t be a Tony.
- This was made for entertainment and specific edge-cases, not for serious use or spammy behavior.

---

## 🧠 Idea Origin
> "Bro... I only remember part of the number and the pizza place doesn't pick up their email."

Say less. This script happened.

---

## 📁 Output
- `phone_numbers.txt`: All generated phone numbers.
- `valid_phone_numbers.txt`: The phone numbers that were confirmed valid.

---

## ❤️ Author's Note
If you’re running this at 2AM with a craving for stuffed crust, I respect you. 🍕

