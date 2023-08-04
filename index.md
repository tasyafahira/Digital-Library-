# Digital-Library-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Perpustakaan Online</title>
    <style>
        * {
            padding: 0;
            margin: 0;
        }

        body {
            width: 100%;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            background-color: #dedede;
        }

        .marquee {
            background-color: #ffffffd7;
            color: #0006ff;
        }

        p {
            margin-bottom: 20px;
            line-height: 1.5em;
        }

        h2 {
            font-size: 17px;
            font-weight: 600;
        }

        h3 {
            font: #fff;
            font-size: 17px;
            padding-bottom: 10px;
            border-bottom: 4px solid #fff;
        }

        h4 {
            font: white;
            padding-top: 10px;
            text-align: left;
            font-size: 15px;
        }

        /* Tambahkan CSS lainnya di sini */

        /*Halaman Buku*/

        .buku {
            padding: 0 6px;
            margin-right: 10px;
            float: left;
            border: 1px solid #dedede;
            width: 23%;
        }

        .gallery:hover {}

        .foto img {
            padding: 5px 0 5px 0;
            width: 100%;
            height: 250px;
        }

        .judul {
            font-size: 13px;
            font-weight: 600;
            padding: 0 0 3px 0;
            text-align: left;
        }

        .penulis {
            font-size: 10px;
            padding-bottom: 5px;
        }

        /* Tambahkan CSS lainnya di sini */

        /* Main */

        .left {
            width: 280px;
            color: #fff;
            border: 1px solid #dedede;
            padding: 10px;
            margin: 10px 10px 10px 0px;
            float: left;
            background-color: #281e5a;
        }

        .left ul {
            list-style-type: none;
        }

        .left ul li {
            display: block;
        }

        .left ul li a {
            display: block;
            font-size: 17px;
            border-bottom: 1px dotted #d4d2db;
            margin-bottom: 10px;
            padding: 10px 5px;
            font: #64bed4;
            color: #fff;
        }

        .left ul li a:hover {
            color: #ca1414;
        }

        .middle {
            width: 500px;
            border: 1px solid #dedede;
            padding: 5px;
            margin: 10px;
            float: left;
        }

    .header {
    position: relative;
    text-align: center;
}

.header::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url("file:///C:/Users/Tasya%20Fahira/OneDrive/Documents/project%20perpustakaan/templates/buku3.jpg");
    background-size: cover;
    opacity: 0.5; /* Sesuaikan kebutuhan Anda */
    z-index: -1;
}

.header h1 {
    position: relative;
    color: #ffffff;
    font-size: 24px;
    font-weight: bold;
    padding: 20px;
}

        .middle a {
            font-weight: bold;
        }

        .middle2 {
            width: 790px;
            height: 100%;
            padding: 5px;
            margin: 10px;
            float: left;
        }

        .middle2 a {
            font-weight: bold;
        }

        .right {
            width: 280px;
            color: #fff;
            border: 1px solid #dedede;
            padding: 10px;
            margin: 10px 0 10px 10px;
            float: right;
            background-color: #281e5a;
        }

        .right ul {
            list-style-type: none;
        }

        .right ul li {
            display: block;
        }

        .right ul li a {
            display: block;
            font-size: 17px;
            border-bottom: 1px dotted #d4d2db;
            margin-bottom: 10px;
            padding: 10px 5px;
            color: #fff;
        }

        .right ul li a:hover {
            color: #ca1414;
        }

        #footer {
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            font-size: 20px;
            color: #6813c9;
            clear: both;
            border: 1px solid #dedede;
            padding: 15px;
        }

        @media screen and (max-width: 1140px) {
            .container {
                width: 100%;
            }

            .left {
                width: 25%;
                background: #0c7575d7;
            }

            .middle {
                width: 68%;
                float: right;
            }

            .middle2 {
                width: 90%;
                float: right;
            }

            .right {
                clear: both;
                padding: 1% 4%;
                width: auto;
                float: none;
                background: #0c7575d7;
            }
        }

        @media screen and (max-width: 780px) {
            .header,
            .footer {
                text-align: center;
            }

            .left {
                width: auto;
                float: none;
            }

            .middle {
                width: auto;
                float: none;
            }

            .right {
                width: auto;
                float: none;
            }
        }
    </style>
</head>

<head>
    <style>
        .header h1 {
	    font-family: "Times New Roman", Times, serif;
            font-weight: bold;
            font-style: italic;
            font-size: 40px; /* Sesuaikan ukuran font sesuai kebutuhan Anda */
        }
    </style>

<body>
    <div id="container">
        <div class="header">
            <img src="C:\Users\Tasya Fahira\OneDrive\Documents\project perpustakaan\templates\logo.png" width="125" height="125">
            <h1>Perpustakaan TEP UNPAD</h1>
      <style>
            .header {
                 text-align: center;
          }  
      </style>
        </div>

        <div class="main">
            <div class="left">
                <h3 align="center">MENU</h3>
                <ul>
                    <li><a href="C:/Users/Tasya%20Fahira/OneDrive/Documents/project%20perpustakaan%203/templates/login.html">Login</a></li>
                    <li><a href="file:///C:/Users/Tasya%20Fahira/OneDrive/Documents/project%20perpustakaan%203/templates/tambah_anggota.html">Tambah Anggota</a></li>
                    <li><a href="C:\Users\Tasya Fahira\OneDrive\Documents\project perpustakaan 3\templates\daftar_buku.html">Daftar Buku</a></li>
                    <li><a href="file:///C:/Users/Tasya%20Fahira/OneDrive/Documents/project%20perpustakaan%203/templates/pinjam_buku.html">Pinjam Buku</a></li>
                    <li><a href="C:\Users\Tasya Fahira\OneDrive\Documents\project perpustakaan 3\templates\kembalikan_buku.html">Kembalikan Buku</a></li>
                </ul>
            </div>

            <div class="middle">
                <h3 align="center">Artikel/Berita/Buku Terbaru</h3>
                <h2 align="center">Buku:The Chronicles Of Narnia - C.S Lewis </h2><br>
                <div align="center">
                    <img src="C:\Users\Tasya Fahira\OneDrive\Documents\project perpustakaan\templates\narnia.jpg"width="240">
                </div>
                
<p style="text-align: center;"><a href="#" onclick="openNewWindow();">Baca Selengkapnya >></a></p>

<script>
function openNewWindow() {
    window.open('halaman_baru.html', '_blank');
}
</script>
            </div>

            <div class="right">
                <h3 align="center">BUKU TERPOPULER</h3>
                <ul>
                    <li><a href="file:///C:/Users/Tasya%20Fahira/OneDrive/Documents/project%20perpustakaan%203/templates/rekomendasi_buku.html">Fantasy</a></li>
                    <li><a href="file:///C:/Users/Tasya%20Fahira/OneDrive/Documents/project%20perpustakaan%203/templates/rekomen_buku.html">Fiction</a></li>
                    <li><a href="file:///C:/Users/Tasya%20Fahira/OneDrive/Documents/project%20perpustakaan%203/templates/rekomendasi_bukubuku.html">Coming-Of-Age</a></li>
                </ul>
            </div>
        </div>

        <div id="footer" align="center">
            <p>&copy; 2023 Perpustakaan TEP UNPAD. All Rights Reserved.</p>
        </div>
    </div>
</body>
</html>
