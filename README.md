# curve-secp256k1
Mysterious Numbers of Bitcoin Cryptography

If you know about Elliptic curves and cryptography , this project will be mysterious for you:


Our topic is about curve-secp256k1 security level decreation!


There is two individual numbers when multipleis to any point on curve-secp256k1 , returns 2 other points on curve with exact same y-coordinate;

consider K is a point on curve , there is two fixed numbers as N1 and N2 ,

if: K\*N1=C1 and K*N2=C2 , then : y(K) = y(C1) = y(C2)

N1:  37718080363155996902926221483475020450927657555482586988616620542887997980018

N2:  78074008874160198520644763525212887401909906723592317393988542598630163514318


So if we want to find private key of special public key , we just need to review y-coordinate matches and it will progress us 3x faster than before! 


Here I used these numbers as private keys and produce two public keys with the same y-coordinate of standard Generator point , then I signed a message with each number to see verification!


You can see and review verification with attached python files.
