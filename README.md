# ClubYdacha
1) В верхней панели зайти во вкладку Build->Genereted Signed APK...
2) Нажать Create new... Далее укачать путь  "Key store path:", заполнить password там их будет два можно разные сделать можно поставить один и тот же (я бы советовал второй вариант чтобы не путаться дальше), и заполнить Firs and Last Name(Если приложение до этого не подписывалось,
если оно уже подписывалось и нужно накотить обновление Choose existing... И указать путь к ключу)
ВАЖНО пароли будут нужны дальше поэтому их НУЖНО запонить или записать в противном случае если накатывать обновление а ключ будет другой это будет считаться другим приложением
3) После создание или указание ключа заполнить два пароля "Key store password" и "Key password"
4) Поставить галочку (V1 jar signature) и нажать кнопку "FINISH"
5) В студии высветиться окно Build genereted succsess и нажать на local в этом окне и появиться файловая система в папке release лежит подписанная apk. Если не успел нажать зайди в проект из файловой системы, и открой папку app и в ней папку release и там будет release apk.
