# hello-world
Hausaufgabe über Weihnachten (Ü DH)
Programmieren ist teilweise ein bisschen überfordernd für mich.

text1 = input(“Welches Projekt möchtest du umbenennen?“)
text2 = "– Online"
print(text1+text2)

text1 = input("Welches Projekt möchtest du umbenennen?")
text2 = " - Online"
print(text1+text2)

--

k = 2

if k > 4:
    print(f"ich hatte {k} Kaffee. Man kann mit mir sprechen")

if k < 3:
    print(f"ich hatte noch nicht genug Kaffee. Komm später wieder")

--

k = 3

if k >= 4:
    print(f"ich hatte {k} Kaffee. Man kann mit mir sprechen")

if k <= 3:
    print(f"ich hatte noch nicht genug Kaffee. Komm später wieder")

--

k = int(input("Wie viele Tassen Kaffe hattest du heute?"))

if k >= 4:
    print(f"ich hatte {k} Kaffee. Man kann mit mir sprechen")

if k <= 3:
    print(f"ich hatte noch nicht genug Kaffee. Komm später wieder")

--

k = int(input("Wie viele Tassen Kaffe hattest du heute?"))

if k <= 4 k <= 8:
    print(f"ich hatte {k} Kaffee. Man kann mit mir sprechen")

if k <= 3:
    print(f"ich hatte noch nicht genug Kaffee. Komm später wieder")

--

k = int(input("Wie viele Tassen Kaffe hattest du heute?"))

if 4 <= k <=8:
    print(f"ich hatte {k} Kaffee. Man kann mit mir sprechen")

elif k <= 3:
    print(f"ich hatte noch nicht genug Kaffee. Komm später wieder")

else:
    print("das war zu viel")

--

n = 0

while n < 8:
    print(f"Die Kaffeemenge {n} ist noch vertretbar")
    n = n+1
