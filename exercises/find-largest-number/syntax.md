# Syntax: Find Largest Number

## Contents <!-- omit in toc -->

- [JavaScript](#javascript)
- [Ruby](#ruby)
- [Python](#python)

## JavaScript

```javascript
function findLargestNumber(pile) {
  let maxSoFar = pile[0];

  for(let number of pile) {
    if (number > maxSoFar) {
      maxSoFar = number;
    }
  }

  return maxSoFar;
}

let pileOfNumbers = [1, 4, 10, 9, -3, 20, 18];
let largestNumber = findLargestNumber(pileOfNumbers);

console.log(largest_number);

```

## Python

```javascript
def find_largest_number(numbers):
  max_so_far = numbers[0]

  for number in numbers:
    if number > max_so_far:
      max_so_far = number

  return max_so_far

pile_of_numbers = [1, 4, 10, 9, -3, 20, 18]
largest_number = find_largest_number(pile_of_numbers)

print(largest_number)

```

## Ruby

```javascript
def find_largest_number(numbers)
  max_so_far = numbers.first

  numbers.each do |number|
    if number > max_so_far
      max_so_far = number
    end
  end

  return max_so_far
end

pile_of_numbers = [1, 4, 10, 9, -3, 20, 18]
largest_number = find_largest_number(pile_of_numbers)

puts(largest_number)

```
