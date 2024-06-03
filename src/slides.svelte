<script lang="ts">
	import { Presentation, Slide, Step, Vertical } from '@components'
	
</script>

<Presentation>
	<Slide animate>
		<div class="h-[75vh]">
			<div class="flex justify-center h-[45vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
			<h1 class="font-bold text-6xl">Niusbuk</h1>
			<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
			<p class="text-lg absolute bottom-4 left-[40%]">&copy; Rafel Camps 2024</p>
		</div>
	</Slide>

	<Slide animate >
		<div class="flex justify-between">
			<div class="h-[75vh] w-1/2">
				<div class="flex justify-center h-[45vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
				<h1 class="font-bold text-6xl">Niusbuk</h1>
				<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
				<p class="text-lg absolute bottom-4 left-[15%]">&copy; Rafel Camps 2024</p>
			</div>
			<div class="w-1/2 px-10">
				<Step fadeDown><h2 class="text-emerald-600 text-6xl mb-5  px-10 w-full text-left">Índex</h2></Step>
				<div class="">
					<Step fadeUp><li class="mb-2 text-2xl text-left">Qué és Niusbuk?</li></Step>
					<Step fadeRight><li class="mb-2 text-2xl text-left">Problema i solució</li></Step>
					<Step fadeRight><li class="mb-2 text-2xl text-left">Funcionalitats Clau</li></Step>
					<Step fadeRight><li class="mb-2 text-2xl text-left">Tecnologies utilitzades</li></Step>
					<Step fadeRight><li class="mb-2 text-2xl text-left">Disseny de la interfície</li></Step>
					<Step fadeRight><li class="mb-2 text-2xl text-left">Casos d'Ús</li></Step>
					<Step fadeRight><li class="mb-2 text-2xl text-left">Seguretat i Autenticació</li></Step>
					<Step fadeRight><li class="mb-2 text-2xl text-left">Desplegament</li></Step>
					<Step fadeRight><li class="mb-2 text-2xl text-left">Beneficis per a l'Hotel</li></Step>
					<Step fadeRight><li class="mb-2 text-2xl text-left">Millores Futures</li></Step>
					<Step fadeRight><li class="mb-2 text-2xl text-left">Conclusió</li></Step>
					<Step fadeRight><li class="mb-2 text-2xl text-left">Preguntes i Respostes</li></Step>
				</div>
			</div>
		</div>
	</Slide>

	<Slide animate >
		<div class="flex justify-between">
			
			<div class="flex flex-col justify-center  w-1/2">
				<Step fadeDown><h2 class="text-emerald-600 text-6xl mb-5 w-full ">Qué és Niusbuk?</h2></Step>
				<div class="w-full">
					<Step fadeUp><li class="mb-3 text-2xl">Es un llibre de torn digital per les recepcións dels hotels</li></Step>
					<Step fadeUp><li class="mb-3 text-2xl">Es un registre de objectes perduts a un hotel</li></Step>
				</div>
			</div>
			<div class="h-[70vh] w-1/2">
				<div class="flex justify-center h-[40vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
				<h1 class="font-bold text-6xl">Niusbuk</h1>
				<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
				<p class="text-lg absolute bottom-4 left-[45%]">&copy; Rafel Camps 2024</p>
			</div>
		</div>
	</Slide>


	<Slide animate >
		<div class="w-[vw] ">
			<div class="flex w-full">
				<div class="flex justify-center h-[15vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
				<div class="ml-4 mt-6">
					<h1 class="font-bold text-6xl">Niusbuk</h1>
					<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
				</div>
			</div>
			<div class="flex mt-5">
				<div class="w-1/2">
					<Step fadeDown><h2 class="text-emerald-600 text-5xl mb-5 w-full ">Problema</h2></Step>
					<div class="w-full">
						<Step fadeLeft><li class="mb-3 text-2xl text-left">Actualment s'utilitzen fulls de càlcul o inclós dietaris de paper</li></Step>
						<Step fadeLeft><li class="mb-3 text-2xl text-left">Perdua de informació</li></Step>
						<Step fadeLeft><li class="mb-3 text-2xl text-left">Difícil actualització i seguiment</li></Step>
						<Step fadeLeft><li class="mb-3 text-2xl text-left">Baixa la qualitat del servei</li></Step>
					</div>
				</div>
				<div class="flex flex-col justify-center  w-1/2 pl-6">
					<Step fadeDown><h2 class="text-emerald-600 text-5xl mb-5 w-full ">Solució</h2></Step>
					<div class="w-full">
						
						<Step fadeRight><li class="mb-3 text-2xl text-left">Enregistrar les incidencies en un format digital</li></Step>
						<Step fadeRight><li class="mb-3 text-2xl text-left">Accesible desde cualsevol terminal amb internet</li></Step>
						<Step fadeRight><li class="mb-3 text-2xl text-left">Actualitzacions de les dades instantànea</li></Step>
				
					</div>
				</div>
			</div>
			
		
		</div>
	</Slide>
	<Slide animate >
		<div class="flex justify-between">
			
			<div class="flex flex-col justify-center  w-1/2">
				<h2 class="text-emerald-600 text-5xl mb-5 w-full mb-10">Funcionalitats Clau</h2>
				<div class="w-full">
					<Step fadeUp><li class="mb-3 text-2xl text-left">Crear incidències segons categories </li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left">Actualitzar l'estat de les mateixes </li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left">Filtrar incidències per categories  </li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left">Cercar per text </li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left">Marcar com a completades </li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left">Crear registre d'objectes perduts </li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left">Actualitzar l'estat de l'objecte, mantenint la cadena de custòdia del mateix </li></Step>
				</div>
			</div>
			<div class="h-[70vh] w-1/2">
				<div class="flex justify-center h-[40vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
				<h1 class="font-bold text-6xl">Niusbuk</h1>
				<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
				<p class="text-lg absolute bottom-4 left-[45%]">&copy; Rafel Camps 2024</p>
			</div>
		</div>
	</Slide>
	<Slide animate >
		<div class="flex justify-between">
			<div class="h-[70vh] w-1/2">
				<div class="flex justify-center h-[40vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
				<h1 class="font-bold text-6xl">Niusbuk</h1>
				<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
				<p class="text-lg absolute bottom-4 left-[45%]">&copy; Rafel Camps 2024</p>
			</div>
			<div class="flex flex-col justify-center  w-1/2">
				<h2 class="text-emerald-600 text-5xl mb-10 w-full ">Tecnologies utilitzades</h2>
				<div class="w-full">
					<Step fadeUp><li class="mb-3 text-2xl text-left"><span class="text-emerald-600 font-semibold mr-5">FrontEnd</span> SvelteKit, TailwindCSS</li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left"><span class="text-emerald-600 font-semibold mr-5">Backend</span> Laravel</li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left"><span class="text-emerald-600 font-semibold mr-5">Base de dades</span> Postgresql</li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left"><span class="text-emerald-600 font-semibold mr-5">Contenidors</span> Docker</li></Step>
				</div>
			</div>
			
		</div>
	</Slide>
	<Vertical>
		<Slide animate >
			<div class="flex justify-between">
				
				<div class="flex flex-col justify-center  w-1/2">
					<h2 class="text-emerald-600 text-6xl mb-5 w-full ">Disseny de la interfície</h2>
					<div class="w-full">
						
		
	
					</div>
				</div>
				<div class="h-[70vh] w-1/2">
					<div class="flex justify-center h-[40vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
					<h1 class="font-bold text-6xl">Niusbuk</h1>
					<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
					<p class="text-lg absolute bottom-4 left-[45%]">&copy; Rafel Camps 2024</p>
				</div>
			</div>
		</Slide>
		<Slide animate >
			<div class="flex justify-between">
				
				<div>
					<div class="flex">
						<div class="flex justify-center h-[15vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
						<div class="ml-4 mt-6">
							<h1 class="font-bold text-6xl">Niusbuk</h1>
							<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
						</div>
					</div>
					<div>
						<img src="https://www.niusbuk.com/img/interfaces/Book.png" alt="llistat incidències">
					</div>
				</div>

				<div class="flex flex-col justify-center  w-1/2">
					<h2 class="text-emerald-600 text-5xl mb-5 w-full ">Llistat d'incidències</h2>
					<div class="w-full">
						
						<Step fadeUp><li class="mb-3 text-2xl">Incidencies amb un color diferent per cada tipus de categoria</li></Step>
						<Step fadeRight><li class="mb-3 text-2xl">Hora i data de creació</li></Step>
						<Step fadeUp><li class="mb-3 text-2xl">Usuari que l'ha creat</li></Step>
						<Step fadeUp><li class="mb-3 text-2xl">Prioritat</li></Step>
						<Step fadeUp><li class="mb-3 text-2xl">Botò d'estat</li></Step>
						<Step fadeUp><li class="mb-3 text-2xl">Botó per la creació d'incidències</li></Step>
				
					</div>
				</div>
				
			</div>
		</Slide>
		<Slide animate >
			<div class="flex justify-between">
				
				<div class="flex flex-col justify-center  w-1/2">
					<h2 class="text-emerald-600 text-5xl mb-5 w-full ">Llistat d'objectes perduts</h2>
					<div class="w-full">
						<Step fadeUp><li class="mb-3 text-2xl">Objectes amb un color diferent per cada tipus de categoria</li></Step>
						<Step fadeRight><li class="mb-3 text-2xl">Data de creació</li></Step>
						<Step fadeUp><li class="mb-3 text-2xl">Usuari que l'ha creat</li></Step>
						<Step fadeUp><li class="mb-3 text-2xl">Estat del objecte</li></Step>
						<Step fadeUp><li class="mb-3 text-2xl">Botò per canviar d'estat</li></Step>
						<Step fadeUp><li class="mb-3 text-2xl">Botó per la creació d'objectes perduts</li></Step>
					</div>
				</div>
				<div>
					<div class="flex">
						<div class="flex justify-center h-[15vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
						<div class="ml-4 mt-6">
							<h1 class="font-bold text-6xl">Niusbuk</h1>
							<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
						</div>
					</div>
					<div>
						<img src="https://www.niusbuk.com/img/interfaces/Items.png" alt="llistat objectes perduts">
					</div>
				</div>
				
			</div>
		</Slide>
		<Slide animate >
			<div class="flex justify-between">
				
				<div>
					<div class="flex">
						<div class="flex justify-center h-[15vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
						<div class="ml-4 mt-6">
							<h1 class="font-bold text-6xl">Niusbuk</h1>
							<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
						</div>
					</div>
					<div>
						<img src="https://www.niusbuk.com/img/interfaces/Users.png" alt="llistat usuaris">
					</div>
				</div>

				<div class="flex flex-col justify-center  w-1/2">
					<h2 class="text-emerald-600 text-6xl mb-5 w-full ">Llistat d'usuaris</h2>
					<div class="w-full">
						
						<Step fadeUp><li class="mb-3 text-2xl">Estatus de l'usuari ( actiu / inactiu )</li></Step>
						<Step fadeRight><li class="mb-3 text-2xl">Email de l'usuari</li></Step>
						<Step fadeUp><li class="mb-3 text-2xl">Rol de l'usuari</li></Step>
						<Step fadeUp><li class="mb-3 text-2xl">Botó per la creació d'usuaris</li></Step>
						
	
					</div>
				</div>
				
			</div>
		</Slide>
	</Vertical>

	<Slide animate >
		<div class="flex justify-between">
			
			<div class="flex flex-col justify-center  w-1/2">
				<h2 class="text-emerald-600 text-5xl mb-5 w-full ">Casos d'Ús</h2>
				<div class="w-full">
					
					<Step fadeRight><li class="mb-3 text-2xl text-left">Inici de sesió</li></Step>
					<Step fadeRight><li class="mb-3 text-2xl text-left">Creació d'usuaris</li></Step>
					<Step fadeRight><li class="mb-3 text-2xl text-left">Crear y actualitzar incièncias</li></Step>
					<Step fadeRight><li class="mb-3 text-2xl text-left">Filtrar y cercar incidèncias</li></Step>
					<Step fadeRight><li class="mb-3 text-2xl text-left">Marcar incidèncias como resoltas</li></Step>
					<Step fadeRight><li class="mb-3 text-2xl text-left">Crear y actualitzar objectes perduts</li></Step>
					<Step fadeRight><li class="mb-3 text-2xl text-left">Filtrar y cercar objectes perduts</li></Step>
								
				</div>
			</div>
			<div class="h-[70vh] w-1/2">
				<div class="flex justify-center h-[40vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
				<h1 class="font-bold text-6xl">Niusbuk</h1>
				<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
				<p class="text-lg absolute bottom-4 left-[45%]">&copy; Rafel Camps 2024</p>
			</div>
		</div>
	</Slide>
	<Slide animate >
		<div class="flex justify-between">
			<div class="h-[70vh] w-1/2">
				<div class="flex justify-center h-[40vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
				<h1 class="font-bold text-6xl">Niusbuk</h1>
				<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
				<p class="text-lg absolute bottom-4 left-[45%]">&copy; Rafel Camps 2024</p>
			</div>

			<div class="flex flex-col justify-center  w-1/2">
				<h2 class="text-emerald-600 text-5xl mb-10 w-full ">Seguretat i Autenticació</h2>
				<div class="w-full">
					
					<Step fadeUp><li class="mb-3 text-2xl text-left">Llibreria Laravel Sanctum</li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left">Autentificació mitjançant API Token</li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left">Protecció CSRF (Cross-Site Request Forgery) </li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left">Protecció davant un nombre màxim d'intents de login</li></Step>

				</div>
			</div>
			
		</div>
	</Slide>
	<Slide animate >
		<div class="flex justify-between">
			
			<div class="flex flex-col justify-center  w-1/2">
				<h2 class="text-emerald-600 text-5xl mb-10 w-full ">Desplegament</h2>
				<div class="w-full">

					<Step fadeLeft><li class="mb-3 text-2xl">Desplegament a un entron cloud</li></Step>
					<Step fadeUp><li class="mb-3 text-2xl">Vercel (Frontend)</li></Step>
					<Step fadeRight><li class="mb-3 text-2xl">Hetzner (Backend)</li></Step>
					
				</div>
			</div>
			<div class="h-[70vh] w-1/2">
				<div class="flex justify-center h-[40vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
				<h1 class="font-bold text-6xl">Niusbuk</h1>
				<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
				<p class="text-lg absolute bottom-4 left-[45%]">&copy; Rafel Camps 2024</p>
			</div>
		</div>
	</Slide>
	<Slide animate >
		<div class="flex justify-between">
			<div class="h-[70vh] w-1/2">
				<div class="flex justify-center h-[40vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
				<h1 class="font-bold text-6xl">Niusbuk</h1>
				<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
				<p class="text-lg absolute bottom-4 left-[45%]">&copy; Rafel Camps 2024</p>
			</div>
			<div class="flex flex-col justify-center  w-1/2">
				<h2 class="text-emerald-600 text-5xl mb-5 w-full ">Beneficis per a l'Hotel</h2>
				<div class="w-full">
					
					<Step fadeUp><li class="mb-3 text-2xl text-left">Eficiencia Operativa: Reducció d'errors en la gestió d'incidències</li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left">Millora el seguiment i actualització d'incidències</li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left">Millora de la Comunicació interna</li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left">Accés Fàcil a Històrics</li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left">Crear un registre de traçabilitat pels objectes trovats a dins l'hotel</li></Step>

				</div>
			</div>
			
		</div>
	</Slide>
	<Slide animate >
		<div class="flex justify-between">
			
			<div class="flex flex-col justify-center  w-1/2">
				<Step fadeDown><h2 class="text-emerald-600 text-5xl mb-5 w-full ">Millores Futures</h2></Step>
				<div class="w-full">
					
					<Step fadeLeft><li class="mb-3 text-2xl">Creació d'incidències amb notes de veu</li></Step>
					<Step fadeLeft><li class="mb-3 text-2xl">Funcionalitats avançades de reportació</li></Step>
					<Step fadeUp><li class="mb-3 text-2xl">Integració amb sistemes de gestió hotelera</li></Step>
					<Step fadeUp><li class="mb-3 text-2xl">Aplicació mòbil per a un accés més fàcil</li></Step>

				</div>
			</div>
			<div class="h-[70vh] w-1/2">
				<div class="flex justify-center h-[40vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
				<h1 class="font-bold text-6xl">Niusbuk</h1>
				<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
				<p class="text-lg absolute bottom-4 left-[45%]">&copy; Rafel Camps 2024</p>
			</div>
		</div>
	</Slide>
	<Slide animate >
		<div class="flex justify-between">
			<div class="h-[70vh] w-1/2">
				<div class="flex justify-center h-[40vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
				<h1 class="font-bold text-6xl">Niusbuk</h1>
				<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
				<p class="text-lg absolute bottom-4 left-[45%]">&copy; Rafel Camps 2024</p>
			</div>
			<div class="flex flex-col justify-center  w-1/2">
				<Step fadeDown><h2 class="text-emerald-600 text-5xl mb-5 w-full ">Conclusió</h2></Step>
				<div class="w-full">
					
					<Step fadeUp><li class="mb-3 text-2xl text-left">La aplicació digitalitza i optimitza la gestió d'incidències al hotel.</li></Step>
					<Step fadeUp><li class="mb-3 text-2xl text-left">Beneficis clars en termes d'eficiència, comunicació i gestió de dades.</li></Step>
					
				</div>
			</div>
			
		</div>
	</Slide>
	<Slide animate >
		<div class="flex justify-between">
			
			<div class="flex flex-col justify-center  w-1/2">
				<Step fadeDown><h2 class="text-emerald-600 text-5xl mb-5 w-full ">Preguntes i Respostes</h2></Step>
			
			</div>
			<div class="h-[70vh] w-1/2">
				<div class="flex justify-center h-[40vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
				<h1 class="font-bold text-6xl">Niusbuk</h1>
				<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
				<p class="text-lg absolute bottom-4 left-[45%]">&copy; Rafel Camps 2024</p>
			</div>
		</div>
	</Slide>
	<Slide animate>
		<div class="h-[70vh]">
			<div class="flex justify-center h-[35vh]"><img src="https://www.niusbuk.com/niusbuk_logo.png" alt="Logo niusbuk"></div>
			<h1 class="font-bold text-6xl">Niusbuk</h1>
			<h2 class="text-2xl">Comunicació hotelera 2.0</h2>
			<h2 class="text-5xl my-7 text-emerald-500">Moltes gràcies</h2>
			<h2 class="text-3xl">Anem a veure l'aplicació en funcionament!!</h2>
			<p class="text-lg absolute bottom-4 left-[45%]">&copy; Rafel Camps 2024</p>
		</div>
	</Slide>
	
</Presentation>
