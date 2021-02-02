# 02022021
sed służy do zamiany wzorca tekstowego występującego w pliku(lub strumienia wejścia) na inny na przykład polecenie
echo 'aaaaaaaaabbbbccc'| sed 's/b/c/'
wypisuje aaaaaaaaacbbbccc
z kolei polecenie
echo 'aaaaaaaaabbbbccc'| sed 's/b/c/g'
wypisuje
aaaaaaaaaccccccc
z kolei jeżeli plik1 to napis aaaaaaaaabbbbccc to wykonanie
sed -i 's/b/c/' plik1 prowadzi do nadpisania pliku1 jako napisu aaaaaaaaacbbbccc
## To jest miejsce na Twoją reklamę
