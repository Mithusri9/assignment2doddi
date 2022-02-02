# assignment2doddi
# Mithusri doddi
###### Himachal pradesh

Himachal pradesh is a ***northern Indian state*** in the Himalayas. It is home to scenic ***mountain towns*** and resorts such as ***Dalhousie***. I like this place because it is well-known for trecking, climbing.

------

# Directions for travelling from Maryville to Himachal Pradesh
1. Book a cab from Maryville to Kansas city ariport.
2. finish the checkin process
    1. Finish the security check.
    2. Board your flight.
    3. Wait for the connecting flight.
3. O'Hare International Ariport to Gaggal Airport 
    1. Collect the lagguage from the airport
    2. Take a cab for the MahaRaja Hotel

- LIST OF SOME SPECIFIC FOOD ITEMS:

    - Chicken Bririyani
    - Naan roti
    - Paneer curry
    - Rasagula

 [ABOUT ME](https://github.com/Mithusri9/assignment2doddi/blob/main/AboutMe.md)


----


# Sports Activities

The table recoomends some of the sport activities.

|    **Sport/Activity**  |    **Location**  | **Amount**  |
|      ----              |    -----         |   -----     |
|      Batmenton         |  Indoor stadium  |     100     |
|      Cricket           |    Ground        |     200     |
|      Baseball          |  NWSM Ground     |     500     |
|      Basketball        |  Indoor stadium  |     100     | 


----


# Quotes by Greatest people

>"We are what our thoughts have made us; so take care about what you think. Words are secondary. Thoughts live; they travel far." by ***Swami Vivekananda***

>"A dream is not that which you see while sleeping, it is something that does not let you sleep."
by ***APJ Abdul Kalam***


# Algorithm on String processing

> You may code the following in the programing language of your choice. Sample input and output are in the document attached. 1 String Processing. A string is a sequence of characters of an alphabet, concatenated together. The concept is no different from how you have seen strings in your previous programming courses.

Source link for the definition - <https://www.cs.cmu.edu/~awb/papers/ESCA98_arch/node4.html>

---

long long compute_hash(string const& s) {
    const int p = 31;
    const int m = 1e9 + 9;
    long long hash_value = 0;
    long long p_pow = 1;
    for (char c : s) {
        hash_value = (hash_value + (c - 'a' + 1) * p_pow) % m;
        p_pow = (p_pow * p) % m;
    }
    return hash_value;
}

---

Source link for the code - <https://cp-algorithms.com/string/string-hashing.html>

