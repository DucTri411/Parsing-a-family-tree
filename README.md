Trước khi chạy, cài pip install kanren

Trường hợp gặp lỗi khi chạy: làm các bước sau
  1. Truy cập "C:\Users\Dell\AppData\Local\Programs\Python\Python313\Lib\site-packages\unification\core.py", đổi from collections import Iterator --> from **collections.abc** import Iterator
  2. Truy cập "C:\Users\Dell\AppData\Local\Programs\Python\Python313\Lib\site-packages\kanren\util.py", đổi tương tự core.py
  3. Cài thêm pip install --upgrade kanren unification multipledispatch toolz để chuyển đổi import sang collections.abc
