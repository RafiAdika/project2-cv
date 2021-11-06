<template>
    <div id="c"> 
        <div id="a"> 
            <div id="d"> 
                <h2>Rafi Adika<font id="e"><br> Roja</font> 
                </h2> 
                <img src="photo.jpg" width="250" height="150"> 
                <h3>Contact 
                    <hr> 
                </h3> 
                <p>address:<br>Karanggayam,Mangkang Wetan RT 03 RW 04</p> 
                <p>Phone:<br>082223461965</p> 
                <p>Email:<br><u>rafiadika64@gmail.com</u></p> 
                <p>Linkedln:<br>-</p> 
                <h3>Bahasa 
                    <hr> 
                </h3> 
                <ul>
                <li>Spanish-C2<br><li>Chinese-A1<br><li>German-A2</li>
                </ul> 
                <h3>Hobi 
                    <hr> 
                </h3> 
                <ul>
                <li>Writting<br><li>Sketcing<br><li>Photography<br><li>Design</li>
                </ul> 
            </div> 
            <div id="b"> 
                <h2>Summary</h2>
        <hr />
        <p>Senior Web Developer Specializing in front and development.<br>Experience with all stages of the development cycle for.<br>Dynamic
        Web Project. Well-versed in numerous programming<br> Languages including HTMLS, PHP OPP, JavaScript, CSS, MySQL.<br>Strong
     in project management and customer relations</p>

     <h2>Skill Highlights</h2>
     <hr />
     <div style="display: flex;">
         <div>
            <ul>
                <li>Project Management</li>
                <li>Strong Decision</li>
                <li>Complex problem solver</li>
           </ul>       
         </div>
         <div>
<ul>
    <li>Creative Design</li>
    <li>Innovative</li>
    <li>Service-focused</li>

</ul>
         </div>
        </div>
     <h2>Experience</h2>
     <hr />
     <h4>Web Developer 09/2015 to 05/2019</h4>
     <h4>Luna Web Design, New York</h4>
     <ul>
         <li>Cooprate with designers to create clean interface and<br>simple,intutitive interactions and experiences</li>
         <li>Develop project concepts and maintain optimal workflow</li>
         <li>work with senior development to manage large,complex design<br> project for corporate clients.</li>
         <li>complex detaild progamming and development tasks<br> for front and public and internal website as well as</li>
    <h2>Education</h2>
        <hr />
        <p>Bachelor of Science:Computer information System-2014<br>Columbia Univercity, NY</p>
    <h2>Certifications</h2>
        <hr />
        <p>PHP Framework (certificate):zend,codeigniter,symfony<br>progamming Languages:Javascript, HTMLS. PHP OPP, CSS, SQL, MySQL.</p>
     </ul> 
            </div> 
        </div> 
    </div> 
</template>
<script>
    export default {
    name: 'CvDua',
    computed: {
        listCv() {
            return this.$store.state.listCv
        }
    }
}
</script>

<style>
#a { 
    display: flex; 
    background-color: rgb(189, 189, 189); 
    padding-left: 20px;
    margin-top: 20px; 
} 
#b { 
    background-color: white; 
    padding-left: 10px;
    width: 500px; 
} 
#c { 
    margin-right: 300px; 
    padding-left: 300px; 
} 
#d { 
    font-family: sans-serif; 
    padding-right: 35px; 
} 
#e { 
    color: rgb(255, 102, 0); 
} 
hr { 
    border: none; 
    height: 1px; 
    /* Set the hr color */ 
    color: black; /* old IE */ 
    background-color: black; /* Modern Browsers */ 
    width: 100%; 
}#a { 
    display: flex; 
    background-color: rgb(189, 189, 189); 
    padding-left: 20px; 
} 
#b { 
    background-color: white; 
    padding-left: 10px; 
} 
#c { 
    margin-right: 300px; 
    padding-left: 300px; 
} 
#d { 
    font-family: sans-serif; 
    padding-right: 35px; 
} 
#e { 
    color: rgb(255, 102, 0); 
} 
hr { 
    border: none; 
    height: 1px; 
    /* Set the hr color */ 
    color: black; /* old IE */ 
    background-color: black; /* Modern Browsers */ 
    width: 100%; 
}
</style>