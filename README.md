# Non-Graded Challenge

_Non Graded Challenge ini dibuat untuk latihan dari tugas tugas yang telah diberikan._

---

## Tugas

## Non Graded Challenge 1 : Python Syntax, Variables, and Data Type

### Task #1

Given list of customer_id that doing transaction in 1 day:
   customer_id = ['B818', 'A461', 'A092', 'A082', 'B341', 'A005', 'A092', 'A461','B219', 'B904', 'A901', 'A083', 'B904', 'A092', 'B341', 'B821','B341', 'B821', 'B904', 'B818', 'A901', 'A083', 'B818', 'A082','B219', 'B219', 'A083', 'A901', 'A082', 'B341', 'B341', 'A083','A082', 'B219', 'B439', 'A461', 'A005', 'A901', 'B341', 'A082','A083', 'A461', 'A083', 'A901', 'A461', 'A083', 'A082', 'A083','B341', 'A901', 'A082', 'A461', 'B219', 'A083', 'B818', 'B821','A092', 'B341', 'A461', 'A092', 'A083', 'B821', 'A092']
   
How many unique customer_id from above list?

### Task #2

Given list of:
   Data = [1, 4, 9, 16, 25, 36, 49,  64, 81, 100]
   
Use indexing so you can get this output:
   1. 16
   2. [36, 49, 64, 81]
   3. [100, 81, 64, 49, 36, 25, 16, 9, 4, 1]

### Task #3
Given a dictionary of:
   provinsi = {'Nanggroe Aceh Darussalam': 'Aceh',
               'Sumatera Selatan': 'Palembang',
               'Kalimantan Barat': 'Pontianak',
               'Jawa Timur': 'Madiun',
               'Sulawesi Selatan': 'Makassar',
               'Maluku': 'Ambon'}
   
What python command can be use to:
   1. Get list of keys available in dictionary
   2. Change 'Jawa Timur' value from 'Madiun'  to 'Surabaya'


## Non Graded Challenge 2 : Python Function, Conditional, and Loop

### Task #1 - Number of Word

**Create a function that count the number of word in a sentence.**
**Instruction:**
   1. Create function called `number_of_word`.
   2. This function takes 1 input, `sentence`.
   3. Inside this function, you can utilize `.split()` method to split the sentence into list of word(s).
   4. Also, `len()` function to count the element inside a list.
   5. Return the number of word from the sentenc?

**Example:**
   - Input: number_of_word(sentence = ’Hello World!’)
   - Output: 2
   
   - Input: number_of_word(sentence = ’Once Upon a Time in a faraway land’)
   - Output: 84


### Task #2 - Find Multiple

**Create a function that will get list of number(s) from a certain range that multiples of given number.**

**Instruction:**
   1. Create function called `find_multiples`.
   2. This function takes 3 input: `start_range`, `end_range`, and `multiple`.
   3. From every number within the given range, check if that number is the mutliples of `multiple`.
   4. Return list of the possible multiple number(s).
   
**Example:**
   - Input: find_multiple(start_range= 1, end_range= 20, multiple= 5)
   - Output: [5, 10, 15, 20]

   - Input: find_multiple(start_range= 1, end_range= 50, multiple= 10)
   - Output: [10, 20, 30, 40, 50]

### Task #3 - Grade Converter

**Create a function that will convert student’s grade to GPA.**

**Instruction:**
   1. Create function called `Grade_Converter`.
   2. This function takes input: `convert_to` and n-paired of student(s) name with its respective score.
   3. Input argument for `**convert_to**` is either `**letter_grade**` or `**gpa**`.
   4. You can utilize **kwargs input argument to generate n-length paired of student(s) name with its respective score (Dictionary).
   5. This function will return dictionary of student’s name along with converted Letter Grade or GPA, depending on user input in `convert_to` parameter
   
| Score Range | Letter Grade | GPA 4.0 Scale |
|-------------|--------------|---------------|
| 85 - 100    | A            | 4.0           |
| 70 - 84.99  | B            | 3.6           |
| 60 - 69.99  | C            | 2.5           |
| 50 - 59.99  | D            | 1.5           |
| 40 - 49.99  | E            | 1.0           |
| 0 - 39.99   | F            | 0.0           |

**Example:**
   - Input: Grade_Converter(convert_to='gpa', Adam=62, Faiz=91)
   - Output: {'Adam': 2.5, 'Faiz': 4}
   
   - Input: Grade_Converter(convert_to='letter_grade', Albert=90, Dwi=82, Syahdan=58, Veronica=84)
   - Output: {'Albert': 'A', 'Dwi': 'B', 'Syahdan': 'D','Veronica': 'B'}