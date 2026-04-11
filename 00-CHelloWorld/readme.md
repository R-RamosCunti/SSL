El compilador seleccionado
clang

version del compilador

rociocunti@Mac 00-CHelloWorld % clang --version
Apple clang version 21.0.0 (clang-2100.0.123.102)
Target: arm64-apple-darwin25.3.0
Thread model: posix
InstalledDir: /Library/Developer/CommandLineTools/usr/bin
rociocunti@Mac 00-CHelloWorld % 

version de c que el compilador compila

rociocunti@Mac ~ % cd /Applications/virtual-box/utn\ local/ssl/tps-ssl/00-CHelloWorld          
rociocunti@Mac 00-CHelloWorld % gcc -std=c23 -Wall -Wextra -Werror -pedantic hello.c -o hello     
rociocunti@Mac 00-CHelloWorld % ./hello                                                           
Hello, World!
rociocunti@Mac 00-CHelloWorld % 


