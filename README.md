# How-to-check-the-direct-of-modules
モジュールの保存場所確認方法
ref: Life with Python -Python Tips：ライブラリ・モジュールの場所を調べたい-
http://www.lifewithpython.com/2014/07/python-get-location-of-libraries-modules-packages.htmlimport datetime


print datetime.__file__
# => datetimeモジュールの場所

import json
print json.__path__
# => jsonパッケージの場所
