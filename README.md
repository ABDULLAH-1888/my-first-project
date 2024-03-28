func addGreetingWord(number: Int, name: String) -> String {
    var greeting: String
    
    if number == 1 {
        greeting = "Hi"
    } else if number == 0 {
        greeting = "Bye"
    } else {
        greeting = "Invalid number"
    }
    
    let finalText = greeting + " " + name
    return finalText
}

let inputNumber = 1
let inputName = "Sally"

let result = addGreetingWord(number: inputNumber, name: inputName)
print(result)