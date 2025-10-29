<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maestría Social - Transforma Tu Vida Social en 30 Días</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800;900&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
        }
        
        .gradient-text {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .pulse-border {
            animation: pulse-ring 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
        }
        
        @keyframes pulse-ring {
            0%, 100% {
                box-shadow: 0 0 0 0 rgba(139, 92, 246, 0.7);
            }
            50% {
                box-shadow: 0 0 0 15px rgba(139, 92, 246, 0);
            }
        }
        
        .book-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .book-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.15);
        }

        .sticky-cta {
            position: fixed;
            bottom: 0;
            left: 0;
            right: 0;
            z-index: 50;
            transform: translateY(100%);
            transition: transform 0.3s ease;
        }

        .sticky-cta.visible {
            transform: translateY(0);
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }

        .float {
            animation: float 3s ease-in-out infinite;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- HERO SECTION -->
    <section class="relative bg-gradient-to-br from-purple-900 via-purple-800 to-indigo-900 text-white overflow-hidden">
        <div class="absolute inset-0 opacity-20">
            <div class="absolute inset-0" style="background-image: radial-gradient(circle at 2px 2px, white 1px, transparent 0); background-size: 40px 40px;"></div>
        </div>
        
        <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 md:py-24">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="text-center md:text-left">
                    <div class="inline-block bg-purple-500/30 backdrop-blur-sm px-4 py-2 rounded-full text-sm font-semibold mb-6 border border-purple-400/50">
                        🔥 Solo por tiempo limitado
                    </div>
                    
                    <h1 class="text-4xl md:text-6xl font-black leading-tight mb-6">
                        Domina las <span class="text-yellow-300">Habilidades Sociales</span> que Te Cambiarán la Vida
                    </h1>
                    
                    <p class="text-xl md:text-2xl text-purple-100 mb-8">
                        La biblioteca completa que todo hombre necesita para ser más <strong>seguro, carismático e irresistible</strong> en cualquier situación social
                    </p>
                    
                    <div class="flex flex-col sm:flex-row gap-4 mb-8">
                        <a href="#comprar" class="pulse-border bg-yellow-400 hover:bg-yellow-500 text-gray-900 font-bold text-lg px-8 py-5 rounded-xl transition-all transform hover:scale-105 shadow-2xl">
                            🚀 Acceso Inmediato - COP $15.000
                        </a>
                        <a href="#contenido" class="bg-white/10 backdrop-blur-sm hover:bg-white/20 text-white font-semibold px-8 py-5 rounded-xl transition-all border-2 border-white/30">
                            Ver Todo el Contenido ↓
                        </a>
                    </div>
                    
                    <div class="flex items-center justify-center md:justify-start gap-8 text-sm">
                        <div class="flex items-center gap-2">
                            <svg class="w-5 h-5 text-green-400" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                            </svg>
                            <span>Acceso Instantáneo</span>
                        </div>
                        <div class="flex items-center gap-2">
                            <svg class="w-5 h-5 text-green-400" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                            </svg>
                            <span>100% Digital</span>
                        </div>
                        <div class="flex items-center gap-2">
                            <svg class="w-5 h-5 text-green-400" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                            </svg>
                            <span>Privacidad Total</span>
                        </div>
                    </div>
                </div>
                
                <div class="float hidden md:block">
                    <div class="relative">
                        <div class="absolute inset-0 bg-gradient-to-br from-yellow-400 to-orange-500 rounded-3xl blur-3xl opacity-30"></div>
                        <img src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?w=600&h=800&fit=crop&q=80" alt="Hombre seguro y carismático" class="relative rounded-3xl shadow-2xl border-4 border-white/20 object-cover">
                    </div>
                </div>
            </div>
        </div>
        
        <div class="absolute bottom-0 left-0 right-0 h-16 bg-gradient-to-t from-gray-50 to-transparent"></div>
    </section>

    <!-- SOCIAL PROOF BAR -->
    <section class="bg-white py-6 border-b border-gray-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-wrap items-center justify-center gap-8 text-center">
                <div>
                    <div class="text-3xl font-black text-purple-600">+50</div>
                    <div class="text-sm text-gray-600">Libros Premium</div>
                </div>
                <div class="h-12 w-px bg-gray-300 hidden sm:block"></div>
                <div>
                    <div class="text-3xl font-black text-purple-600">+150</div>
                    <div class="text-sm text-gray-600">Frases de Apertura</div>
                </div>
                <div class="h-12 w-px bg-gray-300 hidden sm:block"></div>
                <div>
                    <div class="text-3xl font-black text-purple-600">100%</div>
                    <div class="text-sm text-gray-600">Garantía</div>
                </div>
                <div class="h-12 w-px bg-gray-300 hidden sm:block"></div>
                <div>
                    <div class="text-3xl font-black text-purple-600">24/7</div>
                    <div class="text-sm text-gray-600">Acceso Inmediato</div>
                </div>
            </div>
        </div>
    </section>

    <!-- PROBLEMA / SOLUCIÓN -->
    <section class="py-20 bg-gradient-to-b from-gray-50 to-white">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl md:text-5xl font-black text-gray-900 mb-6">
                    ¿Te Identificas con Esto?
                </h2>
            </div>
            
            <div class="grid lg:grid-cols-3 gap-8 mb-12">
                <div class="lg:col-span-2 space-y-8">
                    <div class="bg-red-50 border-l-4 border-red-500 p-6 rounded-lg">
                        <div class="flex items-start gap-4">
                            <div class="text-3xl">❌</div>
                            <div>
                                <h3 class="font-bold text-gray-900 mb-2">Sin Esto:</h3>
                                <ul class="space-y-2 text-gray-700">
                                    <li>• Te quedas sin palabras al hablar con alguien que te gusta</li>
                                    <li>• Ves cómo otros tienen éxito social mientras tú te quedas atrás</li>
                                    <li>• No sabes cómo iniciar o mantener conversaciones interesantes</li>
                                    <li>• Te falta confianza en situaciones sociales</li>
                                    <li>• Pierdes oportunidades por miedo al rechazo</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    
                    <div class="bg-green-50 border-l-4 border-green-500 p-6 rounded-lg">
                        <div class="flex items-start gap-4">
                            <div class="text-3xl">✅</div>
                            <div>
                                <h3 class="font-bold text-gray-900 mb-2">Con Este Pack:</h3>
                                <ul class="space-y-2 text-gray-700">
                                    <li>• Dominas el arte de la conversación en cualquier situación</li>
                                    <li>• Proyectas confianza y carisma naturalmente</li>
                                    <li>• Entiendes la psicología detrás de la atracción</li>
                                    <li>• Tienes +150 formas probadas de iniciar conversaciones</li>
                                    <li>• Conoces las estrategias que usan los más exitosos</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="hidden lg:block">
                    <img src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?w=500&h=700&fit=crop&q=80" alt="Hombre confiado en situación social" class="rounded-2xl shadow-xl object-cover w-full h-full">
                </div>
            </div>
        </div>
    </section>

    <!-- CONTENIDO COMPLETO -->
    <section id="contenido" class="py-20 bg-gray-900 text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <!-- Sección de transformación visual -->
            <div class="mb-20">
                <h2 class="text-3xl md:text-4xl font-black text-center mb-12">
                    La Transformación Que <span class="text-yellow-400">Todos Notan</span>
                </h2>
                <div class="grid md:grid-cols-2 gap-8 max-w-5xl mx-auto">
                    <div class="relative group">
                        <div class="absolute inset-0 bg-red-500 rounded-2xl blur-2xl opacity-20 group-hover:opacity-30 transition-opacity"></div>
                        <div class="relative bg-gradient-to-br from-gray-800 to-gray-900 rounded-2xl p-6 border-2 border-red-500/50">
                            <div class="bg-red-500 text-white text-sm font-bold px-3 py-1 rounded-full inline-block mb-4">ANTES</div>
                            <img src="https://images.unsplash.com/photo-1568602471122-7832951cc4c5?w=500&h=300&fit=crop&q=80" alt="Hombre inseguro" class="rounded-xl mb-4 w-full object-cover h-48 grayscale opacity-70">
                            <ul class="space-y-2 text-sm text-gray-300">
                                <li>❌ Inseguridad en situaciones sociales</li>
                                <li>❌ Conversaciones aburridas y predecibles</li>
                                <li>❌ Sin saber cómo generar atracción</li>
                                <li>❌ Miedo al rechazo paralizante</li>
                            </ul>
                        </div>
                    </div>
                    
                    <div class="relative group">
                        <div class="absolute inset-0 bg-green-500 rounded-2xl blur-2xl opacity-20 group-hover:opacity-30 transition-opacity"></div>
                        <div class="relative bg-gradient-to-br from-green-900 to-emerald-900 rounded-2xl p-6 border-2 border-green-500/50">
                            <div class="bg-green-500 text-white text-sm font-bold px-3 py-1 rounded-full inline-block mb-4">DESPUÉS</div>
                            <img src="https://images.unsplash.com/photo-1492562080023-ab3db95bfbce?w=500&h=300&fit=crop&q=80" alt="Hombre seguro y exitoso" class="rounded-xl mb-4 w-full object-cover h-48">
                            <ul class="space-y-2 text-sm text-green-100">
                                <li>✅ Confianza natural en cualquier contexto</li>
                                <li>✅ Conversaciones magnéticas y memorables</li>
                                <li>✅ Dominio de la psicología de atracción</li>
                                <li>✅ Control total de tus interacciones</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mb-16">
                <h2 class="text-4xl md:text-5xl font-black mb-6">
                    Todo Lo Que Recibes <span class="text-yellow-400">HOY</span>
                </h2>
                <p class="text-xl text-gray-300">
                    Contenido valorado en más de <span class="text-3xl font-black text-yellow-400">COP $850.000</span>
                </p>
            </div>

            <!-- EBOOK PRINCIPAL -->
            <div class="bg-gradient-to-br from-purple-600 to-indigo-700 rounded-3xl p-8 md:p-12 mb-8 border-4 border-yellow-400 overflow-hidden relative">
                <div class="absolute right-0 top-0 opacity-10 hidden md:block">
                    <img src="https://images.unsplash.com/photo-1544027993-37dbfe43562a?w=400&h=500&fit=crop&q=80" alt="Pareja feliz" class="rounded-3xl">
                </div>
                <div class="relative z-10 flex items-start gap-6">
                    <div class="bg-yellow-400 text-gray-900 text-2xl font-black px-4 py-2 rounded-xl shrink-0">
                        PRINCIPAL
                    </div>
                    <div class="flex-1">
                        <h3 class="text-3xl font-black mb-4">📘 Ebook Maestría en Seducción y Habilidades Sociales</h3>
                        <p class="text-xl text-purple-100 mb-4">
                            La guía definitiva para dominar el arte de la atracción, desde los fundamentos hasta técnicas avanzadas. Aprende a leer el lenguaje corporal, crear conexión emocional y generar atracción genuina.
                        </p>
                        <div class="inline-block bg-white/20 backdrop-blur-sm px-4 py-2 rounded-lg">
                            <span class="line-through text-purple-200">Valor: COP $150.000</span>
                            <span class="ml-3 text-yellow-300 font-bold">INCLUIDO</span>
                        </div>
                    </div>
                </div>
            </div>

            <!-- BONOS -->
            <div class="grid md:grid-cols-2 gap-6 mb-12">
                <!-- Bonus 1 -->
                <div class="book-card bg-gradient-to-br from-gray-800 to-gray-900 rounded-2xl p-6 border border-gray-700 relative overflow-hidden">
                    <div class="absolute right-0 bottom-0 opacity-5">
                        <img src="https://images.unsplash.com/photo-1512820790803-83ca734da794?w=300&h=400&fit=crop&q=80" alt="Biblioteca" class="w-48">
                    </div>
                    <div class="relative z-10">
                        <div class="flex items-start gap-4 mb-4">
                            <div class="bg-yellow-400 text-gray-900 font-black px-3 py-1 rounded-lg text-sm">
                                BONUS #1
                            </div>
                        </div>
                        <h4 class="text-2xl font-bold mb-3">📚 Biblioteca de +50 Libros Premium</h4>
                        <div class="space-y-2 text-gray-300 mb-4">
                            <p class="font-semibold text-white">Incluye bestsellers como:</p>
                            <ul class="space-y-1 text-sm">
                                <li>✦ Las 48 Leyes del Poder - Robert Greene</li>
                                <li>✦ El Sutil Arte de Que Te Importe un Carajo</li>
                                <li>✦ Psicología Oscura</li>
                                <li>✦ El Método</li>
                                <li>✦ Y 46 títulos más sobre autoestima, lenguaje corporal y psicología</li>
                            </ul>
                        </div>
                        <div class="inline-block bg-gray-700 px-4 py-2 rounded-lg">
                            <span class="line-through text-gray-400">Valor: COP $500.000</span>
                            <span class="ml-3 text-yellow-400 font-bold">GRATIS</span>
                        </div>
                    </div>
                </div>

                <!-- Bonus 2 -->
                <div class="book-card bg-gradient-to-br from-gray-800 to-gray-900 rounded-2xl p-6 border border-gray-700 relative overflow-hidden">
                    <div class="absolute right-0 bottom-0 opacity-5">
                        <img src="https://images.unsplash.com/photo-1516387938699-a93567ec168e?w=300&h=400&fit=crop&q=80" alt="Conversación" class="w-48">
                    </div>
                    <div class="relative z-10">
                        <div class="flex items-start gap-4 mb-4">
                            <div class="bg-yellow-400 text-gray-900 font-black px-3 py-1 rounded-lg text-sm">
                                BONUS #2
                            </div>
                        </div>
                        <h4 class="text-2xl font-bold mb-3">💬 +150 Abridores de Conversación</h4>
                        <p class="text-gray-300 mb-4">
                            Nunca más te quedes sin saber qué decir. Frases probadas y categorizadas por situación: apps de citas, redes sociales, en persona, mensajes de seguimiento y mucho más.
                        </p>
                        <div class="bg-gray-700 rounded-lg p-4 mb-4 text-sm">
                            <p class="text-gray-300 italic">"¿Cansada de los típicos 'hola'? Tengo una apuesta: si te hago reír en los próximos 3 mensajes, me debes una conversación interesante..."</p>
                        </div>
                        <div class="inline-block bg-gray-700 px-4 py-2 rounded-lg">
                            <span class="line-through text-gray-400">Valor: COP $80.000</span>
                            <span class="ml-3 text-yellow-400 font-bold">GRATIS</span>
                        </div>
                    </div>
                </div>

                <!-- Bonus 3 -->
                <div class="book-card bg-gradient-to-br from-red-900 to-pink-900 rounded-2xl p-6 border-2 border-red-400 md:col-span-2">
                    <div class="flex flex-col md:flex-row items-start gap-6">
                        <div>
                            <div class="flex items-center gap-4 mb-4">
                                <div class="bg-red-500 text-white font-black px-3 py-1 rounded-lg text-sm">
                                    BONUS EXCLUSIVO #3
                                </div>
                                <div class="bg-red-500/30 text-red-200 px-3 py-1 rounded-lg text-xs font-semibold">
                                    🔞 +18 AÑOS
                                </div>
                            </div>
                            <h4 class="text-2xl font-bold mb-3">🎥 Video Tutorial: Técnicas Avanzadas de Intimidad</h4>
                            <p class="text-gray-200 mb-4">
                                Contenido exclusivo y educativo sobre técnicas de placer. Aprende lo que la mayoría no sabe y conviértete en un amante memorable.
                            </p>
                            <div class="inline-block bg-red-800 px-4 py-2 rounded-lg">
                                <span class="line-through text-red-300">Valor: COP $120.000</span>
                                <span class="ml-3 text-yellow-300 font-bold">INCLUIDO</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- COMPARACIÓN DE VALOR -->
            <div class="bg-gradient-to-br from-yellow-400 to-orange-500 rounded-2xl p-8 text-gray-900">
                <div class="grid md:grid-cols-2 gap-8 items-center">
                    <div>
                        <h3 class="text-3xl font-black mb-4">Valor Total del Pack:</h3>
                        <div class="space-y-2 text-lg">
                            <div class="flex justify-between">
                                <span>Ebook Principal:</span>
                                <span class="font-bold">COP $150.000</span>
                            </div>
                            <div class="flex justify-between">
                                <span>+50 Libros Premium:</span>
                                <span class="font-bold">COP $500.000</span>
                            </div>
                            <div class="flex justify-between">
                                <span>+150 Abridores:</span>
                                <span class="font-bold">COP $80.000</span>
                            </div>
                            <div class="flex justify-between">
                                <span>Video Tutorial:</span>
                                <span class="font-bold">COP $120.000</span>
                            </div>
                            <div class="border-t-4 border-gray-900 pt-2 mt-4">
                                <div class="flex justify-between text-2xl font-black">
                                    <span>TOTAL:</span>
                                    <span>COP $850.000</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="text-center">
                        <div class="text-xl font-bold mb-2">TÚ PAGAS SOLO:</div>
                        <div class="text-7xl font-black mb-2">$15.000</div>
                        <div class="text-2xl font-bold">COP</div>
                        <div class="bg-gray-900 text-yellow-400 inline-block px-6 py-3 rounded-xl font-black text-xl mt-4">
                            98% DE DESCUENTO
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ / OBJECIONES -->
    <section class="py-20 bg-white">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl md:text-5xl font-black text-center mb-12">
                Preguntas Frecuentes
            </h2>
            
            <div class="space-y-4">
                <details class="bg-gray-50 rounded-xl p-6 hover:bg-gray-100 transition-colors">
                    <summary class="font-bold text-lg cursor-pointer">
                        ¿Cómo recibo el contenido después del pago?
                    </summary>
                    <p class="mt-4 text-gray-700">
                        Inmediatamente después de completar tu pago, recibirás un correo electrónico con el enlace de descarga. El acceso es instantáneo, 24/7.
                    </p>
                </details>

                <details class="bg-gray-50 rounded-xl p-6 hover:bg-gray-100 transition-colors">
                    <summary class="font-bold text-lg cursor-pointer">
                        ¿Esto realmente funciona o es pura teoría?
                    </summary>
                    <p class="mt-4 text-gray-700">
                        Todo el contenido está basado en psicología probada y experiencias reales. Los libros incluidos son bestsellers reconocidos mundialmente. Las técnicas han sido aplicadas por miles de personas con resultados comprobados.
                    </p>
                </details>

                <details class="bg-gray-50 rounded-xl p-6 hover:bg-gray-100 transition-colors">
                    <summary class="font-bold text-lg cursor-pointer">
                        ¿Es seguro? ¿Respetan mi privacidad?
                    </summary>
                    <p class="mt-4 text-gray-700">
                        100%. Todo es completamente digital y privado. No hay envíos físicos que puedan comprometer tu privacidad. Tu información está protegida y nunca es compartida.
                    </p>
                </details>

                <details class="bg-gray-50 rounded-xl p-6 hover:bg-gray-100 transition-colors">
                    <summary class="font-bold text-lg cursor-pointer">
                        ¿Funciona para mi edad? Tengo [X] años
                    </summary>
                    <p class="mt-4 text-gray-700">
                        Absolutamente. Ya sea que tengas 18 o 50 años, las habilidades sociales y la confianza son universales. Los principios de atracción y comunicación aplican en cualquier etapa de la vida.
                    </p>
                </details>

                <details class="bg-gray-50 rounded-xl p-6 hover:bg-gray-100 transition-colors">
                    <summary class="font-bold text-lg cursor-pointer">
                        ¿Hay garantía de devolución?
                    </summary>
                    <p class="mt-4 text-gray-700">
                        Sí, tienes 7 días de garantía. Si por alguna razón no estás satisfecho con el contenido, te devolvemos el 100% de tu dinero sin preguntas.
                    </p>
                </details>

                <details class="bg-gray-50 rounded-xl p-6 hover:bg-gray-100 transition-colors">
                    <summary class="font-bold text-lg cursor-pointer">
                        ¿Por qué está tan barato si vale tanto?
                    </summary>
                    <p class="mt-4 text-gray-700">
                        Es una promoción especial para hacer el conocimiento accesible. Queremos que más hombres tengan acceso a esta información que puede cambiar sus vidas. El precio puede aumentar en cualquier momento.
                    </p>
                </details>
            </div>
        </div>
    </section>

    <!-- URGENCIA Y CTA FINAL -->
    <section id="comprar" class="py-20 bg-gradient-to-br from-purple-900 via-purple-800 to-indigo-900 text-white relative overflow-hidden">
        <div class="absolute inset-0 opacity-10">
            <img src="https://images.unsplash.com/photo-1511632765486-a01980e01a18?w=1920&h=1080&fit=crop&q=80" alt="Grupo social" class="w-full h-full object-cover">
        </div>
        
        <div class="relative z-10 max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <div class="bg-red-500 inline-block px-6 py-3 rounded-full font-bold text-lg mb-8 animate-pulse">
                ⚠️ OFERTA POR TIEMPO LIMITADO
            </div>
            
            <h2 class="text-4xl md:text-6xl font-black mb-6">
                Es Momento de Tomar Acción
            </h2>
            
            <p class="text-xl md:text-2xl text-purple-100 mb-12">
                Mientras lees esto, otros ya están aplicando estas técnicas y obteniendo resultados. <br>
                <strong class="text-yellow-300">¿Vas a ser el próximo o seguirás esperando?</strong>
            </p>

            <div class="bg-white/10 backdrop-blur-sm rounded-3xl p-8 md:p-12 border-2 border-white/20 mb-8">
                <div class="text-6xl md:text-8xl font-black text-yellow-400 mb-4">
                    COP $15.000
                </div>
                <p class="text-xl text-purple-100 mb-8">
                    Inversión única • Acceso de por vida • Sin pagos recurrentes
                </p>
                
                <a href="https://wa.me/573002219230?text=Hola%2C%20quiero%20el%20Pack%20Maestría%20Social" class="inline-block bg-yellow-400 hover:bg-yellow-500 text-gray-900 font-black text-xl md:text-2xl px-12 py-6 rounded-2xl transition-all transform hover:scale-105 shadow-2xl pulse-border">
                    🚀 ACCEDER AHORA AL PACK COMPLETO
                </a>
                
                <div class="mt-8 flex flex-col sm:flex-row items-center justify-center gap-6 text-sm">
                    <div class="flex items-center gap-2">
                        <svg class="w-5 h-5 text-green-400" fill="currentColor" viewBox="0 0 20 20">
                            <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                        </svg>
                        <span>Acceso Inmediato</span>
                    </div>
                </div>
            </div>

            <div class="grid md:grid-cols-3 gap-6 mt-12">
                <div class="bg-white/5 backdrop-blur-sm rounded-2xl p-6 border border-white/10">
                    <div class="text-4xl mb-3">🎯</div>
                    <h3 class="font-bold text-lg mb-2">Transforma Tu Vida</h3>
                    <p class="text-purple-200 text-sm">Las habilidades que aprenderás te servirán toda la vida</p>
                </div>
                <div class="bg-white/5 backdrop-blur-sm rounded-2xl p-6 border border-white/10">
                    <div class="text-4xl mb-3">💰</div>
                    <h3 class="font-bold text-lg mb-2">Sin Riesgo</h3>
                    <p class="text-purple-200 text-sm">7 días de garantía de devolución total</p>
                </div>
                <div class="bg-white/5 backdrop-blur-sm rounded-2xl p-6 border border-white/10">
                    <div class="text-4xl mb-3">⚡</div>
                    <h3 class="font-bold text-lg mb-2">Instantáneo</h3>
                    <p class="text-purple-200 text-sm">Descarga todo en menos de 5 minutos</p>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-gray-900 text-gray-400 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p class="mb-4">© 2025 Pack Maestría Social. Todos los derechos reservados.</p>
            <p class="text-sm">Este es un producto digital. No hay envíos físicos. El acceso es inmediato tras la compra.</p>
            <p class="text-sm mt-2">Contenido para mayores de 18 años. Privacidad garantizada.</p>
        </div>
    </footer>

    <!-- STICKY CTA MOBILE -->
    <div id="sticky-cta" class="sticky-cta bg-yellow-400 shadow-2xl">
        <div class="max-w-7xl mx-auto px-4 py-4">
            <div class="flex items-center justify-between">
                <div>
                    <div class="font-black text-gray-900 text-lg">COP $15.000</div>
                    <div class="text-xs text-gray-700">98% descuento por tiempo limitado</div>
                </div>
                <a href="https://wa.me/573000000000?text=Hola%2C%20quiero%20el%20Pack%20Maestría%20Social" class="bg-gray-900 hover:bg-gray-800 text-white font-bold px-6 py-3 rounded-xl transition-all">
                    Comprar Ahora
                </a>
            </div>
        </div>
    </div>

    <script>
        // Sticky CTA on scroll
        window.addEventListener('scroll', function() {
            const stickyCta = document.getElementById('sticky-cta');
            if (window.scrollY > 800) {
                stickyCta.classList.add('visible');
            } else {
                stickyCta.classList.remove('visible');
            }
        });

        // Smooth scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({ behavior: 'smooth', block: 'start' });
                }
            });
        });
    </script>
</body>
</html>text-green-400" fill="currentColor" viewBox="0 0 20 20">
                            <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                        </svg>
                        <span>Pago Seguro</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <svg class="w-5 h-5 text-green-400" fill="currentColor" viewBox="0 0 20 20">
                            <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                        </svg>
                        <span>Garantía 7 Días</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <svg class="w-5 h-5 
