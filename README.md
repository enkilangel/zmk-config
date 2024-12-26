### Инструкция по самостоятельной прошивке
1. Зарегистрируйтесь или войдите на GitHub, нажав Sign Up для регистрации или Sign In для входа справа вверху на этой странице
2. Сделайте форк этого репозитория в свой аккаунт GitHub - для этого нажмите кнопку Fork (третья по счету справа от названия репозитория) на [главной странице репозитория](https://github.com/oneofthemoons/zmk-config/tree/master)
 и проследуйте дальнейшим инструкциям от GitHub
3. Перейдите на ресурс https://nickcoutsos.github.io/keymap-editor/ и нажмите на кнопку "Authorize". Авторизуйте свой форк репозитория согласно инструкции на ресурсе
4. Поздравляем! Теперь вы можете настроить прошивку прямо в графическом интерфейсе
5. После внесения собственных настроек нажмите кнопку "Save" и придумайте любое название для ваших изменений
6. Перейдите на страницу вашего форкнутого репозитория через раздел "Repositories" в вашем аккаунте GitHub
7. Выберите вкладку Actions
8. Дождитесь, пока слева от самого верхнего action-а в списке появится зеленый кружочек, означающий, что сборка прошивки завершена
9. Перейдите в самый верхний action в списке, нажмите на "firmware"
10. Скачается архив с прошивкой, разархивируйте его
11. Подключите левую половинку к компьютеру по проводу
12. Дважды нажмите кнопку RESET (маленькая кнопка на самом правом краю левой половинки)
13. К вашему компьютеру будет подключена флешка с названием NICENANO, перетащите на эту флешку файл settings_reset\*.uf2 (вместо звездочки может быть любая надпись)
14. Повторите шаг 12
15. Перетащите на флешку NICENANO файл с названием \*_left\*.uf2 (вместо звездочки может быть любая надпись)
16. Повторите шаги 11-14 для правой половинки клавиатуры
17. Перетащите на флешку NICENANO файл с названием \*_right\*.uf2 (вместо звездочки может быть любая надпись)
18. Ваша клавиатура прошита, можете отключать провод от правой половинки и тестировать результат

Если вы столкнулись с трудностями во время прошивки, свяжитесь с нами по контактам в инструкции или [на нашем сайте](https://klavus.tech/contacts).