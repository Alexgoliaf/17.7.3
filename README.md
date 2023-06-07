money=int(input("введите сумму вклада"))
per_cent={}
per_cent = {'ТКБ': 5.6, 'СКБ': 5.9, 'ВТБ': 4.28, 'СБЕР': 4.0}
deposit=max(per_cent.values())*money/100
print(( deposit),"Макскимальная сумма, которую вы можете заработать")
