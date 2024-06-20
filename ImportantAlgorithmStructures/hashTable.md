# Hash Table

We can explain everything with a visual and example.

Example: Price of products in the supermarket.

"apple,3", "pear,7" 

If I only use arrays it would be a waste of my time so we will use *Hash Table*.

Alright, How do we use the hash table?

+ First we will create an array where the number of elements is equal.
+ We will enter the name of the products into the function as input, we will take the function result as the index of the array.

> [!NOTE]
> This function is called hash function and Hash Function + Arrays = Hash Table


To give an example: Function input: apple and output (array index: 3)

Well function outputs == array indexes


Let's give an illustrated example:

![yeni](https://github.com/isleyen/importantAlgorithmStructures/assets/136992260/3de85d77-c6d8-4402-826f-161049428a15)

*Key 4 = apple* and after function operation *(value 4)apple = (index) 3*.

Summary:

+ The function uses the index of the arrays as labels.
+ Arrays provided fixed-time access

## Hash Function
+ "same input = same output" because index uses different slot. For instance "apple,3" This index is certain. I look at different times and these indexes are the same so this is still "apple,3".
+ "different input = different output" because I set it to "apple,3" and "pear,7" so apple can't take any other value than 3, and pear can't take any other value than 7.
+ The size of the array must be at the limit of the output of the hash table to give an example if "apple,3", my array must have at least 4 indexes(0,1,2,3).
> [!WARNING]
> Unfortunately, it does not always give different outputs for the same input.
> This is also called "collision".

## Collision
![341477619-c271f4c5-b57d-4f8a-9fb7-e4acaba60044](https://github.com/isleyen/importantAlgorithmStructures/assets/136992260/09c63aeb-87fd-401c-adfe-41a32b534273)

![341477676-67659c3b-24b8-4a2c-a079-1d9888e128a1](https://github.com/isleyen/importantAlgorithmStructures/assets/136992260/9eaf7325-823d-40e8-9488-42556a9835fb)

![341477788-41c02719-a48f-4d4f-98f4-91fede9548c1](https://github.com/isleyen/importantAlgorithmStructures/assets/136992260/674bf6f2-7f79-4c53-b3c8-b53eeec8ab30)





