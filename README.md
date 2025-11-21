playlist = [
    ("Taylor Swift", "The Fate of Ophelia", 4.2),
    ("Taylor Swift", "Opalite", 3.9),
    ("HUNTR/X & EJAE & AUDREY NUNA & REI AMI", "Golden", 3.5),
    ("RAYE", "Where Is My Husband!", 3.7),
    ("Olivia Dean", "Man I Need", 3.3),
    ("Olivia Dean", "So Easy (To Fall In Love)", 3.4),
    ("Dave & Tems", "Raindance", 4.0),
    ("HUNTR/X & EJAE & AUDREY NUNA & REI AMI", "How It's Done", 3.6),
    ("ROSÉ & Bruno Mars", "APT.", 3.2),
    ("Lady Gaga & Bruno Mars", "Die With a Smile", 3.8),
    ("Lola Young", "Messy", 3.5),
    ("Benson Boone", "Beautiful Things", 3.7),
    ("Sabrina Carpenter", "Espresso", 3.3),
    ("Kendrick Lamar & SZA", "Luther", 4.1),
    ("Alex Warren", "Ordinary", 3.2),
    ("HAVEN.", "I Run", 3.6),
    ("4 Non Blondes", "What’s Up?", 4.5),
    ("FloyyMenor & Cris MJ", "Gata Only", 3.4),
    ("ZXKAI & slxughter", "NO BATIDÃO (Slowed)", 3.7),
    ("CKay feat. Mavo", "BODY (danz)", 3.8)
]
# ("Lady Gaga", "The Dead Dance", 3.9),
print(f"Původní délka: {len(playlist)}")

playlist.append(("Lady Gaga", "The Dead Dance", 3.9))
print(f"Po přidání: {len(playlist)}")

playlist.pop(0)
print(f"Po odstranění první písničky: {len(playlist)}")

print(f"Finální délka playlistu: {len(playlist)}")
print(playlist)
