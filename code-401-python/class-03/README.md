# Simple guide to Big O Notation
---
## What is Big O

- Big O Notation is a way to measure an algorithm’s efficiency. It measures the time it takes to run your function as the input grows. Or in other words, how well does the function scale. Big O specifically describes the worst-case scenario, and can be used to describe the execution time required or the space used (e.g. in memory or on disk) by an algorithm.




---
### Here are some common orders of growth along with descriptions and examples where possible.
- O(1) : O(1) means that it takes a constant time, like 14 nanoseconds, or three minutes no matter the amount of data in the set.
> Example : 
```
def OddOrEven(n):
    return "Even" if n % 2 else "Odd"\
```
- O(N) : N refers to the size of the input, in your case it's the number of items in your list. O(N) means that your algorithm will take on the order of n operations to insert an item.
> Example  
```
bool ContainsValue(IEnumerable<string> elements, string value)
{
    foreach (var element in elements)
    {
        if (element == value) return true; 
    }     
    return false; 
}
```
- O(N²) : O(n²) means that the calculation runs in quadratic time, which is the squared size of the input data
> Example : 
```
bool ContainsDuplicates(IList<string> elements)
{
    for (var outer = 0; outer < elements.Count; outer++) 
    {
        for (var inner = 0; inner < elements.Count; inner++) 
        { 
            // Don't compare with self 
            if (outer == inner) continue;             
            
            if (elements[outer] == elements[inner]) return true; 
        }
    }    
    return false;
}
```
- O(2^N) : O(2n) denotes an algorithm whose growth doubles with each addition to the input data set. The growth curve of an O(2n) function is exponential - starting off very shallow, then rising meteorically.
> Example : 
```
int Fibonacci(int number)
{
    if (number <= 1) return number;
       
    return Fibonacci(number - 2) + Fibonacci(number - 1); 
}
```

### Logarithms: 

Logarithms or log: A mathematical concept/expression that’s used a lot in Computer Science and it’s the inverse (flip) of exponentials, and they’re used to answer the question: How many times must one “base” number be multiplied by itself to get some other particular number or (what power you have to raise to, to get another number) or we can also define it as The power (or exponent) to which one base number must be raised (multiplied by itself) to produce another number.<br>

---
### Things I want to know more about : 
- How do we know the Big O of huge projects ? 
- Is there a tool that can find the Big O and give you a better solution ? 


---
>### Sources : 
https://towardsdatascience.com/logarithms-exponents-in-complexity-analysis-b8071979e847#:~:text=Logarithms%20or%20log%3A%20A%20mathematical,to%20raise%20to%2C%20to%20get

https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation

https://skerritt.blog/big-o/

https://towardsdatascience.com/introduction-to-big-o-notation-820d2e25d3fd



