***Выполнено ДЗ без звёздочек***

	собрана тестовая инфраструктура
	Установлено ПО
	Клонирован репозиторий из ДЗ и запущена VM
	Обновлено ядро и загрузчик
	С помощью  Packer собран образ системы
		*centos 7.7 на яндексе теперь отсутствует, а на vault.centos.org SHA не совпадает. Сборка выполнена на версии 7.8
	Произведён импорт образа и его тестирование
	Образ загружен в облако вагрант. https://app.vagrantup.com/NickVG/boxes/centos-7-5/
	Обновил версию: не работало монитроание папки в /vagrant/ и не обновлялся загрузчик(пофиксил выполнив на хосте "vagrant plugin install vagrant-vbguest"). Теперь актуальная версия 2.0
	
	
