
from building import *

cwd     = GetCurrentDir()
src     = Glob('./src/*.c') + Glob('./src/*.cpp')
CPPPATH = [cwd+'/inc']

group = DefineGroup('coremark', src, depend = [''], CPPPATH = CPPPATH)

Return('group')
