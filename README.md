# web4lab4
## Membuat Layout Sederhana

### Menambahkan layout About dan Contact
Berikut proses menambahkan layout pada menu HTML:

![Gambar](screenshot/ever.pdf)

- 	Pembuatan layout sederahana untuk menu about , dibawah ini adalah codingannya. 
 
<!DOCTYPE html> 
<html lang="en"> 
<head> 
    <meta charset="UTF-8"> 
    <meta http-equiv="X-UA-Compatible" content="IE=edge"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0">     <title>About Me</title> 
    <link rel="stylesheet" href="style.css"> 
</head> 
<body> 
 
    <div id="container"> 
        <header> 
            <h1>Layout Sederhana</h1> 
            <img src="eagle.jpg"> 
        </header> 
        <nav> 
            <a href="web4lab4.html">Home</a> 
            <a href="artikel.html">Artikel</a> 
            <a href="About.html">About Me</a> 
            <a href="contact.html">Contact</a> 
        </nav> 
     
 
          
  </div> 
 
</body> 
</html> 
 
  
 
-Dibawah ini adalah tampilan about me , beserta codingannya. 
 
<!DOCTYPE html> 
<html lang="en"> 
<head> 
    <meta charset="UTF-8"> 
    <meta http-equiv="X-UA-Compatible" content="IE=edge"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0">     <title>About Me</title> 
    <link rel="stylesheet" href="style.css"> 
</head> 
<body> 
 
    <div id="container"> 
        <header> 
            <h1>Layout Sederhana</h1> 
            <img src="eagle.jpg"> 
        </header> 
        <nav> 
            <a href="web4lab4.html">Home</a> 
            <a href="artikel.html">Artikel</a>             <a href="About.html">About Me</a> 
            <a href="contact.html">Contact</a> 
        </nav> 
     
    <section id="about"> 
        <h1>SAYA EDWIN FIRMANSYAH</h1> 
        <h2>MAHASISWA<span> UNIVERSITAS PELITA BANGSA</span> </h2> 
        <table> 
            <tr> 
                <td><img src="meaina.jpg" alt="" width="100 px"></td> 
            </tr> 
            <tr> 
                <td><b>Nama Lengkap</b></td> 
                <td>:</td> 
                <td>Edwin Firmansyah Hamid</td> 
            </tr> 
            <tr> 
                <td><b>Tanggal Lahir</b></td> 
                <td>:</td> 
                <td>27 mei 1998</td> 
            </tr> 
            <tr> 
                <td><b>Alamat</b></td> 
                <td>:</td> 
                <td>Bekasi, cibarusah kota</td> 
            </tr> 
            <tr> 
                <td><b>Email</b></td> 
                <td>:</td> 
                <td>edwinfirmansyah170@gmail.com</td> 
            </tr> 
        </table>     </section> 
  </div><br><br> 
 
     
    <footer> 
        <p><a>Copyright&copy 2019 | Design By: Edwin firmansyah</a>.</p> 
    </footer> 
</body> 
</html> 
 
  
 
- 	Dibawah ini adalah layout sederhana untuk menu contact  
<!DOCTYPE html> 
<html lang="en"> 
 <head> 
    <meta charset="UTF-8"> 
    <meta http-equiv="X-UA-Compatible" content="IE=edge"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0">     <title>Layout Sederhana</title> 
    <link rel="stylesheet" href="style.css">  </head> 
  <body> 
    <div id="container"> 
        <header> 
            <h1>Layout Sederhana</h1> 
            <img src="eagle.jpg"> 
        </header> 
        <nav> 
            <a href="web4lab4.html">Home</a> 
            <a href="artikel.html">Artikel</a> 
            <a href="About.html">About Me</a> 
            <a href="contact.html">Contact</a> 
        </nav> 
        <div class="contact-section"> 
            <div class="inner-width"> 
              <h1>Get in touch with us</h1> 
              <input type="text" class="nama" placeholder="Nama"> 
              <input type="email" class="email" placeholder="Email"> 
              <textarea rows="1" placeholder="Message" class="message"></texta rea> 
            </div>   
            <button>Send</button><br> 
        </div> 
        <footer> 
            <div class="bungkus"> 
                <h3>Contact</h3> 
                <img src="one.jpg" alt=""> 
                <p>Cibarusah kota. Jl.kp.malaka Bekasi</p><br> 
                <img src="two.jpg" alt=""> 
                <p>edwinfirmansyah170@gmail.com</p><br> 
                <img src="tree.jpg" alt=""> 
                <p>0812-9248-0012</p><br> 
                 
            </div> 
             
            <p>&copy; 2021 - Universitas Pelita Bangsa</p> 
        </footer> 
    </div> 
  </body> 
</html> 
 
  

