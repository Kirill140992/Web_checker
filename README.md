# Web_checker
Скрипт проверяет загрузился ли сайт и находит элемент на загруженном сайте, если есть ошибка, то отправляет сообщение в Slack. 
Бывает возникат проблема, на метриках выглядит, что сайт активн и работает, по факту, клиент видит только страницу загрузки. Ставить алерт на nginx, посчитал немного не верно, поэтому сделал скрипт, потом поставил его в крон, для проверку через промежуток времени
