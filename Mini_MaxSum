// Task2:Max-Minsum
let arr= [1,2,7,3,9,8,4,5];
let accending = arr.sort((a,b) =>  a-b);
let Min_Find = accending[0];
let desending = arr.sort((a,b) =>  b-a);
let Max_Find = desending[0];
// console.log(Max_Total);
let total_value = arr.reduce(function(a,b){
return (a+b);
});
let Max_Total = total_value - Min_Find;
let Min_Total = total_value - Max_Find;
console.log(Min_Total, Max_Total);
