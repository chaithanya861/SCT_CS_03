# SCT_CS_03
A simple yet effective Python script to evaluate password strength based on key security criteria. Provides real-time feedback and improvement suggestions. Ideal for educational use, beginner projects, or integrating into larger authentication systems.
# Password Strength Checker 

This Python script evaluates the strength of a user-provided password based on five key criteria:
- Minimum length (8+ characters)
- Presence of uppercase letters
- Presence of lowercase letters
- Inclusion of digits
- Use of special characters

It returns a strength rating (`Weak`, `Moderate`, or `Strong`) along with actionable suggestions to improve weak passwords.

---

 Features

-  Real-time password evaluation
-  Clear feedback for missing elements
-  Simple CLI interface
-  Easy to integrate into other projects
-  Educational and beginner-friendly

---

 How It Works

The script uses regular expressions to check for:
- `[A-Z]` → Uppercase letters
- `[a-z]` → Lowercase letters
- `\d` → Digits
- `[!@#$%^&*(),.?":{}|<>]` → Special characters

Each satisfied condition adds to the score. The final score determines the password strength:
- `5` → Strong
- `3–4` → Moderate
- `<3` → Weak

---

 Usage

```bash
python password_checker.py
