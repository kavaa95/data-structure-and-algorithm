# data-structure-and-algorithm

#Given an array of integers, find the sum of its elements.

#For example arr=[1,2,3],1+2+3=6 so return 6.


function simpleArraySum(ar) {
    // Write your code here
    var sum=0;
    for(var i=0;i<ar.length;i++){
        sum+=ar[i]
    }
    return sum;
}
