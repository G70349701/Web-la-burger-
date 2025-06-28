<!DOCTYPE html>
    <html lang="es">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>La Burger - Surquillo, Lima</title>
        <!-- Tailwind CSS CDN -->
        <script src="https://cdn.tailwindcss.com"></script>
        <!-- Google Fonts - Inter -->
        <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
        <style>
            body {
                font-family: 'Inter', sans-serif;
                background-color: #f8f8f8; /* Light background */
            }
        </style>
    </head>
    <body class="flex flex-col min-h-screen text-gray-800">
        <!-- Header -->
        <header class="bg-red-700 text-white p-4 shadow-lg rounded-b-lg">
            <div class="container mx-auto text-center">
                <h1 class="text-4xl md:text-5xl font-extrabold mb-2">La Burger</h1>
                <p class="text-xl md:text-2xl font-light">¡Las mejores hamburguesas de Surquillo!</p>
            </div>
        </header>

        <!-- Main Content -->
        <main class="flex-grow container mx-auto p-4 md:p-8">
            <div class="bg-white rounded-xl shadow-lg p-6 mb-8 border border-gray-200">
                <h2 class="text-2xl md:text-3xl font-bold text-red-600 mb-4 text-center">Encuéntranos</h2>
                <div class="text-lg text-center mb-6">
                    <p class="mb-2"><strong>Dirección:</strong> Av Principal 501, Surquillo, Lima</p>
                </div>

                <!-- Google Maps Link -->
                <div class="flex justify-center mb-6">
                    <a href="https://www.google.com/maps/search/?api=1&query=La+Burger+Av+Principal+501+Surquillo+Lima"
                       target="_blank"
                       rel="noopener noreferrer"
                       class="inline-flex items-center px-6 py-3 bg-blue-600 text-white font-semibold rounded-lg shadow-md hover:bg-blue-700 transition duration-300 transform hover:scale-105">
                        <svg class="w-5 h-5 mr-2" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd"></path>
                        </svg>
                        Ver en Google Maps
                    </a>
                </div>

                <p class="text-center text-gray-600 text-sm italic">Haz clic para ver nuestra ubicación exacta y obtener indicaciones.</p>
            </div>

            <!-- Section: Menú -->
            <div class="bg-white rounded-xl shadow-lg p-6 mb-8 border border-gray-200">
                <h2 class="text-2xl md:text-3xl font-bold text-red-600 mb-6 text-center">Nuestro Menú</h2>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 text-gray-700">
                    <!-- Hamburguesas -->
                    <div>
                        <h3 class="text-xl md:text-2xl font-bold text-red-500 mb-3 border-b-2 border-red-300 pb-1">Hamburguesas</h3>
                        <ul class="space-y-3">
                            <li>
                                <p class="font-semibold">Burger Caramel <span class="float-right">S/16.90</span></p>
                                <p class="text-sm">Pan brioche, carne 130 gr, cebolla caramelizada, queso cheddar, papas al hilo y vegetales.</p>
                            </li>
                            <li>
                                <p class="font-semibold">Burger Hawaiana <span class="float-right">S/17.90</span></p>
                                <p class="text-sm">Pan brioche, carne 130 gr, piña, queso, jamón, papas al hilo y vegetales.</p>
                            </li>
                            <li>
                                <p class="font-semibold">Burger Bacon <span class="float-right">S/16.90</span></p>
                                <p class="text-sm">Pan brioche, carne 130 gr con tocino, papas al hilo y vegetales.</p>
                            </li>
                            <li>
                                <p class="font-semibold">Burger Cheese <span class="float-right">S/15.90</span></p>
                                <p class="text-sm">Pan brioche, carne 130 gr, queso cheddar, papas al hilo y vegetales.</p>
                            </li>
                            <li>
                                <p class="font-semibold">Burger Royal <span class="float-right">S/15.90</span></p>
                                <p class="text-sm">Pan brioche, carne 130 gr con huevo, papas al hilo y vegetales.</p>
                            </li>
                            <li>
                                <p class="font-semibold">Burger Deluxe <span class="float-right">S/19.90</span></p>
                                <p class="text-sm">Pan brioche, carne 130 gr + 4 toppings (a elección), papas al hilo y vegetales. (No incluye toppings con *)</p>
                            </li>
                            <li>
                                <p class="font-semibold">Burger A Lo Pobre <span class="float-right">S/17.90</span></p>
                                <p class="text-sm">Pan brioche, carne 130 gr con plátano frito, huevo, papas al hilo y vegetales.</p>
                            </li>
                            <li>
                                <p class="font-semibold">Burger Doble <span class="float-right">S/18.90</span></p>
                                <p class="text-sm">Pan brioche, 2 carnes de 130 gr, papas al hilo y vegetales.</p>
                            </li>
                            <li>
                                <p class="font-semibold">Burger Clásica <span class="float-right">S/14.90</span></p>
                                <p class="text-sm">Pan brioche, carne de 130 gr, papas al hilo y vegetales.</p>
                            </li>
                            <li>
                                <p class="font-semibold">Burger Argentina <span class="float-right">S/18.90</span></p>
                                <p class="text-sm">Pan brioche, carne 130 gr, chorizo, papas al hilo y vegetales.</p>
                            </li>
                        </ul>
                    </div>

                    <!-- Toppings y Extras -->
                    <div>
                        <h3 class="text-xl md:text-2xl font-bold text-red-500 mb-3 border-b-2 border-red-300 pb-1">Toppings y Extras</h3>
                        <ul class="space-y-2 mb-4">
                            <li>Cebolla Caramelizada <span class="float-right">S/2.50</span></li>
                            <li>Huevo <span class="float-right">S/2.50</span></li>
                            <li>Jamón <span class="float-right">S/2.50</span></li>
                            <li>Piña <span class="float-right">S/2.50</span></li>
                            <li>Plátano <span class="float-right">S/2.50</span></li>
                            <li>Queso Cheddar <span class="float-right">S/2.50</span></li>
                            <li>Tocino <span class="float-right">S/3.00</span></li>
                            <li>Filete de Pollo* <span class="float-right">S/4.50</span></li>
                            <li>Frankfurter* <span class="float-right">S/4.50</span></li>
                            <li>Chorizo* <span class="float-right">S/4.50</span></li>
                            <li>Carne* <span class="float-right">S/5.50</span></li>
                        </ul>
                        <p class="text-sm italic mb-4">CREMAS: Mayonesa, Ketchup, Ají, Mostaza, Tártara, Golf y Aceituna.</p>

                        <h3 class="text-xl md:text-2xl font-bold text-red-500 mb-3 border-b-2 border-red-300 pb-1">Promociones</h3>
                        <p class="font-semibold mb-2">PAPA O CAMOTE FRITO + BEBIDA</p>
                        <p class="text-sm">Pepsi, Coca Cola, 7UP o agua. S/1.00 Coca Cola o Inca Kola.</p>

                        <h3 class="text-xl md:text-2xl font-bold text-red-500 mb-3 border-b-2 border-red-300 pb-1">Salchipapas</h3>
                        <ul class="space-y-3">
                            <li>
                                <p class="font-semibold">Salchipapas <span class="float-right">S/19.90</span></p>
                                <p class="text-sm">Salchipapa + 3 toppings a elección. (No incluye toppings con *)</p>
                            </li>
                            <li>
                                <p class="font-semibold">Salchi queso tocino <span class="float-right">S/18.90</span></p>
                                <p class="text-sm">Salchipapa con queso cheddar y tocino.</p>
                            </li>
                            <li>
                                <p class="font-semibold">Frankfurter <span class="float-right">S/15.90</span></p>
                                <p class="text-sm">Salchipapa con salchicha Frankfurter ahumada.</p>
                            </li>
                            <li>
                                <p class="font-semibold">Cheese <span class="float-right">S/16.90</span></p>
                                <p class="text-sm">Salchipapa + queso cheddar</p>
                            </li>
                        </ul>

                        <h3 class="text-xl md:text-2xl font-bold text-red-500 mb-3 border-b-2 border-red-300 pb-1">Sándwiches</h3>
                        <ul class="space-y-3">
                            <li>
                                <p class="font-semibold">Sándwich de pollo <span class="float-right">S/15.90</span></p>
                                <p class="text-sm">Pan brioche, filete de pollo a la parrilla, papas al hilo y vegetales.</p>
                            </li>
                            <li>
                                <p class="font-semibold">Churipan <span class="float-right">S/14.90</span></p>
                                <p class="text-sm">Pan brioche, chorizo a la parrilla, papas al hilo y vegetales.</p>
                            </li>
                        </ul>

                        <h3 class="text-xl md:text-2xl font-bold text-red-500 mb-3 border-b-2 border-red-300 pb-1">Bebidas</h3>
                        <ul class="space-y-2">
                            <li>Pepsi <span class="float-right">355 ml S/3</span></li>
                            <li>Conc. piña <span class="float-right">355 ml S/3</span></li>
                            <li>7UP <span class="float-right">355 ml S/3</span></li>
                            <li>Agua <span class="float-right">500 ml S/3</span></li>
                            <li>Inca Kola <span class="float-right">300 ml S/4</span></li>
                            <li>Coca Cola <span class="float-right">300 ml S/4</span></li>
                        </ul>
                    </div>
                </div>
                <div class="text-center text-gray-600 text-sm mt-8">
                    <p class="font-semibold">HORARIO:</p>
                    <p>LUNES A DOMINGO: 5:00 pm a 11:00 pm</p>
                    <p>@laburgeralcarbon</p>
                    <p>Av. Principal 501, Surquillo.</p>
                    <p>934 504 415</p>
                </div>
            </div>


            <!-- Section: Contacto with updated info -->
            <div class="bg-white rounded-xl shadow-lg p-6 mb-8 border border-gray-200">
                <h2 class="text-2xl md:text-3xl font-bold text-red-600 mb-4 text-center">Contáctanos</h2>
                <div class="text-lg text-center text-gray-700">
                    <p class="mb-2"><strong>Dirección:</strong> Av Principal 501, Surquillo, Lima</p>
                    <p class="mb-2"><strong>Teléfono:</strong> +51 934 504 415 (con WhatsApp)</p>
                    <p>¡Esperamos verte o escucharte pronto!</p>
                </div>
            </div>
        </main>

        <!-- Footer -->
        <footer class="bg-gray-800 text-white p-4 text-center rounded-t-lg">
            <p>&copy; 2025 La Burger. Todos los derechos reservados.</p>
            <p class="text-sm mt-2">Av Principal 501, Surquillo, Lima</p>
        </footer>
    </body>
    </html>
    ```
