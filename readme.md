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

##### `True` case in boolean example:
- [x] floatNumber = 10.5 :arrow_right: isBool = bool(floatNumber) `// True`
- [x] number = 10 :arrow_right: isBool = bool(number) `// True`
- [x] number = -2 :arrow_right: isBool = bool(number) `// True`
- [x] string = " " :arrow_right: isBool = bool(string) `// True`
- [x] string = "hello" :arrow_right: isBool = bool(string) `// True`
- [x] 10 > 5 :arrow_right: `// True`
- [x] 12 >= 12 :arrow_right: `// True`
- [x] 3 < 4 :arrow_right: `// True`
- [x] 4 <= 4 :arrow_right: `// True`
- [x] not False :arrow_right: `// True`
- [x] 5 == 5 :arrow_right: `// True`
- [x] 4 != 5 :arrow_right: `// True`
##### `False` case in boolean example:
- [x] floatNumber = 0.0 :arrow_right: isBool = bool(floatNumber) `// False`
- [x] number = 0 :arrow_right: isBool = bool(number) `// False`
- [x] string = "" :arrow_right: isBool = bool(string) `// False`
- [x] 10 < 5 :arrow_right: `// False`
- [x] 12 < 12 :arrow_right: `// False`
- [x] 12 <= 2 :arrow_right: `// False`
- [x] 3 >= 4 :arrow_right: `// False`
- [x] 4 > 4 :arrow_right: `// False`
- [x] 2 > 4 :arrow_right: `// False`
- [x] not True :arrow_right: `// False`
- [x] 5 == 6 :arrow_right: `// False`
- [x] 5 != 5 :arrow_right: `// False`

### 4. Float
Floating point numbers are decimal values or fractional numbers like `133.5, 2897.11, and 3571.213`
<i>Example: </i>
- [x] scoreAvg = 10.5
- [x] money = 1.6

#### Float conversion
> Convert integer, string and boolean to boolean

- [x] string = "10" :arrow_right: floatNumber = float(string) `// 10.0`
- [x] number = 10 :arrow_right: floatNumber = float(number) `// 10.0`
- [x] isBoolean = True :arrow_right: floatNumber = float(isBoolean) `// 1.0`
- [x] isBoolean = False :arrow_right: floatNumber = float(isBoolean) `// 0.0`

