# lesson78-79
Болкарева Анна

1-Один из методов защиты информации от неправомерного доступа это шифрование, т. е. кодирование специального вида. Шифрование это преобразование (кодирование) открытой информации в зашифрованную, недоступную для понимания посторонними 

2-Ключ это параметр алгоритма шифрования (шифра). позволяющий выбрать одно конкретное преобразование из всех вариантов, предусмотренных алгоритмом. Знание ключа позволяет свободно зашифровывать и расшифровывать сообщения

3-Методы шифрования и расшифровывания сообщения изучает наука криптология, история которой насчитывает около четырех тысяч лет. Она состоит из двух ветвей: криптографии и криптоанализа

4-Симметричный шифр означает, что и для шифрования, и для расшифровывания сообщений используется один и тот же ключ. Единственный минус симметричного шифрования — сложность передачи секретного ключа в самом начале от одного участника к другому.

5-Асимметричное шифрование – метод шифрования информации, который предполагает использование сразу двух ключей. А именно – открытого и закрытого. Открытый (или публичный) ключ используется для непосредственного шифрования данных и может передаваться по незащищенным каналам. Закрытый (или приватный) ключ используется для расшифровки полученной информации. Сами ключи представляют собой очень большие числа, связанные друг с другом определенной функцией. Несмотря на такую связь, зная один ключ, вычислить второй крайне сложно. Стойким считается алгоритм, который для успешного раскрытия требует от противника недостижимых вычислительных ресурсов, недостижимого объёма перехваченных сообщений или такого времени, что по его истечении защищённая информация будет уже не актуальна

6-Криптостойкость шифра это устойчивость шифра к расшифровке без знания ключа

Задачи

1-сдйо фыфшуф зкцеш шфтщ, эктщ мксёдш зкцошв

3-рубикон перейдён, сдвиг 27

#79

1-Хэш-функция (от англ. hash мешанина, крошить), а само полученное число называется хэш-кодом, хэш-суммой или просто хэшем исходной строки. Важно, что, зная хэш-код, невозможно восстановить исходный пароль! В этом смысле хэширование это необратимое шифрование

2-В случае поиска в словаре по ключу (а в словаре только такой и возможен), также вызывается хеш-функция для ключа, хеш преобразуется в индекс, по которому производится поиск нужных данных и возврат искомого значения

3-Такая ситуация - совпадение хэш-кодов различных исходных строк - называется коллизней (англ. collision столкновение). Коллизии будут всегда ведь мы «сжимаем длинную цепочку байтов до числа. Казалось бы, ничего хорошего не получилось: если взломщик узнает хэш-код, то, зная алгоритм его получения, он сможет легко подобрать пароль с таким же хэшем и получить доступ к данным. Однако это произошло потому, что мы выбрали плохую хэш-функцию

4-Криптостойкой хеш-функция может быть только в том случае, если выполняются главные требования: стойкость к восстановлению хешируемых данных и стойкость к коллизиям, то есть образованию из двух разных массивов данных двух одинаковых значений хеша

5-Здесь выражение «невозможно за приемлемое время» (или «вычислительно невозможно») означает, что эта задача решается только перебором вариантов (других алгоритмов не существует), а количество вариантов настолько велико, что на решение могут уйти сотни и тысячи лет

6-Даже если взломщик получил хэш-код пароля, он не сможет за приемлемое время получить сам пароль (или пароль, дающий такой же хэш-код)

7-Надёжные пароли должны состоять не менее чем из 7-8 символов; пароли, состоящие из 15 символов и более, взломать методом «грубой силы» практически невозможно. Не используйте пароли типа «12345», «qwerty», свой день рождения, номер телефона. Плохо, если пароль представляет собой известное слово, для этих случаев взломщики используют подбор по словарю

8-Сложнее всего подобрать пароль, который представляет собой случайный набор заглавных и строчных букв, цифр и других знаков

9-Сегодня для хэширования в большинстве случаев применяют алгоритмы MD5, SHA1 и российский алгоритм, изложенный в ГОСТ Р34.11-94 (он считается одним из самых надёжных). В криптографии хэш-коды чаще всего имеют длину 128, 160 и 256 битов

10-
