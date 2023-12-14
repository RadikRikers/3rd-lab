usage:

`encrypt.py -i INPUTFILE -o OUTPUTFILE -k KEYFILE (optional: -w BLOCKSIZE -r ROUNDSIZE)`
<br>
`decrypt.py -i INPUTFILE -o OUTPUTFILE -k KEYFILE (optional: -w BLOCKSIZE -r ROUNDSIZE)`


При малом количестве раундов и коротком ключе, алгоритм взламывается линейным криптоанализом;
При использовании до 20 раундов, взламывается дифференциальным криптоанализом;
При кол-ве раундов >20 и сложном ключе, взломать практически невозможно.
