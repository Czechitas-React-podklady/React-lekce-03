# Cvičení 1 - Aplikace

1. Ve své složce, kde si vytváříš projekty pro tento kurz, si pomocí `create-czechitas-app` vyrob nový projekt. Nazvi ho třeba `aplikace`.

1. Pomocí `npm run start` v terminálu zkus projekt spustit, abyses přesvědčila, že všechno správně funguje.

1. Vytvoř hlavní komponentu `App`, která nebude mít žádné `props`, ale později do ní umístíme ostatní komponenty. Tento úkol je jednoduchý, protože v projektu vytvořeném pomocí `create-czechitas-app` už komponenta `App` je a v podstatě ti stačí jenom vymazat její obsah.

	Naše aplikace bude obsahovat tři komponenty: `Header`, `Main` a `Footer`.

1. Vytvoř komponentu `Header`, která bude obsahovat kód pro hlavičku stránky, který by měl vypadat zhruba takto:

	```html
	<header>
		<h1>Titulek stránky</h1>
	</header>
	```

	Komponenta bude přijímat jednu jedinou prop nazvanou `title`, ve které které bude titulek stránky, který chceme doplnit místo textu v nadpisu `<h1>`.

1. Vytvoř komponentu `Main`, která bude mít obsah zhruba v této podobě:

	```html
	<main>
		<p>Text na stránce</p>
	</main>
	```

	Tato komponenta bude mít jednu prop s názvem `content`, ve které se do komponenty bude předávat obsah, který se doplní jako text odstavce.

1. Jako poslední vyrob komponentu `Footer`, jejíž obsah bude podobně jednoduchý, jako u předchozích komponent:

	```html
	<footer>
		&copy; 2021, Alenka Nováková
	</footer>
	```

	Komponenta bude mít dvě props s názvem `author` a `year`, ve které bude jméno autora a rok uvedený za copyrightem.

1. Nainmportuj a přidej všechny tři vytvořené komponenty do komponenty `App`, aby se v naší aplikaci na stránce zobrazila hlavička, hlavní obsah a patička pod sebou.

1. Ověř si, že se všechny `props` správně propsaly do jednotlivých komponent.

1. Pokud máš čas a chuť, vyrob jednoduché CSS, aby aplikace lépe vypadala. Nezapomeň CSS naimportovat do stránky do stránky.
