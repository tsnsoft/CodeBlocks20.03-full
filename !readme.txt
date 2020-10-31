	Настройки распаковать сюда (вместо talip - имя пользователя): 
C:\Users\talip\AppData\Roaming\CodeBlocks

---

https://sourceforge.net/projects/codeblocks/files/Binaries/Nightlies/2020/
https://sourceforge.net/projects/codeblocks/files/Binaries/Nightlies/Prerequisites/
https://github.com/wxWidgets/wxWidgets/releases/tag/v3.1.4

--- ЭТО ТОЛЬКО ДЛЯ СБОРКИ НОВОЙ ВЕРСИИ WXWIDGETS -- НЕ ДЕЛАТЬ ТЕМ КТО НЕ В ТЕМЕ !!!

Добавляем в переменную окружения Path стрку C:\CODEBLOCKS\MinGW\bin

cd C:\CODEBLOCKS\wxWidgets\build\msw
mingw32-make -f makefile.gcc BUILD=release SHARED=0
mingw32-make -f makefile.gcc BUILD=debug SHARED=0

Удаляем из переменной окружения Path стрку C:\CODEBLOCKS\MinGW\bin

---
