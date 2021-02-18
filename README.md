# A1. Простой стек

|		      |				       |
| ------------------- | ------------------------------ |
| Ограничение времени | 1 секунда                      |
| Ограничение памяти  | 64Mb                           |
|Ввод                 |стандартный ввод или input.txt  |
|Вывод 	              |стандартный вывод или output.txt|

Напишите программу моделирующую работу стека. Программа считывает последовательность команд и в зависимости от команды выполняет ту или иную операцию. После выполнения каждой команды программа должна вывести одну строчку. Возможные команды для программы: 

**push n**- Добавить в стек число n (значение n задается после команды). Программа должна вывести ok.

**pop**   - Удалить из стека последний элемент. Программа должна вывести его значение.

**back**  - Программа должна вывести значение последнего элемента, не удаляя его из стека.

**size**  - Программа должна вывести количество элементов в стеке.

**clear** - Программа должна очистить стек и вывести ok.

**exit**  - Программа должна вывести bye и завершить работу. 
	

## Формат ввода

Команды управления стеком вводятся в описанном ранее формате по 1 на строке.

Гарантируется, что набор входных команд удовлетворяет следующим требованиям: максимальное количество элементов в стеке в любой момент не превосходит 100, все команды pop и back корректны, то есть при их исполнении в стеке содержится хотя бы один элемент.


## Формат вывода

Требуется вывести протокол работы со стеком, по 1 сообщению в строке.

### Пример
| -------- | -------- |
|Ввод      |   Вывод  |
|push 1    |    ok    |
|back      |    1     |
|exit      |   bye    |

	




