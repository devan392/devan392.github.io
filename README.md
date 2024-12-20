# devan392.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, 
    initial-scale=1.0">
    
    <title>Portofolioo Web </title>

    *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: double;
    border: none;
    outline: none;
    font-family:'poppins',sans-serif
}

html{
    font-size: large;
}

body{
    width: 100%;
    height: 100%;
    overflow-x: hidden;
    background-color:white;
    color: white;
}

header{
    margin-top: 20px;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    width: 100%;
    padding: 1rem 9%;
    background-color: transparent;
    filter: drop-shadow(10px);
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
}

.logo{
    font-size: 3rem;
    color: white;
    font-weight: 650;
    cursor: pointer;
    transition: 1s ease;
}

.logo:hover{
    transform: rotate3d(1.1);
}
nav a{
    font-size: large;
    color: blue;
    margin-left: 3rem;
    font-weight: 500;
    transition: 1s ease;
    border-bottom: 5px solid transparent;
}

nav a:hover,
nav a.active{
    color: white;
    border-bottom: 1px solid rebeccapurple;
}
    @media(max-width:995px){
        nav{
            position: absolute;
            top: 100%;
            right: 0;
            width: 40%;
            border-left: 3px solid black;
            border-bottom: 3px solid black;
            border-bottom-left-radius: 2rem;
            padding:1rem solid;
            background-color:brown;
            border-top: 0.1rem solid brown;
        }

        nav.active{
            display:block;
            font-size: 2rem;
            margin: 3rem 0;
        }

        nav a:hover,
        nav a.active{
            padding: 1rem;
            border-radius: 0.5rem;
            padding-bottom: 0.5rem solid red
        }
    }

    section{
        min-height: 100vh;
        padding: 5rem 9% 5rem;

    }

    .home{
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 8rem;
        background-color:brown;
    }

    .home.home-content h1{
        font-size: 5rem;
        font-weight:700;
        line-height: 1.3;
    }

    span{
        color: black;
    }

    .home.content h3{
        font-size: 4rem;
        margin-bottom: 1rem;
        font-weight: 700;
    }

    .home-img{
        border-radius: 50%;
    }

    .home-img img{
        position: relative;
        width: 32vw;
    }


</head>
<body>
    <header>
        <a href="#" class="logo">Devan</a>

        <nav>
            <a href="#" class="active">Home</a>
            <a href="#" class="active">Services</a>
            <a href="#" class="active">Skills</a>
            <a href="#" class="active">Education</a>
            <a href="#" class="active">Experience</a>
            <a href="#" class="active">Contact</a>
        </nav>
    </header>
    <section class="home">
        <div class="home-img">
            <img src="/Foto/fot fot.jpg" alt="">
        </div>
        <div class="home-content">
            <h2>HALO !</h2>
            <br>
            <h3 class="typing-text"> Nama saya Devan Haidar Wirya Hidayat. Saya seorang siswa jurusan Sistem Informasi yang antusias untuk belajar lebih dalam mengenai teknologi dan bagaimana teknologi bisa digunakan untuk membantu orang lain. Saya memiliki minat besar dalam pengembangan aplikasi yang bermanfaat dan dapat memberikan solusi nyata bagi pengguna.
            </h3>
            <div class="social-icons">
                <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                <a href="#"><i class="fa-brands fa-github"></i></a>
                <a href="#"><i class="fa-brands fa-instagram"></i></a>
            </div>
            <a href="#" class="btn"></a>
        </div>
    </section>
</body>
</html>
