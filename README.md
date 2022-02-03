# assignment2-kumbhum
Assignment 2
# Sreeja Kumbhum
#### Golkonda

The Golconda region was renowned for its diamonds,qutb shahi tombs,Lumbni park, NTR Gardens are the other visiting places around. Golkonda famous for its **biryanI**, Biryani is a mixed rice dish originating among **Pakistanis and other Muslims of the Indian subcontinent**. It is made by adding rice and spices to meat, eggs, spices etc. **Biryani** is one of **the most popular dishes** in South Asia.
***
#### Different varities of biryani
1. Hyderabadi biryani.
    1. The Pakki Hyderabadi Biryani involves cooking of basmatic rice and meat separately.
    2. kachi Hyderabadi Biryani is made from the raw marinated meat (chicken or lamb) placed between the layers of basmati rice infused with saffron, onions and dried fruits, both are slow-cooked in a dough-sealed earthen pot over charcoal fire, which results in rich, aromatic and punchy biryani.
2. Lucknowi Biryani. 
3. Calcutta Biryani.
4. Thalassery Biryani. 
5. Bombay Biryani. 
6. Sindhi Biryani. 
7. Tehari Biryani.
Best place for hyderabadi biryani is Bawarchi its in RTC X road, it is situated half an hour drive away from shamshabad airport which is known as Rajiv Gandhi international airport.
The cheapest and fastest way to get from Airport to RTC X Roads is to drive by car or motor vehicle. 

[About me](ABOUTME.md)
***
### List of Sports/Activities
The below list shows sports/Actitvites along with its location and price.
| Sport/Activity | Location| price |
| --- | --- | --- |
| Yoga | park | $20 |
| Badminton | Court | $25 |
| Painting | Hall | $15 |
| Cricket | stadium | $40 |

***
### Pithy quotes 
>“You must be the change you wish to see in the world.” — -*Gandhi*. 

>“All our dreams can come true, if we have the courage to pursue them” – *Walt Disney*.
***
### code fencing
> In mathematics and computer programming, exponentiating by squaring is a general method for fast computation of large positive integer powers of a number, or more generally of an element of a semigroup, like a polynomial or a square matrix. Some variants are commonly referred to as square-and-multiply algorithms or binary exponentiation. These can be of quite general use, for example in modular arithmetic or powering of matrices. For semigroups for which additive notation is commonly used, like elliptic curves used in cryptography, this method is also referred to as double-and-add.<https://en.wikipedia.org/wiki/Exponentiation_by_squaring>
```
long long binpow(long long a, long long b) {
    if (b == 0)
        return 1;
    long long res = binpow(a, b / 2);
    if (b % 2)
        return res * res * a;
    else
        return res * res;
}
```
<https://cp-algorithms.com/algebra/binary-exp.html>
