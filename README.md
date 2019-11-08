1. Установите [Termux](https://play.google.com/store/apps/details?id=com.termux&hl=ru)
2. Введите следующие команды поочерёдно для установки необходимых компонентов:
    pkg install update
	pkg install python
    pkg install git
	git clone https://github.com/flexholy/smsbomb
	cd smsbomb
	python -m pip install -r requirements.txt
	python main.py
	После этого вам в консоль напишет айпи которое надо будет вставить в браузер

