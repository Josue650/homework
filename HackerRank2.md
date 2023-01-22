```
function miniMaxSum(arr) {
    // Write your code here
    let min = 0
    let max = 0
    for(let i = 0; i < arr.length; i++){
        min = arr[0] +  arr[1] + arr[2] + arr[3]
        max =  arr[1] + arr[2] + arr[3] + arr[4]
    }
    console.log(min, max)

}
```

### For this problem ive been trying to figure it out for the past 4 days. I feel like my thought process is right but i dont think im implementing it correct. So what i want to do is take the first 4 elements of the array and add those. Then for max take all the elements exept the fourth. but i keep getting the wrong output.
