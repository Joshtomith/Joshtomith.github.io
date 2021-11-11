1.) LOOKUP TIME Splay Advantage: AVL is typically faster in regards of real time lookups(O(log n)). However, Splay always guarentees a generally fast response(O(n log n) at worst) 
so in general Splay can be considered more reliable. Meaning if you were going to minimize realtime lookups Splay tree is the best way to go. The graphs were even for the most part but this is reflected in larger sample sizes(Splay dropped off in efficeny with larger sample sizes), 
as the amount of quick lookups were a lot higher leading to a lower performance on larger sample sizes. 
Also more hevaily utilized results are shifted to the top for easier use and speed in Splay in some implementations. I like to think of it as a search engine with having more frequented results appear at the top of the searches. 
Overall a good choice in all scenarios, but especially suited for quick small lookeups.

2.) SHAPE AND Multi-Threading: AVL's method of storing data is very unique and can be useful in a lot of scenarios requiring quick responses. As mentioned before in general 
most operation are O(log n), this is largely due to the tree always being in order regardless of lookups. So if you needed a data structure to manage large sizes, with constant rebalancing its always typically quick to pull data up. The benefit of having a very small height to the tree because of constant rebalancing can be very useful, 
because if you needed to ascess and element at the bottom it would be almost just as quick as options close to the top. 
These is especially useful if you consider how many computers can utilize multithreading,meaning that multiple AVL trees could be searched way quicker then Splay tree. This is pertinant to things like video games that require snappy 
calculations to maintain an experience. 
