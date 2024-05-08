<h1>TAILWIND CSS LECTURE 3</h1>
<p>In this repository, I learned about <b>Why use Tailwind CSS?</b>.</p>
<h1>WHY USE TAILWIND CSS ?</h1>
<ul><li>No reinventing of class names required.</li>
<li>Your CSS doesn't grow with your html and designs.</li>
<li>When you make a change, no risk of breaking existing templates.</li>
<li>It doesn't make site slow and doesn't increase bundle size.</li>
<li>Site remains responsive.</li></ul>
<h1>SETTING UP TAILWIND CSS</h1>
<ul><li>npm init -y //Initializes directory as Node.js project</li>
<li>npm install -D tailwindcss postcss autoprefixer //Install required packages</li>
<li>npm install vite</li>
<li>npx tailwindcss init -p</li>
<li>Create CSS file "input.css", add it to your html and edit it with this content:

@tailwind base;
@tailwind components;
@tailwind utilities;</li>
<li>In your tailwind.config.js file replace content:[], with content:["*"].</li>
<li>Add "start":"vite" to your scripts in package.json.</li>
<li>Run npm run start command to start a dev server.</li></ul>
