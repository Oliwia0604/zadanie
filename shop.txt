print("Lista zakupów")

shopping_list = {
    'piekarnia': ['Chleb', 'Pączek', 'Bułki'],
    'warzywniak': ['Marchew', 'Seler', 'Rukola']
}

quantity = 0

for key, value in shopping_list.items():
    print(f'Idę do {key.title()}, kupuję tu następujące rzeczy: {value}')
    quantity += len(value)

 print(f'W sumie kupuję {quantity} produktów.')
exersice = "zadanie 2"
print(exersice)

#liczby 0-100 , podzielne przez 5 

for value in range (0, 100):
  if value % 5 == 0 and value >= 1:
   print(value)
   print(value**3)



def shopping(items):
    shopping_cart = "Koszyk zawiera: "
    for item in items:
        shopping_cart += item + '\n'
    return shopping_cart

basket = shopping(shopping_items)
print(basket)