# fstab-my-patent-1-device-1--proprietary-speed-system-linux
fstab proprietary 1 device 1€

Super speed ssd hdd flash cd

Griggorii@gmail.com

Example /etc/fstab 

UUID= ( My disk number adress) /               ext4    errors=remount-ro 0       1

/swap    sw              0       0

UUID= ( My disk number adress) /               ext4    errors=remount-ro 0       1

/swap    sw              0       0

UUID= ( My disk number adress) /               ext4    errors=remount-ro 0       1

/swap    sw              0       0


Или 

/boot/efi/efi.kernel

/swap    sw              0       0

/boot/efi/efi.kernel

/swap1    sw              0       0

/boot/efi/efi.kernel

/swap2    sw              0       0

..............

efi.kernel как пример может иметь другое название созданного ядра и после /swap    sw              0       0 иногда может идти строка вида моё устройство

f5ffff-фирма производитель

Пока пример без всякого устройства флешки вот https://github.com/Griggorii/fstab-my-patent-1-device-1--proprietary-speed-system-linux/blob/master/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202019-03-20%2018-50-18.png

Свапы создаются в терминале от рута примерно так ну и где за место 812 можно поставить сколько хотите и за место имени swapfile можно использовать любое другое имя или вообще устройство 

&&fallocate -l 812M /swapfile

&&chmod 600 /swapfile

&&mkswap /swapfile

&&swapon /swapfile

Потом редактируется /etc/fstab исходя из имён созданных свапов


После этого надо будет сделать update-initramfs -u -v && update-initramfs -u && update-grub

Можно дублировать это до бесконечности указывая тот же uuid  и скорость будет всё выше и выше вот такой вот с виду бутерброд это
скорость которая еще не дана земному шару 

И это будет на одном свопе , но можно сделать и /swap2 и /swap3 итд так же сапом может быть и устройство которе будет иметь другой адрес типа t5uk-superpuperfleshmegaboostspeed и более цифр или же же иметь адрес uuid

С этой лицензии деньги будут идти на разработку моей OS которая соответственно уже быстрее всех в мире осей за счет этой 

технологии , повторять технологию запрещено она запатентована здесь до выпуска моей оси

Пишете если вы создавали свап с какой либо файловой системой fat32 ext ntfs и другие fs на какой у вас стала скорость более высокой

Когда наберется на создание операционной системы достаточно денег то технология станет бесплатной для гугла , яндекса и других крупных комьюнити которые тоже делают оси

Игроки разработчики уже могут уже опробовать эту технологию на созданных ими играх , но учитывая лицензию

Естественно пока не известно как поведет себя fstab если будет меняться ядро или оборудование или обновление с релиза на релиз , так что в некотором варианте надо будет приводить систему в дифолт , а после всех обновлений с релиза на релиз делать все заново

Теперь я думаю понятно что это не просто я там написал в уши в глаза залил и хочу распилить как спо и гноме фундатион, а то что я не стоял там с графиками рассказывая не понятную хрень и собираюсь не за что получить деньги на разработку , а всё расписал как я понял и думаю кто прочтет тот поймёт что это сверх новая открытая мною технология ускорения
кто недалек
