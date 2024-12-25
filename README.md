# python-GUI-pwgen-with-clipboard
To prosta aplikacja napisana w Pythonie z graficznym interfejsem użytkownika (GUI) do generowania bezpiecznych haseł. Umożliwia dostosowanie długości hasła oraz zawartości, takiej jak wielkie litery, cyfry i znaki specjalne. Aplikacja pozwala również na łatwe kopiowanie wygenerowanych haseł do schowka.

## Funkcje
- **Dostosowanie długości hasła**: Możesz określić, jak długie ma być hasło.
- **Opcje zawartości hasła**:
  - Włączanie wielkich liter
  - Włączanie cyfr
  - Włączanie symboli
- **Wyświetlanie hasła**: Wygenerowane hasło jest widoczne w polu tylko do odczytu.
- **Kopiowanie do schowka**: Jednym kliknięciem skopiuj hasło do schowka.
- **Prosty interfejs**: Intuicyjny design oparty na `tkinter`.

## Wymagania
- Python 3.x
- Wymagane biblioteki Pythona:
  - `tkinter` ((domyślnie dostępne w Pythonie)dla Arch Linux pakiet musi być zainstalowany przez `sudo pacman -S tk`)
  - `pyperclip` ((instalacja: `pip install pyperclip`)dla Arch linux pakiet musi zostać zainstalowany przez `sudo pacman -S pyperclip-python`)
    Wszystkie biblioteki dostepne są również w AUR.

## Uzytkowanie
`python pwgen.py`
