# UnityAutoTranslation  

## Русский

* Текущий статус работы над проектом  

Я смог в ручном режиме перевести некоторые игровые элементы: тексты в диалогах, надписи над элементах графического интерфейса, а также системные тексты.
Сейчас разрабатывается логика приложения, которое при вводе hex-кода из оригинального файла модифицирует его таким образом, чтобы не было критический ошибок при его запаковке обратно в ресурсы движка.

В ходе тестов было обнаружено 3 пути возникновения ошибок:
1. не изменение предшествующего тексту числа блоков hex-кода;
2. смещение символов границ файла;
3. некорректное изменение размера длины hex-кода при кодировке русского текста в hex-код.

**Прошу обратить внимание:** есть ОЧЕНЬ большая вероятность, что написанное приложение будет корректно обрабатывать только конкретную игру, а другие игры - с некоторой вероятностью, начиная от 25% успеха (не спрашивайте почему).

## English

* Current project work status  

I was able to manually translate some game elements: texts in dialogs, inscriptions above the elements of the graphical interface, as well as system texts.
Now the application logic is being developed, which, when entering a hex-code from the original file, modifies it so that there are no critical errors when packing it back into the engine resources.

During the tests, 3 ways of error occurrence were found:
1. not changing the number of hex blocks preceding the text;
2. offset of characters of file borders;
3. incorrect resizing of the length of the hex-code when encoding Russian text to hex-code.

**Please note:** there is a VERY high probability that the written application will correctly process only a specific game, and other games - with a certain probability, starting from 25% of success (do not ask why).
