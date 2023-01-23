
https://en.wikipedia.org/w/index.php?title=Automated_readability_index&oldid=1011143677  

Мы создадим программу вычисляющую Автоматический индекс удобочитаемости (ARI). Формула была представлена в 1968 году и множество научных работ основано на ней. Индекс вычисляется по следующей формуле:  

                               score=4.71×characters / words+0.5×words / sentences−21.43  

Также программа должна читать файл, а не ввод с терминала. Вы указываете название файла через аргумент командной строки.  

Программа должна вывести сам индекс и приблизительный возраст требуемый для понимая текста  

Используйте функции округления для вычисления индекса как натурального числа.  

Также вывести количество символов, слов, и предложений которые есть в тексте.  

Число символов - это любой видимый символ (потому что в настоящем тексте, символ - это все кроме пробела, новой строки и табуляции).  

Пример 1  

ввод: java Main in.txt  
Readability is the ease with which a reader can understand a written text. In natural language, the readability of text depends on its content and its presentation. Researchers have used various factors to measure readability. Readability is more than simply legibility, which is a measure of how easily a reader can distinguish individual letters or characters from each other. Higher readability eases reading effort and speed for any reader, but it is especially important for those who do not have high reading comprehension. In readers with poor reading comprehension, raising the readability level of a text from mediocre to good can make the difference between success and failure

вывод:  
Words: 108  
Sentences: 6  
Characters: 580  
The score is: 12.86  
This text should be understood by 17-18 year-olds.  

Пример 2  

ввод: java Main in.txt  

This is the page of the Simple English Wikipedia. A place where people work together to write encyclopedias in different languages. That includes children and adults who are learning English. There are 142,262 articles on the Simple English Wikipedia. All of the pages are free to use. They have all been published under both the Creative Commons License 3 and the GNU Free Documentation License. You can help here! You may change these pages and make new pages. Read the help pages and other good pages to learn how to write pages here. You may ask questions at Simple talk.  
вывод:  
Words: 100  
Sentences: 10  
Characters: 476  
The score is: 5.98  
This text should be understood by 10-11 year-olds.   
