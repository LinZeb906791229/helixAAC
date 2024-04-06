Import('RTT_ROOT')
Import('rtconfig')
from building import *

src = Glob('*.c') + Glob('./real/*.c')

cwd = GetCurrentDir()

CPPPATH = [cwd + '/pub', cwd + '/real']

group = DefineGroup('helixAAC', src, depend = ['PKG_USING_HELIX_AAC'], CPPPATH = path)

Return('group')