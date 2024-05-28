<script>
export default{
  name: 'Header'
}
</script>

<template>
  <div class="flex items-center justify-center">
    <a class="mt-1" href="#">
      <img src="../assets/Logo.svg" alt="logo" id="logo">
    </a>

  
<!-- <form class="mx-auto">   
  <label for="default-search" class="mb-2 text-sm font-medium text-gray-900 sr-only dark:text-white">Search</label>
  <div class="relative">
      <div class="absolute inset-y-0 start-0 flex items-center ps-3 pointer-events-none">
          <svg class="w-4 h-4 text-gray-500 dark:text-gray-400" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 20">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m19 19-4-4m0-7A7 7 0 1 1 1 8a7 7 0 0 1 14 0Z"/>
          </svg>
      </div>
      <input type="search" id="default-search" class="block w-full p-4 ps-10 text-sm text-gray-900 border border-gray-300 rounded-lg bg-gray-50 focus:ring-blue-500 focus:border-blue-500  dark:border-gray-600 dark:placeholder-gray-400 dark:text-dark dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Search..." required />
      <button type="submit" class="text-white absolute end-2.5 bottom-2.5 bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
        Search
      </button>
  </div>
  
</form> -->
</div>

  <div class="book-now flex justify-center pt-5">
    <h1>Prenota subito il tuo Pet Taxi</h1>
  </div>

</template>

<style>
#logo{
  max-width: 700px;
  border-radius: 25px;

}

#default-search{
  width: 500px;
}

.book-now {
  font-size: 24px;
  font-weight: bold;
  color: #ffffff;
  text-align: center;
  padding: 20px;
  background-color: #ed5120;
  border-radius: 10px;
  cursor: pointer;
  transition: background-color 0.3s ease;
  max-width: 50%;
  margin: 1rem auto;
}

.book-now:hover {
  animation: wiggle 0.3s ease infinite alternate;
}

@keyframes wiggle {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(-5px);
  }
}

</style>
