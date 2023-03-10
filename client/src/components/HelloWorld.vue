<template>
  <div class="flex space-between bg-white h-full w-full full">
    <div class=" w-1/2 left">
      <div class="mt-48 ml-24 ">
        <img src="../assets/sitting-dev.svg" alt="">
      </div>
    </div>
    <div class=" w-1/2">
       <h3 class="mt-8 text-4xl">Create Account</h3>
         <div class="mt-12">
          <form action="">
            <div class="mb-5">
           <label for="name" class="block mb-2 font-bold  text-lg text-left ml-20"> School Name</label>
           <input type="text" id="name" name="name" 
           class="border border-gray-300 shadow p-3 w-4/5 rounded mb-">
           <label for="name" class="block mt-8 font-bold text-lg text-gray-600 text-left ml-20">Email Address</label>
           <input type="text" id="email" name="email"
            class="border border-gray-300 shadow p-3 w-4/5 rounded mb-">
            <label for="name" class="block mt-8 font-bold text-lg text-gray-600 text-left ml-20">Password</label>
           <input type="text" id="password" name="password"
            class="border border-gray-300 shadow p-3 w-4/5 rounded mb-">
            <label class="block mb-1 text-lg font-bold text-left ml-20 mt-8" for="select-item">Country</label>

  <div class="relative w-4/5 ml-20">
    <select class="w-full border border-gray-300 shadow p-3 rounded focus:border-blue-500 focus:shadow-outline outline-none appearance-none" id="select-item">
      <option>Singapore</option>
      <option>Luxembourg</option>
      <option>Italy</option>
      <option>Germany</option>
      <option>USA</option>
      <option>Canada</option>
      <option>Brazil</option>
      <option>UAE</option>
    </select>

    <div class="pointer-events-none absolute inset-y-0 right-0 flex items-center px-2 text-gray-700">
      <svg class="fill-current h-4 w-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
        <path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z" />
      </svg>
    </div>
  </div>

  <label class="block mb-1 font-bold text-lg text-left ml-20 mt-8" for="select-item">State</label>

  <div class="relative  w-4/5 ml-20">
    <select class="w-full border  border-gray-300 shadow p-3 focus:shadow-outline outline-none appearance-none" id="select-item">
      <option>Singapore</option>
      <option>Luxembourg</option>
      <option>Italy</option>
      <option>Germany</option>
      <option>USA</option>
      <option>Canada</option>
      <option>Brazil</option>
      <option>UAE</option>
    </select>

    <div class="pointer-events-none absolute inset-y-0 right-0 flex items-center px-2 text-gray-700">
      <svg class="fill-current h-4 w-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
        <path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z" />
      </svg>
    </div>
  </div>
  <label for="name" class="block mb-2 font-bold  text-lg text-left ml-20 mt-8"> Address</label>
           <input type="text" id="address" name="address" 
           class="border border-gray-300 shadow p-3 w-4/5 rounded mb-">
         </div>
          </form>
          <button class="mt-12 text-white text-2xl rounded-xl font-semibold ">Create</button>
         </div>
    </div>
  </div>
</template>

<style scoped>
   button{
    background:  #3503FD;
    width: 356px;
    height: 73px;
   }
   .left{
    border-right: 1px solid #7A7A7A; 
   }
   .full{
    border-bottom-left-radius: 40%;
   }
</style>



<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>


