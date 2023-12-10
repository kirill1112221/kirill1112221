dict = {
            "КРИНЖ": "Что-то очень странное или стыдное",
            "ЛОЛ": "Что-то очень смешное"
            }
            
word = input("Введите непонятное слово ").upper()
    
    
if word in dict.keys():
  print(dict.get(world))
else:
    print('это го слово еще нет')
