author:
  name: Tamas Foldi
  twitter: tfoldi
  url: http://jordanscales.com
output: basic.html
controls: true
theme: sjaakvandenberg/cleaver-light

--

# Going Functional
## Three programming languages what every data scientist should learn

--

# Why should I learn a new language?

--

**Clojure** Impure, Functional, Dynamically typed

#### Haskell

Pure, functional, Static 

#### Julia

Dynamic, Performance oriented

--

### A textual example

Content can be written in **Markdown!** New lines no longer need two angle brackets.


```haskell
  -- fibonacci sequence
  unfoldr (\(f1,f2) -> Just (f1,(f2,f1+f2))) (0,1)
 
  fibs = 0:1:zipWith (+) fibs (tail fibs)
 
  fib = 0:scanl (+) 1 fib -- also seen as: fibs = fix ((0:) . scanl (+) 1)

```

--
### Heading four
### Heading five

--

### A list of things

* Item 1
* Item B
* Item gamma

No need for multiple templates!
