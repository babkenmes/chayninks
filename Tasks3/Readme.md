
### 1. Ֆունկցիա որը մարդկանց տվյալներով զանգված և վերադարձնում նրանց աշխատավարձերի գումարը
```javascript 
//Օրինակ․
getBudget([
  { name: "John", age: 21, budget: 23000 },
  { name: "Steve",  age: 32, budget: 40000 },
  { name: "Martin",  age: 16, budget: 2700 }
]) // 65700

getBudget([
  { name: "John",  age: 21, budget: 29000 },
  { name: "Steve",  age: 32, budget: 32000 },
  { name: "Martin",  age: 16, budget: 1600 }
]) // 62600
```

### 2. Ունենք հյուրերի ցանկով օբյեկտ իրենց երկրներով, գրել ֆունկցիա որը կվերադարձնի ողջույնի նախադասություն "Hi! I'm [name], and I'm from [country]."
```javascript 
//Օրինակ․
const GUEST_LIST = {
  Randy: "Germany",
  Karla: "France",
  Wendy: "Japan",
  Norman: "England",
  Sam: "Argentina"
}

greeting("Randy")// "Hi! I'm Randy, and I'm from Germany."

```

### 3. Ֆունկցիա որը հաշվում է առաքման գումարը, եթե ապրանքների ընդհանուր արժեքն անցնում է 50$-ը առաքումն անվճար է հակառակ դեպքում ամեն ապրանքի համար 1.5$
```javascript 
//Օրինակ․

shippingCost([{productName:"Shampoo", price:8},{productName:"Soap", price:2} ]) // 3
shippingCost([{productName:"Samsung TV", price:500},{productName:"Battery", price:5} ]) // 0

```
