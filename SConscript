
from building import *

cwd     = GetCurrentDir()
src     = Glob('*.c') + Glob('*.cpp')
CPPPATH = [cwd]

group = DefineGroup('coremark', src, depend = [''], CPPPATH = CPPPATH)

Return('group')
