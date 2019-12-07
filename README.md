# cananimate
CSS Library Animation


<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- cananimate -->
    <link rel="stylesheet" href="cananimate.css">

    <!-- bootstrap -->
    <link rel="stylesheet" href="bootstrap.css">

    <title>Cananimate</title>
  </head>
  <body>
    
    <div class="jumbotron jumbotron-fluid" style="background:linear-gradient(to left, #6A0DC4, #8D18FF, #A240FC, #B850FF, #D168FF)">

        <div class="container">
            <div id="cananimated" class="text-center">
                <h1 class="text-white">Cananimate</h1>
            </div>
        </div>

        <div class="container mt-5 mb-5">

            <div class="text-center">
                <select class="custom-select">
                    <option selected>Pilih Kelas Animasi</option>
                    <option id="toRight">toRight</option>
                    <option id="toLeft">toLeft</option>
                    <option id="toBottom">toBottom</option>
                    <option id="toTop">toTop</option>
                    <option id="bounce">bounce</option>
                    <option id="fadeIn">fadeIn</option>
                    <option id="fadeOut">fadeOut</option>
                    <option id="zoomIn">zoomIn</option>
                    <option id="zoomOut">zoomOut</option>
                    <option id="spin">spin</option>
                  </select>
            </div>

        </div>

    </div>

    <div class="jumbotron jumbotron-fluid bg-white">

        <div class="container">

            <div class="row">

                <div class="col-md-6 ml-auto">
                    <div class="text-left">
                            <h3>Tentang Cananimate</h3>
                            <p>Cananimate merupakan library animasi CSS yang didesain sangat ringan dan mudah untuk digunakan. Cananimate dibuat oleh Wahyu Krisna Aji pada Bulan Desember 2019, yaitu seorang IT antusias dan fullstack web developer.</p>
                            <p>Nama File : cananimate.css</p>
                            <p>Tanggal Pembuatan : 7 Desember 2019</p>
                            <p>Tanggal Rilis : 7 Desember 2019</p>
                            <p>Versi : 1.0</p>
                            <p>Lisensi : MIT</p>
                            <p>Jenis Program : Open-Source (terbuka)</p>
                            <p>Pencipta & Hak Cipta : &copy Wahyu Krisna Aji 2019</p>
                    </div>
                </div>


                <div class="col-md-6 mr-auto">
                    <div class="text-right">
                        <h3>Tentang Pencipta Cananimate</h3>
                        <p>Pencipta dari Cananimate (Wahyu Krisna Aji) adalahseorang IT antusiast yang menekuni bidang web developer. Wahyu juga merupakan seorang fullstack web developer yangsaat ini bekerja di PT Aplikasi Untuk Bangsa sebagai frontend web developer.</p>
                        <p>facebook : <a href="https://www.facebook.com/wahyu.k.aji.96" class="text-dark">Wahyu Kun</a></p>
                    </div>
                </div>

            </div>

        </div>

    </div>

    <script src="bootstrap.js"></script>
    <script src="jquery.js"></script>

    <script>
        $(function(){
            $('#toRight').click(function(){
                $('#cananimated').removeClass("toLeft");
                $('#cananimated').removeClass("toBottom");
                $('#cananimated').removeClass("toTop");
                $('#cananimated').removeClass("bounce");
                $('#cananimated').removeClass("fadeIn");
                $('#cananimated').removeClass("fadeOut");
                $('#cananimated').removeClass("zoomIn");
                $('#cananimated').removeClass("zoomOut");
                $('#cananimated').removeClass("spin");
                $('#cananimated').addClass("toRight");
            })
        })

        $(function(){
            $('#toLeft').click(function(){
                $('#cananimated').removeClass("toRight");
                $('#cananimated').removeClass("toBottom");
                $('#cananimated').removeClass("toTop");
                $('#cananimated').removeClass("bounce");
                $('#cananimated').removeClass("fadeIn");
                $('#cananimated').removeClass("fadeOut");
                $('#cananimated').removeClass("zoomIn");
                $('#cananimated').removeClass("zoomOut");
                $('#cananimated').removeClass("spin");
                $('#cananimated').addClass("toLeft");
            })
        })

        $(function(){
            $('#toBottom').click(function(){
                $('#cananimated').removeClass("toRight");
                $('#cananimated').removeClass("toLeft");
                $('#cananimated').removeClass("toTop");
                $('#cananimated').removeClass("bounce");
                $('#cananimated').removeClass("fadeIn");
                $('#cananimated').removeClass("fadeOut");
                $('#cananimated').removeClass("zoomIn");
                $('#cananimated').removeClass("zoomOut");
                $('#cananimated').removeClass("spin");
                $('#cananimated').addClass("toBottom");
            })
        })

        $(function(){
            $('#toTop').click(function(){
                $('#cananimated').removeClass("toRight");
                $('#cananimated').removeClass("toBottom");
                $('#cananimated').removeClass("toLeft");
                $('#cananimated').removeClass("bounce");
                $('#cananimated').removeClass("fadeIn");
                $('#cananimated').removeClass("fadeOut");
                $('#cananimated').removeClass("zoomIn");
                $('#cananimated').removeClass("zoomOut");
                $('#cananimated').removeClass("spin");
                $('#cananimated').addClass("toTop");
            })
        })

        $(function(){
            $('#bounce').click(function(){
                $('#cananimated').removeClass("toRight");
                $('#cananimated').removeClass("toBottom");
                $('#cananimated').removeClass("toTop");
                $('#cananimated').removeClass("toLeft");
                $('#cananimated').removeClass("fadeIn");
                $('#cananimated').removeClass("fadeOut");
                $('#cananimated').removeClass("zoomIn");
                $('#cananimated').removeClass("zoomOut");
                $('#cananimated').removeClass("spin");
                $('#cananimated').addClass("bounce");
            })
        })

        $(function(){
            $('#fadeIn').click(function(){
                $('#cananimated').removeClass("toRight");
                $('#cananimated').removeClass("toBottom");
                $('#cananimated').removeClass("toTop");
                $('#cananimated').removeClass("bounce");
                $('#cananimated').removeClass("toLeft");
                $('#cananimated').removeClass("fadeOut");
                $('#cananimated').removeClass("zoomIn");
                $('#cananimated').removeClass("zoomOut");
                $('#cananimated').removeClass("spin");
                $('#cananimated').addClass("fadeIn");
            })
        })

        $(function(){
            $('#fadeOut').click(function(){
                $('#cananimated').removeClass("toRight");
                $('#cananimated').removeClass("toBottom");
                $('#cananimated').removeClass("toTop");
                $('#cananimated').removeClass("bounce");
                $('#cananimated').removeClass("fadeIn");
                $('#cananimated').removeClass("toLeft");
                $('#cananimated').removeClass("zoomIn");
                $('#cananimated').removeClass("zoomOut");
                $('#cananimated').removeClass("spin");
                $('#cananimated').addClass("fadeOut");
            })
        })

        $(function(){
            $('#zoomIn').click(function(){
                $('#cananimated').removeClass("toRight");
                $('#cananimated').removeClass("toBottom");
                $('#cananimated').removeClass("toTop");
                $('#cananimated').removeClass("bounce");
                $('#cananimated').removeClass("fadeIn");
                $('#cananimated').removeClass("fadeOut");
                $('#cananimated').removeClass("toLeft");
                $('#cananimated').removeClass("zoomOut");
                $('#cananimated').removeClass("spin");
                $('#cananimated').addClass("zoomIn");
            })
        })

        $(function(){
            $('#zoomOut').click(function(){
                $('#cananimated').removeClass("toRight");
                $('#cananimated').removeClass("toBottom");
                $('#cananimated').removeClass("toTop");
                $('#cananimated').removeClass("bounce");
                $('#cananimated').removeClass("fadeIn");
                $('#cananimated').removeClass("fadeOut");
                $('#cananimated').removeClass("zoomIn");
                $('#cananimated').removeClass("toLeft");
                $('#cananimated').removeClass("spin");
                $('#cananimated').addClass("zoomOut");
            })
        })

        $(function(){
            $('#spin').click(function(){
                $('#cananimated').removeClass("toRight");
                $('#cananimated').removeClass("toBottom");
                $('#cananimated').removeClass("toTop");
                $('#cananimated').removeClass("bounce");
                $('#cananimated').removeClass("fadeIn");
                $('#cananimated').removeClass("fadeOut");
                $('#cananimated').removeClass("zoomIn");
                $('#cananimated').removeClass("zoomOut");
                $('#cananimated').removeClass("toLeft");
                $('#cananimated').addClass("spin");
            })
        })

    </script>

  </body>
</html>
