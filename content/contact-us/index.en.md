+++
title = "Contact Us"
showTableOfContents = false
showRecent = false
showDate = false
showWordCount = false
showReadingTime = false
showPagination = false
+++

Please use the form below to get in touch regarding research, talks, or educational materials.

<form action="https://formspree.io/f/xjyvojdn" method="POST" class="flex flex-col max-w-xl gap-5 mt-8">
  
  <!-- Hidden field to redirect to the thanks page -->
  <input type="hidden" name="_next" value="https://statisticaljustice.com/thanks/">
  
  <div class="flex flex-col gap-2">
    <label for="email" class="text-sm font-semibold text-neutral-800 dark:text-neutral-200">
      Email
    </label>
    <input 
      type="email" 
      name="email" 
      id="email" 
      required 
      placeholder="you@email.com" 
      class="w-full px-4 py-2 border rounded-lg shadow-sm bg-neutral-50 border-neutral-300 text-neutral-900 focus:outline-none focus:ring-2 focus:ring-primary-500 focus:border-primary-500 dark:bg-neutral-800 dark:border-neutral-700 dark:text-white dark:placeholder-neutral-500" 
    />
  </div>

  <div class="flex flex-col gap-2">
    <label for="message" class="text-sm font-semibold text-neutral-800 dark:text-neutral-200">
      Message
    </label>
    <textarea 
      name="message" 
      id="message" 
      rows="5" 
      required 
      placeholder="Write your message here..." 
      class="w-full px-4 py-2 border rounded-lg shadow-sm bg-neutral-50 border-neutral-300 text-neutral-900 focus:outline-none focus:ring-2 focus:ring-primary-500 focus:border-primary-500 dark:bg-neutral-800 dark:border-neutral-700 dark:text-white dark:placeholder-neutral-500"
    ></textarea>
  </div>

  <button 
    type="submit" 
    class="px-6 py-2.5 mt-2 font-semibold text-white transition-all duration-200 rounded-lg shadow-md w-max bg-primary-600 hover:bg-primary-700 focus:outline-none focus:ring-2 focus:ring-primary-500 focus:ring-offset-2 dark:focus:ring-offset-neutral-900">
    Send
  </button>
  
</form>