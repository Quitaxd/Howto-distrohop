# Distro nasıl atlanır?


## Öncelikle bize gerekenler;

* USB

* Bir Bilgisayar

* Bilgi

## İndirme İşlemi

* Dağıtımları belli sitelerden indiririz. Bazı dağıtımların indirme siteleri; (Dağıtıma tıklayınca indirme sitesine erişeceksiniz. Eğer listede o dağıtım yoksa Google' a yazabilirsiniz.)

[Ubuntu](https://ubuntu.com/download/desktop)

[Linux Mint](https://linuxmint.com)

[EndeavourOS](https://endeavouros.com)

## USB' ye ISO yazdırma;

* Öncekikle;

lsblk yazalım ve usbmizi bulalım. Bulunca başındaki kodu kopyalayın.

* Sonra şunu yazalım;

$ sudo dd if=archlinux-2017.iso of=/dev/ status=progress

* /dev/ dan sonra oraya usb kodunu yapıştıralım. Sonra if= yazan kısımda iso' nun yolunu gösterelim. Sonra enter tuşuna basıp bekleyelim. Sonra komut bitince diğer adıma geçelim.

## Kurulum

* Sonra bekleyin ve sistemi USB ile boot edin. Nasıl yapılacağına internetten bakabilirsiniz.

* Daha sonra kurulum talimatlarını gerçekleştirin ve oldu! Artık distro değiştirdiniz.
