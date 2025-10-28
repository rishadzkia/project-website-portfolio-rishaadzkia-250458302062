🚀 Setting Up Tailwind CSS via CDN

Use Tailwind CSS in your project no Node.js

1️⃣ Add the CDN Link to Your HTML

In your main HTML file, add this <script> inside the <head>:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Risha Portfolio</title>
  <!-- 🌟 Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body>
  <h1 class="text-3xl font-bold underline">
    Hello world! 🌈
  </h1>
</body>
</html>


2️⃣ Start Using Tailwind Classes

Now you can use Tailwind utility classes directly in your HTML.

Example:

<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
  Click Me ✨
</button>

- bg-blue-500 → background color
- hover:bg-blue-700 → changes background color on hover
- text-white → text color white
- font-bold → bold text
- py-2 px-4 → padding
- rounded → rounded corners
