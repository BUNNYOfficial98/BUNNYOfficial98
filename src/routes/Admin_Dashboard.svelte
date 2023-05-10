<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WakuWaku</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- <script src="./tailwind3.js"></script> -->
  <script src="https://kit.fontawesome.com/YOUR-KIT-ID.js" crossorigin="anonymous"></script>
  <script src="https://example.com/fontawesome/v5.15.4/js/all.js" data-family-prefix="icon"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;800&display=swap"
  rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.2/font/bootstrap-icons.css"> 

<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">

<!-- jQuery library -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>

<!-- Latest compiled JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

</head>

<style>
  body {
    background-color: rgb(224 231 255);
    padding: 0;
  }
  header {  
  display: flex; 
  justify-content: flex-end;
  align-items: center;
  height: 60px;
}

.notification {
  font-size: 1.125rem; /* 18px */
  line-height: 1.75rem; /* 28px */
  position: relative;
  padding: 0.3em 0.6em;
  border-radius: 9999px;
  margin-right: 20px;
  background-color: whitesmoke; /* add some margin to separate the notification from other elements */
}
.notification:hover {
  cursor: pointer; /* change the cursor to a pointer on hover */
  background-color: #153ef3;
  color: white;/* add a light gray background color */
}

/* Make badge responsive */
.badge {
  border-radius: 9999px;

  margin-right: 20px;
  position: relative;
  font-size: 1.125rem; /* 18px */
  line-height: 1.75rem; /* 28px */
  padding: 0.3em 0.7em;
  background-color: #153ef3;
  color: white;
  font-family: sans-serif;
  font-style: italic;
}

@media screen and (max-width: 768px) {
  .badge {
    font-size: 1.2em;
    padding: 0.15em 0.4em;
  }
}
    aside {
      height: 100%;
      width: 210px; /* adjust as needed */
      position: fixed;
      top: 0;
      left: 0;
      background-color: white;
      /* box-shadow: 0 25px 50px -12px rgb(0 0 0 / 0.25); */
      padding: 1rem;
      font-weight: bold;
    }
.container {
  max-width: 805px;
  margin: 3px;
  margin-left: 18%;
  padding: 1%;
  background-color: white;
  border-radius: 0.5rem; /* 8px */
}

.container button {
  font-size: 20px;
  margin-top: -5%;
  padding: 1px;
  background-color: rgb(59 130 246);
  color: white;
  border-radius: 0.375rem;
}
.container h1 {
  text-align: left;
}
.container p {
  text-align: left;
}
.menu {
  text-align: center;
  font-size: large;
  padding: 10%;
}
.menu span {
    cursor: pointer;
    }
    .menu span:hover {
      color: white
    }
.m-container {
  max-width: 390px;
  margin: 1px auto;
  margin-left: 18%;
  margin-top: 25px;
  padding: 1vh;
  background-color: white;
  background-color: white;
  font-size: 20px;
  justify-content: space-between;
  justify-content: center;
  align-content: center;
  border-radius: 0.5rem; /* 8px */
}



.m1-container {
  max-width: 390px;
  margin: 1px auto;
  margin-right: 300px;
  margin-top: -11.60%;
  padding: 1vh;
  background-color: white;
  font-size: 20px;
  border-radius: 0.5rem; /* 8px */
 }


h1 {
  font-size: 2em;
  text-align: center;
}

@media screen and (min-width: 600px) {
  h1 {
    font-size: 3em;
  }
}

p {
  font-size: 1em;
  text-align: center;
}

@media screen and (min-width: 600px) {
  p {
    font-size: 1.2em;
  }
}
.w3-panel {
  max-width: 805px;
  min-height: 350px;
  margin: 5px;
  margin-top: 20px;
  margin-left: 18%;
  padding: 5vh;
  background-color: white;
  border-radius: 0.5rem; /* 8px */
  top: 444px;
left: 226px;
width: 802px;
height: 302px;
/* UI Properties */
background: var(--text-icons-btn-bg4) 0% 0% no-repeat padding-box;
border: 1px solid var(--line-1);
background: #FDFDFD 0% 0% no-repeat padding-box;
border: 1px solid #E4E4E4;
border-radius: 6px;
opacity: 1;
}
.w3-panel span {
  text-align: normal;
  font-size: 20px;
  font-weight: bold;
}
.w3-panel p {
  text-align: left;
  font-size: 15px;
}
.inside-panel {
  max-width: 350px; 
  padding: 20px;
  background-color: rgb(224 231 255);
  border-radius: 0.5rem; /* 8px */
} 
.inside-panel p {
color: var(--background-1);
text-align: left;
font: normal normal normal 12px/21px Segoe UI;
letter-spacing: 0px;
color: #2F80ED;
opacity: 1;
}
.panel {
    /* Layout Properties */
top: 463px;
left: 630px;
width: 382px;
height: 290px;
/* UI Properties */
opacity: 0.5;
  max-width: 350px;
  padding: 10px;
  background-color: rgb(224 231 255);
  border-radius: 0.5rem; /* 8px */
  margin: 2px auto;
  margin-right: -5px;
  margin-top: -40%;
}
.panel h1 {
  font-weight: normal;
  font-size: 20px;
  padding-right: 50%;
  
}
.panel p {
  text-align: start;
  font-size: 20px;
  
}
.panel span {
  background-color: white;
  border-radius: 0.5rem;
  font-size: 20px;
  color: black;
}
.right-container {
  margin-right: 2%;
  margin-left: 80%;
  margin-top: -735px;
  padding: 0;
  height: 380px;
  background-color: white;
  border-radius: 0.5rem; /* 8px */
}
.right-container p{
  font-size: 20px;
  text-align: start;
  margin-left: 2%;
  padding-top: 2%;
  font-weight: bold;
}
.right-container i {
  margin: 5%;
  font-size: 20px;
  margin-right: 2%;
  font-weight: bold;
}
.right-container h {
  margin: 2%;
  font-size: 18px;
}

  </style>

<body>
  <header>
    <span class="notification">
      <i class="fa-regular fa-bell"></i>
  </span>
  <span class="badge">P</span>
  </header>

 <aside>
    <div class="avatar">
      <img src="/src/routes/assets/img/logo.png">
    </div>
    <br>
    <div class="menu">
      <div class="p-2.5 mt-2 flex items-center rounded-md px-4 duration-300 cursor-pointer hover:bg-blue-500">
        <i class="fa-solid fa-house"></i>
        <span class="text-[15px] ml-4 color-black">Dashboard</span>
      </div>
      <div class="p-2.5 mt-2 flex items-center rounded-md px-4 duration-300 cursor-pointer  hover:bg-blue-500">
        <i class="fa-solid fa-users"></i>
        <span class="text-[15px] ml-4 color-black">My surveys</span>
      </div>
      <div class="p-2.5 mt-2 flex items-center rounded-md px-4 duration-300 cursor-pointer  hover:bg-blue-500">
        <i class="fa fa-file"></i>
        <span class="text-[15px] ml-4 color-black">Forms</span>
      </div>
      <div class="p-2.5 mt-2 flex items-center rounded-md px-4 duration-300 cursor-pointer  hover:bg-blue-500">
        <i class="fa fa-pie-chart"></i>
        <span class="text-[15px] ml-4 color-black">Analytics</span>
      </div>
    </div>
</aside>

  <main>
     <div class="container">
      <h1>Hello, Admin <span style="color: rgb(14 165 233);">Yukio!</span></h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      <br>
      <button>
        Create form
      </button>
  </main>
  <div class="m-container">
    <span>Schools</span><br>
    <div style="text-align: right;" class="icon">
      <i class="fa fa-flag"></i><br>
      <span>View all</span>
      </div>
      <span>0</span>
    <br>
    <span>Registered schools</span>
  </div>
  <div class="m1-container">
    <span>Forms</span><br>  
    <div style="text-align: right;" class="icon">
      <i class="fa fa-file"></i><br>
      <span>View all</span>
      </div>
      <span>0</span>
    <br>
    <span>Current forms</span>
    
  </div>
<div>
</div>
  <div class="w3-panel">
    <span>Published forms</span> 
    <p>The public forms well be displayed here. These</p>
    <p>are the steps for creating and letting the students</p>
    <p>see it.</p>
    <div class="inside-panel">
      <p>Step 1. Create a school in my survey in the side navigation.</p>
      <p>Step 2. Go to forms in the side navigation.</p>
      <p>Step 3. Select create form and edit.</p>
      <p>Step 4. Share the form with a school and publish it.</p>
    </div>
    <div class="panel">
      <p>Published forms</p>
      <div class="w-100 bg-white h-20 rounded-md">
        <span class="badge" style="background-color:rgb(2 132 199); border-radius: 9999px; margin-left: 5px; margin-top: 6px; color: rgb(2 132 199) ;  width: 1px; ">.
        </span>
         <span style="font-size: 15px; font-weight: normal;">Untitled form 1 <span class="badge" style="background-color: green; font-size: 2px; height: 10px; width: 2px;">.</span>
         <span style="font-size: 15px; font-weight: normal; margin-left: 75px;">160/416</span>
        <div class="progress" style="height: 8px; width: 88%; align-items: absolute; margin-left: 33px; margin-top: -2%;">
          <div class="progress-bar" role="progressbar" style="width: 45%;">
        </div>
      </div>
      <div class="w-100 bg-white h-20 rounded-md">
        <span class="badge" style="background-color:rgb(2 132 199); border-radius: 9999px; margin-left: 5px; margin-top: 6px; color: rgb(2 132 199) ;  width: 1px; ">.
        </span>
         <span style="font-size: 15px; font-weight: normal;">Untitled form 2    
          <span class="badge" style="background-color: green; font-size: 2px; height: 10px; width: 2px;">.</span>
         <span style="font-size: 15px; font-weight: normal; margin-left: 75px;">587/902</span>
        <div class="progress" style="height: 8px; width: 88%; align-items: absolute; margin-left: 33px; margin-top: -2%;">
          <div class="progress-bar" role="progressbar" style="width: 66%;">
        </div>
      </div>
      <div class="w-100 bg-white h-20 rounded-md">
        <span class="badge" style="background-color:rgb(2 132 199); border-radius: 9999px; margin-left: 5px; margin-top: 6px; color: rgb(2 132 199) ;  width: 1px; ">.
        </span>
         <span style="font-size: 15px; font-weight: normal;">Untitled form 3 <span class="badge" style="background-color: green; font-size: 2px; height: 10px; width: 2px;">.</span>
         <span style="font-size: 15px; font-weight: normal; margin-left: 90px;">0/384</span>
        <div class="progress" style="height: 8px; width: 88%; align-items: absolute; margin-left: 33px; margin-top: -2%;">
          <div class="progress-bar" role="progressbar" style="width: 0%;">
        </div>
      </div>
      <div class="w-100 bg-white h-20 rounded-md">
        <span class="badge" style="background-color:rgb(2 132 199); border-radius: 9999px; margin-left: 5px; margin-top: 6px; color: rgb(2 132 199) ;  width: 1px; ">.
        </span>
         <span style="font-size: 15px; font-weight: normal;">Untitled form 4 <span class="badge" style="background-color: green; font-size: 2px; height: 10px; width: 2px;">.</span>
         <span style="font-size: 15px; font-weight: normal; margin-left: 90px;">0/289</span>
        <div class="progress" style="height: 8px; width: 88%; align-items: absolute; margin-left: 33px; margin-top: -2%;">
          <div class="progress-bar" role="progressbar" style="width: 0%;">
        </div>
      </div>
</body>
<div>
  <div class="right-container">
    <p>Schools</p>
    <br>
      <div class="w-11 bg-success p-10 mx-5 h-20 rounded-full py-1"></div>
        <div class="w-52 bg-success mx-11 mt-3 h-9 rounded-full"></div>
        <div class="w-32 bg-success mx-11 mt-3 h-7 rounded-full"></div>
    <br>
    <div class="w-11 bg-success p-10 mx-5 h-20 rounded-full py-1"></div>
    <div class="w-52 bg-success mx-11 mt-3 h-9 rounded-full"></div>
    <div class="w-32 bg-success mx-11 mt-3 h-7 rounded-full"></div>
    <br>
    <br>
    <i class="fa-light fa-plus outline-dashed p-3"></i>
    <h>Create school space</h>
  </div>
</div>
