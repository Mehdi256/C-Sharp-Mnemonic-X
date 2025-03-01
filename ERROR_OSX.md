# ENGLISH
When an "Operation not permitted" error occurs

MacOSX Mojave, Catalina, Big Sur, Monterey.


Enable full disk access for terminal

Click on the Apple logo and select System Preferences.
In the new window, find and open Security & Privacy.
Select the "Privacy" tab, find "Full Disk Access" on the left sidebar.
Click on the padlock in the left corner and use Touch ID or passcode to unlock it.
If Terminal appears in the left pane but is checked, check its box. Select "Quit and reopen" to give Terminal full access to the drive.
If not, click the + icon in the right pane and find "Terminal" in Applications, click "Open".
Then the Terminal will appear in the list of allowed applications with the checkbox checked.
Launch Terminal and enter the same command that is causing the "Operation not permitted" error to see if it works now.



Mac OS X High Sierra


Temporarily disable System Integrity Protection

Does the "Operation not permitted" message still appear after enabling full disk permission for the terminal? You can then temporarily disable System Integrity Protection on your Mac. Developers need to disable SIP to test code, debug applications, and install system extensions on Mac. After you complete the necessary steps, you'd better re-enable SIP as soon as possible to protect your Mac from virus attacks and malware infections.

Shut down your Mac and restart it in macOS Recovery Mode.
Click "Utilities" on the top menu bar and launch "Terminal".
Enter the disable command csrutil disable in the Terminal.
Press Return or Enter on your keyboard.
Then click the Apple menu and select Restart.
Open the Terminal application and run the previous command.

Starting a Mac computer with an Intel processor in Recovery Mode (Mac OS Recovery Mode)

Follow these steps to start your Mac with an Intel processor in recovery mode:

Turn off your Mac completely, and then press the power button or the Touch ID button to turn on your Mac.
Hold down the Command + R keys at the same time as soon as the Mac starts up or you hear the startup beep.
Mac recovery mode keys
Keep holding the keys for a few seconds until you see the Apple logo and release the keys to start the Mac in the recovery partition.
You successfully boot into macOS Recovery until you see a utilities window with several recovery and troubleshooting features.



# RUSSIAN

При возникновении ошибки "Operation not permitted"

MacOSX Mojave, Catalina, Big Sur, Monterey.


Включить полный доступ к диску для терминала

Нажмите на логотип Apple и выберите «Системные настройки».
В новом окне найдите и откройте Безопасность и конфиденциальность.
Выберите вкладку «Конфиденциальность», найдите «Полный доступ к диску» на левой боковой панели.
Нажмите на замок в левом углу и используйте Touch ID или пароль, чтобы разблокировать его.
Если Терминал отображается на левой панели, но отмечен флажком, установите его флажок. Выберите «Выйти и снова открыть», чтобы предоставить Терминалу полный доступ к диску.
Если нет, щелкните значок + на правой панели и найдите «Терминал» в приложениях, нажмите «Открыть».
Затем Терминал появится в списке разрешенных приложений с установленным флажком.
Запустите Терминал и введите ту же команду, которая вызывает ошибку «Операция не разрешена», чтобы увидеть, работает ли она сейчас.



MacOSX High Sierra


Временно отключить защиту целостности системы

Сообщение "Operation not permitted" по-прежнему появляется после включения полного разрешения на доступ к диску для терминала? Затем вы можете временно отключить защиту целостности системы на своем Mac. Разработчикам необходимо отключить SIP для тестирования кода, отладки приложений и установки системных расширений на Mac. После того, как вы выполните необходимые действия, вам лучше как можно скорее повторно включить SIP, чтобы защитить Mac от вирусных атак и заражения вредоносным ПО.

Выключите свой Mac и перезагрузите его в режиме восстановления macOS.
Нажмите «Утилиты» в верхней строке меню и запустите «Terminal».
Введите команду отключения csrutil disable в Терминале.
Нажмите Return или Enter на клавиатуре.
Затем щелкните меню Apple и выберите «Перезагрузить».
Откройте приложение «Terminal» и выполните предыдущую команду.

Запуск компьютер Mac с процессором Intel в режиме восстановления(Mac OS Recovery Mode)

Выполните следующие действия, чтобы запустить компьютер Mac с процессором Intel в режиме восстановления:

Полностью выключите Mac, а затем нажмите кнопку питания или кнопку Touch ID, чтобы включить Mac.
Удерживайте одновременно клавиши Command + R, как только Mac запустится или вы услышите звуковой сигнал запуска.
Клавиши режима восстановления Mac
Продолжайте удерживать клавиши в течение нескольких секунд, пока не увидите логотип Apple, и отпустите клавиши, чтобы запустить Mac в разделе восстановления.
Вы успешно загружаетесь в MacOS Recovery, пока не увидите окно утилит с несколькими функциями восстановления и устранения неполадок.
