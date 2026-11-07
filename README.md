# Yongxin-High-School-2026-Sports-Meet
永新中学2026秋季校运会记
import string
import time
text = 'Hello World'
temp = ''
for ch in text:
    for i in string.printable:
        if i == ch or ch =='':
           time.sleep(0.02)
           print(temp+i)
           temp +=ch
           break
        else:
            time.sleep(0.02)
            print(temp+i)
