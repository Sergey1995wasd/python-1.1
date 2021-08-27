# python-1.1
duration = int(input('Число: '))
d = duration // 86400
h = (duration - (d * 86400)) // 3600
m = (duration - (h * 3600)) // 60
s = duration % 60
print(d, 'сутки', h, 'час', m, 'мин', s, 'сек')
