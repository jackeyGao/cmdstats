cmdstats
------------

.. role:: bash(code)
   :language: bash


查看你终端命令使用频率列表, 原理是通过宿主目录下的 ``.*history`` 分析后得到历史命令使用频率状态， 并且进行排序输出.

.. image:: https://github.com/jackeyGao/cmdstats/raw/master/screenCapture.jpg


Install
------------

::

    pip install git+https://github.com/jackeyGao/cmdstats.git

Usage
------------

::

    $ cmdstats -l 25
    1   1919  27.01675%  vim
    2   1524  21.45572%  python
    3   797   11.22061%  ls
    4   646   9.09475%   git
    5   356   5.01197%   cd
    6   215   3.02689%   ll
    7   186   2.61861%   pip
    8   82    1.15444%   rm
    9   71    0.99958%   workon
    10  66    0.92918%   mysql
    11  61    0.85879%   clear
    12  59    0.83063%   curl
    13  56    0.7884%    ps
    14  54    0.76024%   cat
    15  43    0.60538%   tail
    16  37    0.52091%   grep
    17  36    0.50683%   echo
    18  36    0.50683%   mv
    19  35    0.49275%   sh
    20  32    0.45051%   mkdir
    21  29    0.40828%   nohup
    22  29    0.40828%   cp
    23  28    0.3942%    pwd
    24  27    0.38012%   su
    25  26    0.36604%   mkvirtualenv




License
------------

The MIT License (MIT)

Copyright (c) 2015 JackeyGao

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

