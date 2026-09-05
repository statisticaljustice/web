+++
title = "Contáctanos"
showTableOfContents = false
showRecent = false
showDate = false
showWordCount = false
showReadingTime = false
showPagination = false
+++

Por favor, usa el formulario a continuación para ponerte en contacto sobre investigación, charlas o materiales educativos.

<form action="https://formspree.io/f/xjyvojdn" method="POST" class="flex flex-col max-w-xl gap-5 mt-8">
  
  <!-- Campo oculto para redirigir a la página de gracias -->
  <input type="hidden" name="_next" value="https://statisticaljustice.com/gracias/">
  
  <div class="flex flex-col gap-2">
    <label for="email" class="text-sm font-semibold text-neutral-800 dark:text-neutral-200">
      Correo electrónico
    </label>
    <input 
      type="email" 
      name="email" 
      id="email" 
      required 
      placeholder="tu@correo.com" 
      class="w-full px-4 py-2 border rounded-lg shadow-sm bg-neutral-50 border-neutral-300 text-neutral-900 focus:outline-none focus:ring-2 focus:ring-primary-500 focus:border-primary-500 dark:bg-neutral-800 dark:border-neutral-700 dark:text-white dark:placeholder-neutral-500" 
    />
  </div>

  <div class="flex flex-col gap-2">
    <label for="message" class="text-sm font-semibold text-neutral-800 dark:text-neutral-200">
      Mensaje
    </label>
    <textarea 
      name="message" 
      id="message" 
      rows="5" 
      required 
      placeholder="Escribe tu mensaje aquí..." 
      class="w-full px-4 py-2 border rounded-lg shadow-sm bg-neutral-50 border-neutral-300 text-neutral-900 focus:outline-none focus:ring-2 focus:ring-primary-500 focus:border-primary-500 dark:bg-neutral-800 dark:border-neutral-700 dark:text-white dark:placeholder-neutral-500"
    ></textarea>
  </div>

  <button 
    type="submit" 
    class="px-6 py-2.5 mt-2 font-semibold text-white transition-all duration-200 rounded-lg shadow-md w-max bg-primary-600 hover:bg-primary-700 focus:outline-none focus:ring-2 focus:ring-primary-500 focus:ring-offset-2 dark:focus:ring-offset-neutral-900">
    Enviar
  </button>
  
</form>