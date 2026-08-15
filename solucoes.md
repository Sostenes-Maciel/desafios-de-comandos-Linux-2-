## Problema p1-b
`tar -xzf challenges.tar.gz`

## Problema p2-b
`cd challenges`

## Problema p3-b
`ls`

## Problema p4-b
`mkdir foo`

## Problema p5-i
`mkdir -p foo/bar/1/2/3`

## Problema p6-b
`rm -rf foo`

## Problema p7-b
`./hello_executable`

## Problema p8-b
`echo "OlÁ Mundo" > hello.txt`

## Problema p9-b
`touch empty.txt`

## Problema p10-b
`rm empty.txt`

## Problema p11-i
`> empty.txt`

## Problema p12-i
`echo -n > empty.txt`

## Problema p13-b
`cp hello.txt goodbye.txt`

## Problema p14-b
`mv goodbye.txt hello_copy.txt`

## Problema p15-i
`diff hello.txt hello_copy.txt`

## Problema p16-b
`cat hello.txt hello_copy.txt > 2_hellos.txt`

## Problema p17-b
`pwd`

## Problema p18-b
`ls -l`

## Problema p19-b
`chmod +w restricted.txt`

`nano restricted.txt`

## Problema p20-b
`./hello_executable`

## Problema p21-b
`chmod +x challenge_20`

`./challenge_20`

## Problema p22-b
`gcc compile_me.c`

`./a.out`

## Problem p23-a
`./redirect &> output.txt`

## Problema p24-b
`date`

## Problema p25-b
`ps aux`

## Problema p26-b
`nproc`

## Problema p27-b
`uname -r`

## Problema p28-b
`grep -r "You found the needle in the haystack!" bunch_of_files/`

## Problema p29-b
`head -n 25 people.csv`

## problema p30-b
`tail -n 25 people.csv`

## Problema p31-i
`diff greeting1.txt greeting2.txt`

## Problema p32-i
`echo "Olá"; sleep 5; echo "mundo!"`

## Problema p33-i
`dd if=/dev/zero of=arquivo_zeros.txt bs=1M count=1`

## Problema p34-i
`dd if=/dev/urandom of=arquivo_aleatorio.txt bs=1M count=2`

## Problema p35-i
`wc -l README.txt`

## Problema p36-b
`tac README.txt`

## problema p37-i
`cut -d ',' -f 2 people.csv`

## Problema p38-a
`cut -d ',' -f 2 people.csv | sort | uniq | wc -l`

## Problema p39-a
`tail -n +2 people.csv | cut -d ',' -f 2 | sort | uniq | wc -l`

## Problema p40-a
`sed '1d' people.csv | cut -d ',' -f 2 | sort | uniq | wc -l`

## Problema p41-a
`time tail -n +2 people.csv | cut -d ',' -f 2 | sort | uniq | wc -l`

`time sed '1d' people.csv | cut -d ',' -f 2 | sort | uniq | wc -l`

## Problema p42-a
`cut -d ',' -f 4 people.csv | grep "^Josiah$" | wc -l`

## problema p43-i
`find . -maxdepth 1 -type f | wc -l`

## Problema p44-i
`find . -mindepth 1 -maxdepth 1 -type d | wc -l`

