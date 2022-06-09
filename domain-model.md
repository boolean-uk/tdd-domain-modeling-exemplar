| Objects | Properties | Messages | Scenario | Output | Example |
|---------|------------|----------|----------|--------|---------|
| Item    |            |          |          |        |         |
| Basket  | items @Array, maxCapacity @number| addItem(@Item)|| the added Item | addItem(item) => {}
|         |            | isFull() | basket is not full| false | isFull() => false
|         |            | isFull() | basket is full| true | isFull() => true