<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile</title>
    <!-- Tailwind CSS CDN for easy styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom font for a clean look */
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100 min-h-screen flex items-center justify-center p-4">

    <!-- Main profile card container -->
    <div class="bg-white rounded-xl shadow-lg p-8 max-w-sm w-full mx-auto flex flex-col items-center">
        <!-- Profile Picture -->
        <div class="mb-6">
            <img 
                src="https://i.pinimg.com/736x/4e/54/e8/4e54e882356e01cd1c1ccccd5b71a27a.jpg" 
                alt="Profile Picture" 
                class="w-36 h-36 rounded-full object-cover border-4 border-purple-300 shadow-md"
                onerror="this.onerror=null;this.src='https://placehold.co/150x150/CCCCCC/000000?text=Error';"
            >
        </div>

        <!-- Name -->
        <h1 class="text-3xl font-bold text-gray-800 mb-2">John Doe</h1>

        <!-- Occupation/Title -->
        <p class="text-lg text-purple-600 mb-6">Web Developer | Designer</p>

        <!-- Short Bio -->
        <div class="text-center text-gray-700 mb-8">
            <p class="leading-relaxed">
                Passionate about creating engaging and user-friendly web experiences. 
                Constantly learning new technologies and striving for elegant solutions.
            </p>
        </div>

        <!-- Interests Section -->
        <div class="w-full">
            <h2 class="text-xl font-semibold text-gray-800 mb-4 border-b-2 border-purple-200 pb-2 text-center">Interests</h2>
            <ul class="list-none p-0 m-0 grid grid-cols-2 gap-2 text-gray-600">
                <li class="bg-purple-50 text-purple-700 px-3 py-1 rounded-full text-sm text-center">Coding</li>
                <li class="bg-purple-50 text-purple-700 px-3 py-1 rounded-full text-sm text-center">Photography</li>
                <li class="bg-purple-50 text-purple-700 px-3 py-1 rounded-full text-sm text-center">Hiking</li>
                <li class="bg-purple-50 text-purple-700 px-3 py-1 rounded-full text-sm text-center">Reading</li>
            </ul>
        </div>
    </div>

</body>
</html>
