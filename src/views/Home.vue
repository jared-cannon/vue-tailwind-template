<template>
    <div class="home">
        <div class="min-h-screen bg-gray-100 py-6 flex flex-col justify-center sm:py-12">
            <div class="relative py-3 sm:max-w-xl sm:mx-auto">
                <div class="absolute inset-0 bg-gradient-to-r from-green-500 to-light-blue-500 shadow-lg transform -skew-y-6 sm:skew-y-0 sm:-rotate-6 sm:rounded-3xl"></div>
                <div class="relative px-4 py-10 bg-white shadow-lg sm:rounded-3xl sm:p-20">
                    <div class="max-w-md mx-auto">
                        <div class="flex flex-row justify-center">
                            <img class="h-8" src="../assets/logo.png" alt="Vue Logo">
                            <img class="h-6 mx-2 my-1" src="../assets/plus-icon.svg" alt="Plus Icon">
                            <svg class="h-8 w-14">
                                <path fill-rule="evenodd" clip-rule="evenodd" d="M25.517 0C18.712 0 14.46 3.382 12.758 10.146c2.552-3.382 5.529-4.65 8.931-3.805 1.941.482 3.329 1.882 4.864 3.432 2.502 2.524 5.398 5.445 11.722 5.445 6.804 0 11.057-3.382 12.758-10.145-2.551 3.382-5.528 4.65-8.93 3.804-1.942-.482-3.33-1.882-4.865-3.431C34.736 2.92 31.841 0 25.517 0zM12.758 15.218C5.954 15.218 1.701 18.6 0 25.364c2.552-3.382 5.529-4.65 8.93-3.805 1.942.482 3.33 1.882 4.865 3.432 2.502 2.524 5.397 5.445 11.722 5.445 6.804 0 11.057-3.381 12.758-10.145-2.552 3.382-5.529 4.65-8.931 3.805-1.941-.483-3.329-1.883-4.864-3.432-2.502-2.524-5.398-5.446-11.722-5.446z" fill="#06B6D4"></path>
                            </svg>
                        </div>
                        <div class="divide-y divide-gray-200">
                            <div class="py-8 text-base leading-6 space-y-4 text-gray-700 sm:text-lg sm:leading-7">
                                <p>
                                    A template project with Vue and Tailwind installed out of the box.
                                    Perfect for learning Vue and Tailwind or quickly spinning up a website.
                                </p>
                            </div>
                            <div class="pt-6 text-base leading-6 font-bold sm:text-lg sm:leading-7">
                                <p>
                                    <a href="https://v3.vuejs.org/guide/introduction.html" class="text-green-600 hover:text-green-700"> Read the Vue docs &rarr; </a>
                                </p>
                                <p>
                                    <a href="https://tailwindcss.com/docs" class="text-cyan-600 hover:text-cyan-700"> Read the Tailwind docs &rarr; </a>
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

export default {
  name: 'Home'
}
</script>
