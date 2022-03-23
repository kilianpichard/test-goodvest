<template>
  <div class="bg-white w-8/12 md:w-6/12 xl:w-4/12 lg:w-5/12 2xl:w-4/12 overflow-hidden rounded-lg flex flex-col items-between justify-between form column-3">
    <div class="w-full flex items-center flex-col">
      <img src="@/assets/kids-devices-1.png" class="w-full h-56 2xl:h-64 object-cover"/>
      <p class="font-serif italic text-4xl font-extralight my-3 2xl:text-5xl 2xl:my-5">
        Sign in
      </p>
      <div class="w-full px-11">
          <div class="w-full my-2 mb-8 font-bold">
            <p class="pb-2 2xl:text-xl">Username or email</p>
            <input type="text" class="w-full h-12 px-3 rounded-sm border border-gray-300 2xl:h-14"
                    placeholder="Your usermail or email"/>
          </div>
          <div class="w-full mt-2 font-bold">
            <p class=" pb-2 2xl:text-xl">Password</p>
            <input type="password" class="w-full h-12 px-3 rounded-sm border border-gray-300 2xl:h-14" placeholder="Your password"/>
          </div>
          <div class="w-full -mt-1.5 mb-2 2xl:-mt-0.5 2xl:mb-4">
            <a class="text-primary text-xs font-bold 2xl:text-sm">Forgot password?</a>
          </div>
      </div>
    </div>
    <div class="flex border-t px-11 border-gray-300 w-full py-4 items-center justify-between">
      <div class="text-xs 2xl:text-base">Don't have an account ? <a class="text-primary">Sign up</a></div>
      <button class="w-28 h-10 text font-bold rounded bg-primary text-white">Sign in</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "login"
}
</script>

<style scoped>
</style>