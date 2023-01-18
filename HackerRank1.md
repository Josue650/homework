 ```
 function plusMinus(arr) {
    // Write your code here
    let pos = 0, neg = 0, zero = 0

    for(let i = 0; i < arr.length;i++){
        if(arr[i] > 0){
            pos++
        } else if ( arr[i] < 0){
            neg++
        } else {
            zero++
        }
    }
      console.log((pos/arr.length).toFixed(6))
        console.log((neg/arr.length).toFixed(6))
          console.log((zero/arr.length).toFixed(6))
}
```
### For this problem the question is asking to create a fuc=nction that goes through each element. For ex pos is one neg is another and zero is the last. I got the logic of creating the variables and seting them to equal 0. Then i crate a for loop to go through the array. I then create a if, else if , else and add every time the array touches pos, neg or zero. I got the answer wrong the first time, but not because of the logic. I was console logging in the wrong place, also only console logging one of the values. After speaking with arthur he pointed me in the right direction.
