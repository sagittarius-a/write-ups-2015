<div><h3>What's the hell?!</h3><p>There are 4 equations systems, which depend on password. Each one of them has 3 equations and depend on 3 variables.</p>
<pre><code>1) p[0] + p[1] = 101
   p[1] + p[2] = 143
   p[0] * p[2] = 5035

2) p[3] + p[5] = 163
   p[3] + p[4] = 226
   p[4] * p[5] = 5814

3) p[7] + p[8] = 205
   p[6] + p[8] = 173
   p[6] * p[7] = 9744

4) p[9] + p[10] * p[11] = 5375
   p[10] + p[9] * p[11] = 4670
   p[9] + p[10] = 205
</code></pre>
<p>They are constructed in such way, that the solution exists. There are several ways to get right sides of equations: 
1. Simply <code>std::cout</code> them
2. Spot that they look like lines, rectangles and cubes of corresponding sizes
3. Use debuggers in runtime
4. Google a lot and find analog literals library with documentation and examples
5. Read and understand the code of library</p></div>
