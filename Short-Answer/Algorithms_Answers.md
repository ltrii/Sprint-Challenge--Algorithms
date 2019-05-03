Add your answers to the Algorithms exercises here.

E1 -->

    a) a === 0 (constant)
       while 0 < n ^ 3
    So when N is == 2 it will run twice, n == 3 will run 3 times and so forth...

        O(n)

    b)
        if n == 5 (for example) run each go around for index i until i == n ) [if n is 5 i will be 5 upon completion] Ends look when N iterations have completed.

        for index j in range i + 1 to n go around adding 1 to j. [if n is 5 j will be 5 upon completion]

        for index k in range j + 1 to n go around adding 1 to k. [if n is 5 k will be 5 upon completion]

        for index l in range k + 1 to 10 + k go around adding one to l and sum.

        [if n is 5 l will run 15 times (for each parent range)]


    c)O(n)


E2 -->

    Binary search. Find the middle (maybe len(list)/2)[The length of the list of stories divided by two] and drop an egg.

    If the egg breaks: go lower and try again.
    If not: go higher and try to break it.

    Repeat until you find the floor with the least egg breakage

    O(logn)

