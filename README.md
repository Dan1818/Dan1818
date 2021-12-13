while True:
	#<head>
	import colorama
	from colorama import Fore, Back, Style
	colorama.init()
	print(Fore.GREEN)
	#</head>




	#<body>
	cam1 =input('введите первое число : ')
	cam2 =input('введите второе число : ')
	camn =input('введите действие: ')



	if camn == "+":
		a = float(cam1) + float(cam2)

		print(Back.BLUE +"Ответ: ",a)
	elif camn == "-":
		a = float(cam1) - float(cam2)

		print(Back.BLUE +"Ответ: ",a)
	elif camn == "*":
		a = float(cam1) * float(cam2)

		print(Back.BLUE +"Ответ: ",a)
	elif camn == "/":
		a = float(cam1) / float(cam2)
		print(Back.BLUE +"Ответ: ",a) 
	elif camn == ":":
		a = float(cam1) / float(cam2)
		print(Back.BLUE +"Ответ: ",a) 


	else:
		print(Fore.RED)
		print(Back.WHITE)
		print("\nВозникла ошибка.\nВы что то попутали наверное")
	print(Style.RESET_ALL)
	continue
	#</body>



aimp = input()
