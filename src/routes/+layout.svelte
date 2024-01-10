<script>
    import "../app.css";
  </script>
  <nav class="px-4 py-2 flex justify-between text-white gap-3 bg-slate-900 rainbow">

    <a href="/" class="flex gap-3 items-center">
		<svg  width="29" height="30" viewBox="0 0 29 30" fill="none" xmlns="http://www.w3.org/2000/svg" class="rainbow-bg">
        <path d="M0 0V30H29V0H0ZM23 9H17V21H23V25H6V21H12V9H6V5H23V9Z" fill="white"/>
      </svg>Enjoy code in the dark with kakao
	</a>
	<div class="flex gap-3 items-center">
	  <a href="/example" class="rainbow">Example</a>
	  <a href="/task1" class="rainbow">Task 1</a>
	  <a href="/task2" class="rainbow">Task 2</a>
	  <a href="/task3" class="rainbow">Task 3</a>
  </nav>
  <slot />

  <style>
    .rainbow-bg{
		animation: rainbow-bg 2.5s linear;
		animation-iteration-count: infinite;
}
    .rainbow{
		animation: rainbow 2.5s linear;
		animation-iteration-count: infinite;
}

@keyframes rainbow-bg{
		100%,0%{
			background-color: rgb(255,0,0);
		}
		8%{
			background-color: rgb(255,127,0);
		}
		16%{
			background-color: rgb(255,255,0);
		}
		25%{
			background-color: rgb(127,255,0);
		}
		33%{
			background-color: rgb(0,255,0);
		}
		41%{
			background-color: rgb(0,255,127);
		}
		50%{
			background-color: rgb(0,255,255);
		}
		58%{
			background-color: rgb(0,127,255);
		}
		66%{
			background-color: rgb(0,0,255);
		}
		75%{
			background-color: rgb(127,0,255);
		}
		83%{
			background-color: rgb(255,0,255);
		}
		91%{
			background-color: rgb(255,0,127);
		}
}

@keyframes rainbow{
		100%,0%{
			color: rgb(255,0,0);
		}
		8%{
			color: rgb(255,127,0);
		}
		16%{
			color: rgb(255,255,0);
		}
		25%{
			color: rgb(127,255,0);
		}
		33%{
			color: rgb(0,255,0);
		}
		41%{
			color: rgb(0,255,127);
		}
		50%{
			color: rgb(0,255,255);
		}
		58%{
			color: rgb(0,127,255);
		}
		66%{
			color: rgb(0,0,255);
		}
		75%{
			color: rgb(127,0,255);
		}
		83%{
			color: rgb(255,0,255);
		}
		91%{
			color: rgb(255,0,127);
		}
}
  </style>