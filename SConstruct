"""The SConstruct file"""

import os

from freelan.buildtools import Environment

env = Environment(ENV=os.environ.copy(), ARGUMENTS=ARGUMENTS)

targets = SConscript('SConscript', exports='env')

Default('freelan')
