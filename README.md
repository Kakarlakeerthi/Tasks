//4.reverse the order of elements
arr = [23,45,12,67,89,34]
result = arr.reverse()
console.log(result)

//5.find max value in the array 
arr = [23,45,12,67,89,34]
result = arr.reduce((acc, current) => Math.max(acc, current));
console.log(result)

//6.second largest 
arr =  [10,5,8, 20,15,12] 


function secondLargest(arr) {
  var max1st = arr[0];
  var max2nd = 0;
  
  for(let i=0; i<arr.length; i++) {
    if(arr[i] > max1st) {
      max2nd = max1st;
      max1st = arr[i];
    }
    else if(arr[i] > max2nd && arr[i] != max1st) {
      max2nd = arr[i];
    }
  }

  return max2nd;
}

console.log(secondLargest(arr))

//7.sum of all numbers 
arr = [1,2,3,4,5,6,7,8,9]
result = 0
function sum_of_even(arr) {
    for(let i of arr){
        if(i%2==0){
            result = result + i
        }
    }
    console.log(result)
}

sum_of_even(arr)
