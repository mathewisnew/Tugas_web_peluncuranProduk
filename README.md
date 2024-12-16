Notes 
=========

Notes Onepage Free Comming Soon HTML5 Template .
Download Free Wordpress Version From : http://www.themefisher.com/items/notes-coming-soon-wordpress-theme/ . 


ini untuk tugas pemrogramman web 1
saya tambah countdown mulai
<!-- Tambahkan jQuery -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <!-- Tambahkan Plugin Countdown -->
      
    <script src="path/to/jquery.lwtCountdown-1.0.js"></script>
   letak: sebelum <!-- </head> -->
lalu
              <!-- Countdown Initialization -->

<script>
    $(document).ready(function () {
        $('#countdown_dashboard').countDown({
            targetDate: {
                day: 31,
                month: 12,
                year: 2024,
                hour: 23,
                min: 59,
                sec: 59,
                utc: true
            },
            onComplete: function () {
                alert('Countdown selesai!');
            }
        });
    });
</script>

letak:
setelah header close di bagian countdown, dan
sebelum about start nikmati fitur terbaik
(intinya sebelum </body>)


ketemu template dari:
https://www.jagoanhosting.com/blog/template-website-html-css/#notes:~:text=template%2Dagency%2D2017/.-,Notes,-Salah%20satu%20fungsi > lalu ke > https://themewagon.com/themes/notes-free-responsive-product-launching-landing-page-template/.
