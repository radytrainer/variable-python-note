## Variable in Python

### 1. Integer
Integer is an number that represents from `-Infinity to +Infinity`

<i>Example: </i>
- [x] positiveNumber = 10
- [x] negativeNumber = -9
- [x] age = 30
- [x] numberOfStudent = 25
- [x] numberOfCar = 100
#### Integer conversion
> Convert  string, float and boolean to integer
- [x] string = "10" :arrow_right: number = int(string) `// 10`
- [x] string = "A" :arrow_right: `ValueError: invalid literal for int() with base 10: 'A'`
- [x] floatNumber = 10.5 :arrow_right: number = int(floatNumber) `// 10`
- [x] number = 10 :arrow_right: string = str(number) `// "10"`
- [x] isBoolean = True :arrow_right: number = int(isBoolean) `//1`
- [x] isBoolean = False :arrow_right: number = int(isBoolean) `//0`

### 2. String
String is a collection of alphabets, words or other characters. String represent in double quote `" "` or single quote `' '`

<i>Example: </i>
- [x] firstName = "Rady"
- [x] lastName = "Y"
- [x] schoolName = 'PNC'
- [x] studentName = 'Bopha'
- [x] text = "Hello world in 1995"

#### String conversion
> Convert integer, float and boolean to string

- [x] floatNumber = 10.5 :arrow_right: string = str(floatNumber) `// "10.5"`
- [x] number = 10 :arrow_right: string = str(number) `// "10"`
- [x] isBoolean = True :arrow_right: string = string(isBoolean) `// "True"`
- [x] isBoolean = False :arrow_right: string = string(isBoolean) `// "False"`


### 3. Boolean
 Boolean variable can have only two values - `True` or `False`. Boolean values mostly happen in comparisons `>, <, >=, <=, not, ==, !=`

<i>Example: </i>
- [x] isFound = True
- [x] isLetterA = False
- [x] hasA = True
- [x] isGreaterThan = 10 > 10 `// False`
- [x] iEqualTo = 10 == 10  `// True`
#### Boolean conversion
> Convert integer, float and string to boolean

##### `True` case in boolean:
- [x] floatNumber = 10.5 :arrow_right: isBool = bool(floatNumber) `// True`
- [x] number = 10 :arrow_right: isBool = bool(number) `// True`
- [x] string = " " :arrow_right: isBool = bool(string) `// True`
- [x] string = "hello" :arrow_right: isBool = bool(string) `// True`

