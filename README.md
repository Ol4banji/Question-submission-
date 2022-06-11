[
https://play.onflow.org/cdcc9393-6a2c-4a40-a9e4-0b709fe492d4?type=script&id=0ee2a8f8-3e05-4167-a3bc-c88500856ac1&storage=none](https://play.onflow.org/local-project?type=script&id=local-script-temp-0&storage=none)# Question-submission-


 Chapter 1 Day 1

-Blockchain in my own words is an open, decentralized, shared databased used openly to store data -Smart contract are programs created to specify some functionality users can interact with -Script is where user view data on blockchain while transaction is a paid function for users on blockchain

Chapter 1 Day 2

-It maximizes efficiency while maintaining the highest level of security It's code is easy to read, declarative, allows developer to express their intention directly -It's similar to other programming language and easy to transition to if you have prior knowledge Its debug in an easy manner, makes error message very clear -Its an Resource Oriented Programm as it uses core things called resource which defines mostly everything in Flow Blockchain

Chapter 2 Day 1

https://play.onflow.org/cdcc9393-6a2c-4a40-a9e4-0b709fe492d4?type=script&id=29b1e3ce-b4cc-42b3-ad7d-e41d695670a6&storage=none

Chapter 2 Day 2

-We wouldn’t call changeGreeting in a script because scripts are used to view data, and changeGreeting is used to modify data

-AuthAccount in prepare phase of transaction is use to access data in the account created on the flow prepare phrase in transaction is used to access the information/data in the account while the execute phase is used to call functions and do stuff to change the data on the blockchain

https://play.onflow.org/cdcc9393-6a2c-4a40-a9e4-0b709fe492d4?type=script&id=60140ab1-5211-4869-8b48-24981f1be550&storage=none

Chapter 2 Day 3

https://play.onflow.org/local-project?type=script&id=local-script-temp-0&storage=none

https://play.onflow.org/local-project?type=script&id=local-script-temp-0&storage=none

The ! force unwrap operator is used to unwrap optional variables forcly. Since the operation is forced it will fail or exit the code if the value is nil.

pub fun main() {
    var int5: Int? = 5
    var unwrappedInt1: Int = int5!  

    var int7: Int? = nil
    var unwrappedInt2: Int = int7! 
}

The error message states that it is expecting a string to be returned not an optional

The variable returned is a dictionary and dictonaries always return as an optional

You could fix this by using ! to force unwrap the returned value or preferably change the return type to accept the optional and allow the error be handled.
