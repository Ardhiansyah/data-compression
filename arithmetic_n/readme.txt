Command untuk mengcompile file main-c dan main-e:

FILE main-c
gcc -o main-c arith_n.c main-c.c errhand.c bitio.c

FILE main-e
gcc -o main-e arith_n.c main-e.c errhand.c bitio.c

Cara menggunakan .exe file:

KOMPRESI
main-c <nama file yang akan dikompresi> <nama file hasil kompresi>

DEKOMPRESI
main-e <nama file yang akan di dekompresi> <nama file hasil dekompresi>

Contoh : 
main-c original_files/video.mp4 compressed_files/video.mp4.arith_n
main-e compressed_files/berk.raw.arith_n original_files/berk.raw