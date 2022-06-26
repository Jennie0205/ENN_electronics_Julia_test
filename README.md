# The uploaded ipynb file includes 
## 1. Fibonacci number calcularion function 
     
function fibonacci_num(n) 
\# input n: n is a term in the Fibonacci number
\# output : nth Fibonacci number 
    
    if n <= 1 || isinteger(n)!= true 
        return "Not valid number"
    else
        \# calculate the Fibonacci numbers using the Golden Ratio
        return round(((1+5 ^ 0.5) / 2 )^n / (5 ^ 0.5))
    end
end
      
## 2. String reverse function
function reverse_string(s)
\# input s: given string
\# output reverse_s : reversed given string
    
    \# Split given string with space and return them as string array
    arr_s = split(s, " ") 
    \# join elements in arr_s with reversed order
    reverse_s = join(reverse(arr_s), " ")
    return (reverse_s)
end
