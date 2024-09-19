<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/toastify-js/src/toastify.min.css"/>

    <link rel="preconnect" href="https://fonts.googleapis.com"/>
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin/>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,400;0,500;0,700;1,400&display=swap" 
    rel="stylesheet"/>
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" 
    integrity="sha512-Fo3rlrZj/k7ujTnHg4CGR2D7kSs0v4LLanw2qksYuRlEzO+tcaEPQogQ0KaoGN26/zrn20ImR1DfuLWnOo7aBA==" 
    crossorigin="anonymous" referrerpolicy="no-referrer" />

    <meta property="og:type" content="website"/>
    <meta property="og:title" content="Hamburgueria"/>
    <meta property="og:image" content=""/>
    <meta property="og:description" content="O melhor hamburger caseiro"/>
    <meta property="og:site_name" content="Hamburgueria"/>

    <link rel="stylesheet" href="C:\Users\GEAN\Desktop\html\styles\output.css"/>

    <title>Hamburgueria</title>
</head>
<body>
    
    <header class="w-full h-[420px] bg-zinc-900 bg-home bg-cover bg-center">
        <div class="w-full h-full flex flex-col justify-center items-center">
            <img
              src="C:\Users\GEAN\Desktop\html\assets\hamb-1.png"
              alt="Logo Hamburgueria"
              class="w-32 h-32 rounded-full shadow-lg hover:scale-110 duration-200"             
            />
            <h1 class="text-4xl mt-4 mb-2 font-bold text-white">Hamburgueria</h1>
            
            <span class="text-white font-medium">Rua XXX N°, Cidade - XX</span>

            <div class="bg-green-600 px-4 py-1 rounded-lg mt-5 " id="date-span">
                <span class="text-white font-medium">Seg a Dom - 18:00 as 22:00</span>
            </div>

        </div>
    </header>

    <h2 class="text-2xl md:text-3xl font-bold text-center mt-9 mb-6">
        Conheça nosso menu
    </h2>

    <div id="menu">

        <main class="grid grid-cols-1 md:grid-cols-2 gap-7 md:gap-10 mx-auto max-w-7xl px-2 mb-16">

            <div class="flex gap-2">
                <img
                  src="C:\Users\GEAN\Desktop\html\assets\hamb-1.png"
                  alt="Hamburger Smash"
                  class="w-28 h-28 rounded-md hover:scale-110 hover:-rotate-2 duration-300"
                />

                <div>
                    <p class="font-bold">Hamburger Smash</p>
                    <p class="text-sm">Pão levinho de fermentação natural da Trigou, 
                        burger 160g, queijo pratoe maionese da casa.</p>

                    <div class="flex items-center gap-2 justify-between mt-3">
                        <p class="font-bold text-lg">R$ 18.90</p>
                        <button 
                            class="bg-gray-900 px-5 rounded add-to-cart-btn"
                            data-name="Hamburger Smash"
                            data-price="18.90"
                        >
                            <i class="fa fa-cart-plus text-lg text-white"></i>
                        </button>
                    </div>

                </div>

            </div>


            <div class="flex gap-2">
                <img
                  src="C:\Users\GEAN\Desktop\html\assets\hamb-2.png"
                  alt="Hamburger Duplo"
                  class="w-28 h-28 rounded-md hover:scale-110 hover:-rotate-2 duration-300"
                />

                <div>
                    <p class="font-bold">Hamburger Duplo</p>
                    <p class="text-sm">Pão levinho de fermentação natural da Trigou, 
                        burger 160g, queijo pratoe maionese da casa.</p>

                    <div class="flex items-center gap-2 justify-between mt-3">
                        <p class="font-bold text-lg">R$ 32.90</p>
                        <button 
                            class="bg-gray-900 px-5 rounded add-to-cart-btn"
                            data-name="Hamburger Duplo"
                            data-price="32.90"
                        >
                            <i class="fa fa-cart-plus text-lg text-white"></i>
                        </button>
                    </div>

                </div>

            </div>


            <div class="flex gap-2">
                <img
                  src="C:\Users\GEAN\Desktop\html\assets\hamb-3.png"
                  alt="Hamburger Salad"
                  class="w-28 h-28 rounded-md hover:scale-110 hover:-rotate-2 duration-300"
                />

                <div>
                    <p class="font-bold">Hamburger Salad</p>
                    <p class="text-sm">Pão levinho de fermentação natural da Trigou, 
                        burger 160g, queijo pratoe maionese da casa.</p>

                    <div class="flex items-center gap-2 justify-between mt-3">
                        <p class="font-bold text-lg">R$ 35.90</p>
                        <button 
                            class="bg-gray-900 px-5 rounded add-to-cart-btn"
                            data-name="Hamburger Salad"
                            data-price="35.90"
                        >
                            <i class="fa fa-cart-plus text-lg text-white"></i>
                        </button>
                    </div>

                </div>

            </div>


            <div class="flex gap-2">
                <img
                  src="C:\Users\GEAN\Desktop\html\assets\hamb-4.png"
                  alt="Hamburger da casa"
                  class="w-28 h-28 rounded-md hover:scale-110 hover:-rotate-2 duration-300"
                />

                <div>
                    <p class="font-bold">Hamburger da casa</p>
                    <p class="text-sm">Pão levinho de fermentação natural da Trigou, 
                        burger 160g, queijo pratoe maionese da casa.</p>

                    <div class="flex items-center gap-2 justify-between mt-3">
                        <p class="font-bold text-lg">R$ 30</p>
                        <button 
                            class="bg-gray-900 px-5 rounded add-to-cart-btn"
                            data-name="Hamburger da casa"
                            data-price="30"
                        >
                            <i class="fa fa-cart-plus text-lg text-white"></i>
                        </button>
                    </div>

                </div>

            </div>

        </main>

        <div class="mx-auto max-w-7xl px-2 my-2">
            <h2 class="font-bold text-3xl">
                Bebidas
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-7 md:gap-10 mx-auto max-w-7xl px-2 mb-16" id="menu">

            <div class="flex gap-2 w-full">
                <img
                  src="C:\Users\GEAN\Desktop\html\assets\refri-1.png"
                  alt="Coca lata"
                  class="w-28 h-28 rounded-md hover:scale-110 hover:-rotate-2 duration-300"
                />

                <div class="w-full">
                    <p class="font-bold">Coca lata</p>

                    <div class="flex items-center gap-2 justify-between mt-3">
                        <p class="font-bold text-lg">R$ 6</p>
                        <button 
                            class="bg-gray-900 px-5 rounded add-to-cart-btn"
                            data-name="Coca lata"
                            data-price="6"
                        >
                            <i class="fa fa-cart-plus text-lg text-white"></i>
                        </button>
                    </div>

                </div>

            </div>

            <div class="flex gap-2 w-full">
                <img
                  src="C:\Users\GEAN\Desktop\html\assets\refri-2.png"
                  alt="Guaraná lata"
                  class="w-28 h-28 rounded-md hover:scale-110 hover:-rotate-2 duration-300"
                />

                <div class="w-full">
                    <p class="font-bold">Guaraná lata</p>

                    <div class="flex items-center gap-2 justify-between mt-3">
                        <p class="font-bold text-lg">R$ 6</p>
                        <button 
                            class="bg-gray-900 px-5 rounded add-to-cart-btn"
                            data-name="Guaraná lata"
                            data-price="6"
                        >
                            <i class="fa fa-cart-plus text-lg text-white"></i>
                        </button>
                    </div>

                </div>

            </div>

        </div>

    </div>

    <div 
        class="bg-black/60 w-full h-full fixed top-0 left-0 z-[99] items-center justify-center hidden"
        id="cart-modal"
    >

        <div class="bg-white p-5 rounded-md min-w-[90%] md:min-w-[600px]">
            <h2 class="text-center font-bold text-2xl mb-2">Meu carrinho</h2>

            <div id="cart-items" class="flex justify-between mb-2 flex-col"></div>

            <p class="font-bold">Total: <span id="cart-total">0.00</span></p>

            <p class="font-bold mt-4">Endereço de entrega:</p>
            <input
                type="text"
                placeholder="Digite seu endereço completo..."
                id="address"
                class="w-full border-2 p-1 rounded my-1"
            />
            <p class="text-red-500 hidden" id="address-warn">Digite seu endereço completo!</p>

            <div class="flex items-center justify-between mt-5 w-full">
                <button id="close-modal-btn">Fechar</button>
                <button id="checkout-btn" class="bg-green-500 text-white px-4 py-1 rounded">Finalizar pedido</button>
            </div>

        </div>

    </div>

    <footer class="w-full bg-red-500 py-3 fixed bottom-0 z-40 flex items-center justify-center">
        <button 
        class="flex items-center gap-2 text-white font-bold"
        id="cart-btn"
        >
            (<span id="cart-count">0</span>)
            Veja meu carrinho
            <i class="fa fa-cart-plus text-lg text-white"></i>
        </button>
    </footer>


    <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/toastify-js"></script>
    <script src="script.js"></script>

</body>
</html>
