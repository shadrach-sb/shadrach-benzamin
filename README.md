<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>sb</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
</head>
<body>
    <nav class="w-full h-20 flex justify-between items-center p-4 px-[5%] bg-green-500">
       <div class="text-4xl font-bold text-white">Landing Page</div>
       <div class="md:flex">
            <ul class="flex space-x-7 text-white font-bold ">
               <li class ="px-4 py-2 rounded-lg text-white text-x1 font-medium hover:bg-green-200 hover:text-white transition">Home</li>
               <li class ="px-4 py-2 rounded-lg text-white text-x1 font-medium hover:bg-green-200 hover:text-white transition">About</li>
               <li class ="px-4 py-2 rounded-lg text-white text-x1 font-medium hover:bg-green-200 hover:text-white transition">Sign up</li>
            </ul>
        </div>

    </nav>
    <div class="flex justify-between itmes items-center mx-[5%] my-[2%]">
        <div class="pr-12">
            <h1 class="text-6xl text-green-700 font-bold ">GeeksforGeeks</h1>
            <button class="border-none border-red-100 text-lg font-semibold bg-gray-300 rounded-xl hover:bg-green-500 w-40 py- px-5 ">Explore More</button>
        </div>
        <div><img src="sbimage.webp" alt="img"/></div>
    </div>
    
</body>
</html>
