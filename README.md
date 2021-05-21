#generally what programmers dont do is
#int ary[n]; cin>>n;
#this is considered to be a bad practice!!! but why ?
#Because program basiccally has 2 memories => Stack and Heap, as the name suggests , HEAP memory is too big, but stack is limited
What a code starts, it starts with stack memory. If user enters n = 10, it will work;
BUT
#if user enters n = 10000000;
now this much amount of memory isn't available with stack always, and hence code will crash. But if we do like ary[1000000], here code already knows that we need this much amount of memory, so we will start with this much memory in stack.
