# Modern JavaScript 

## ES6 fat Arrow function


```
let math =(a,b)=>{
    return a + b
}
console.log(math(10,20))
```

## Truthy falsy

```
//False values = 0,null,undefined,NaN;
```

## Ternary Operator

```
let age = 18;
if(age>=18){
    console.log("Adult")
}
else{
     console.log("Child")
}

//Ternary

(age>=18)  ? "Adult" : Child

```


## Array find() method

```
let numbers = [1,2,3,4,5,6,7,8,9]

let result = numbers.find(function(currValue){
    return currValue > 5
});
console.log(result) //Ans:6
```

## Array push() method 

```
let numbers = [1,2,3,4]
let result = numbers.push(5,6,7)
console.log(result)

Output = [1,2,3,4,5,6,7]
```

## Array map() method 

### 1.
```
let numbers = [1,2,3,4]

let result = numbers.map((num)=>{
    return = num * 2
})
console.log(result)

Output = [2,4,6,8]
```
### 2.

```
let users = [
    {
        name:"Abdullah Al Nirob"
    },
    {
        name: "Arafat Islam"
    },
    {
        name:"Saiful Islam Rafel"
    }
]

    users.map((user)=>{
    console.log(`His name is` ${user.name})
})

 Output = 
 His name is Abdullah Al Nirob
 His name is Arafat Islam
 His name is Saiful Islam Rafel
```

## Loop

### For loop

```
for(let i=0;i<=10;i++){
    console.log(i)
}

Output =
0
1
2
3
4
5
6
7
8
9
```
### For of loop
```
let array = [1,2,3,4,5,6,7]

for(element in array){
    console.log(element)
}
Outpur=
1
2
3
4
5
6
7
```

### For in Loop

```
let obj =[{
    name:"java",
    is:"Programming Language"
    },
]

for(myObj in obj){
    console.log(myObj)
}
Output =
    name
    is

```

## Spread Operator 

```
let numbers = [1,2,3,4,5,6]
let newNumber = [...numbers,7,8,9]
console.log(newNumber)

Output = [1,2,3,4,5,6,7,8,9]
```

## Template Literals

```
let name = "Abdullah Al Nirob"
console.log(`My name is ${name}`)

Output = My name is Abdullah Al Nirob
```
