
#Nafen Token 

* Владелец токена может сжечь свои токены, при этом на контракте токена будет вызван эвент сообщающий о том что "адресс дрежателя" сжег x Токенов, это сделано для возможности рефанда инвесторам попавшим в черный список

#Nafen Crowdsale

*Токен нельзя перемещать до завершения ICO 
* При деплое контракта указывается время начала каждой из фаз и сколько каждая из них длиться. А таже адресс кошелька на который будут переводиться деньги после окончания краудсейла и адрес куда будут переведены токены для команды.
* Фиксируем курс эфира к Евро.
* Возможно частичное снятие средств, в промежутки между стадиями ICO
* Курс может быть изменён только ораклом
* На протяжении всего краудсейла действует система скидок из таблицы.
* На протяжении всего краудсейла могут инвестировать только люди находящиеся в белом списке.
* В белый список инвесторов может добавлять владелец контракта а также Менджер Крапудсейла.
* Менеджер Краудсейла устанавливается владельцем контракта в любой момент времени и может быть изменен в дальнейшем.
* Менеджер и владелец контракта могут выпускать токены вручную используя функцию manualTransfer. 
* По окончании краудсейла после вызова функции finishCrowdsale будет выпущено еще 5% от общего колличества токенов для команды и оттправлено на адрес указанный при деплое
