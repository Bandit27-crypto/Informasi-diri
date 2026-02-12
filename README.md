<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Biodata & Refleksi - Advanced</title>

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css" rel="stylesheet">

<style>
    body {
        background: linear-gradient(135deg, #141e30, #243b55);
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        color: white;
    }

    .glass-card {
        background: rgba(255, 255, 255, 0.08);
        backdrop-filter: blur(15px);
        border-radius: 20px;
        box-shadow: 0 10px 30px rgba(0,0,0,0.4);
        transition: 0.4s ease;
        height: 100%;
    }

    .glass-card:hover {
        transform: translateY(-8px);
    }

    .profile-img {
        width: 100%;
        aspect-ratio: 1/1;
        object-fit: cover;
        border-radius: 20px;
        border: 4px solid #0d6efd;
    }

    .section-title {
        font-weight: bold;
        letter-spacing: 1px;
        text-transform: uppercase;
    }

    .skill-bar {
        height: 10px;
        border-radius: 10px;
    }

    .reflection-box {
        background: rgba(255, 255, 255, 0.1);
        border-left: 6px solid #0d6efd;
        border-radius: 20px;
        backdrop-filter: blur(10px);
    }

    .btn-custom {
        border-radius: 30px;
        padding: 8px 20px;
    }

    footer {
        font-size: 14px;
        opacity: 0.7;
    }

    .fade-in {
        animation: fadeIn 1.5s ease;
    }

    @keyframes fadeIn {
        from {opacity: 0; transform: translateY(20px);}
        to {opacity: 1; transform: translateY(0);}
    }
</style>
</head>

<body>

<div class="container py-5 fade-in">

    <div class="row g-4 align-items-stretch">

        <div class="col-md-4 d-flex">
            <div class="glass-card p-3 w-100 text-center">
                <img src="C:\Users\berna\Downloads\foto-rio.jpeg" alt="Foto Bernardus" class="profile-img mb-3">
                <h4 class="fw-bold">Bernardus Satrio Cahyono</h4>
                <p class="text-info">Calon Web Developer</p>

                <button class="btn btn-primary btn-custom"
                        data-bs-toggle="modal"
                        data-bs-target="#contactModal">
                    <i class="bi bi-envelope-fill"></i> Hubungi Saya
                </button>
            </div>
        </div>

        <div class="col-md-8 d-flex">
            <div class="glass-card p-4 w-100">
                <h4 class="section-title text-primary mb-3">
                    <i class="bi bi-person-badge-fill"></i> Informasi Diri
                </h4>

                <p style="text-align: justify;">
                     Nama saya <strong>Bernardus Satrio Cahyono</strong>, lahir pada tanggal <strong>27 April 2009</strong> di Jakarta. 
                    Saya adalah anak pertama dari tiga bersaudara. Sebagai anak sulung, saya berusaha menjadi pribadi yang 
                    bertanggung jawab, disiplin, dan mampu memberikan contoh yang baik bagi adik-adik saya dalam kehidupan sehari-hari.
                </p>

                <p style="text-align: justify;">
                    Saya memiliki ketertarikan besar terhadap dunia teknologi, khususnya dalam bidang pengembangan website 
                    dan desain antarmuka. Saya senang mempelajari HTML, CSS, dan Bootstrap karena framework ini membantu 
                    saya memahami bagaimana membangun tampilan website yang responsif, modern, dan terstruktur dengan baik.
                </p>

                <p style="text-align: justify;">
                    Bagi saya, teknologi bukan hanya sekadar pelajaran sekolah, tetapi juga keterampilan masa depan. 
                    Saya terus berlatih meningkatkan kemampuan coding, berpikir logis, serta kreativitas desain agar 
                    dapat menjadi seorang Web Developer profesional yang mampu menciptakan karya yang bermanfaat 
                    dan membanggakan keluarga saya.
                </p>

                <hr class="border-light">

                <h5 class="mt-3">Keahlian</h5>

                <p>HTML</p>
                <div class="progress skill-bar mb-2">
                    <div class="progress-bar bg-primary" style="width: 85%"></div>
                </div>

                <p>CSS</p>
                <div class="progress skill-bar mb-2">
                    <div class="progress-bar bg-info" style="width: 80%"></div>
                </div>

                <p>Bootstrap</p>
                <div class="progress skill-bar">
                    <div class="progress-bar bg-success" style="width: 75%"></div>
                </div>
            </div>
        </div>

    </div>

</div>

<div class="container pb-5 fade-in">
    <div class="reflection-box p-5 text-white">
        <h3 class="text-center text-primary fw-bold mb-4">
            <i class="bi bi-lightbulb-fill"></i> Refleksi Diri
        </h3>

        <p style="text-align: justify;">
             Pada Ulangan Harian 1, saya memperoleh nilai yang kurang memuaskan karena masih menulis kode HTML dan CSS secara manual tanpa memanfaatkan Bootstrap. 
            Kesalahan utama saya adalah tidak menggunakan <code>container</code> di dalam <code>div class</code>, sehingga tata letak menjadi tidak terstruktur dan kurang responsif.Saya tahu bahwa kesalahan seperti ini bisa terjadi karena terlalu mengandalkan kode yang sebelumnya pernah saya buat dan tidak belajar cara menggunakan <code>bootstrap</code> dengan benar.
        </p>

        <p style="text-align: justify;">
             Dari pengalaman tersebut, saya menyadari bahwa Bootstrap bukan sekadar alat untuk memperindah tampilan, 
            tetapi merupakan sistem yang membantu membangun struktur layout secara efisien. Materi ini juga sebnarnya sangat berguna bagi kita agar bisa mempermudah penulisan dan meminimalisir kesalahan.

        <p style="text-align: justify;">
             Nilai yang kurang baik tersebut menjadi motivasi bagi saya untuk belajar lebih dalam tentang struktur dasar 
            seperti <code>container</code>, <code>row</code>, dan <code>col</code>. Saya memahami bahwa kesalahan kecil dalam struktur 
            dapat berdampak besar pada hasil akhir. Ke depannya, saya berkomitmen untuk lebih teliti, 
            memanfaatkan framework dengan benar, dan menghasilkan karya yang lebih profesional.
        </p>
        </p>
    </div>
</div>

<footer class="text-center pb-3">
    © 2026 Bernardus Satrio Cahyono | Future Web Developer 
</footer>

<div class="modal fade" id="contactModal" tabindex="-1">
  <div class="modal-dialog">
    <div class="modal-content bg-dark text-white">
      <div class="modal-header border-secondary">
        <h5 class="modal-title">Hubungi Saya</h5>
        <button type="button" class="btn-close btn-close-white" data-bs-dismiss="modal"></button>
      </div>
      <div class="modal-body">
        <form id="contactForm">
          <div class="mb-3">
            <label class="form-label">Nama</label>
            <input type="text" class="form-control" id="nama" required>
          </div>
          <div class="mb-3">
            <label class="form-label">Pesan</label>
            <textarea class="form-control" rows="3" id="pesan" required></textarea>
          </div>
          <button type="submit" class="btn btn-primary w-100">Kirim</button>
        </form>
      </div>
    </div>
  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

<script>
document.getElementById("contactForm").addEventListener("submit", function(event){
    event.preventDefault();

    let nama = document.getElementById("nama").value;
    let pesan = document.getElementById("pesan").value;

    alert("Terima kasih " + nama + " \nPesan Anda berhasil dikirim!");

    document.getElementById("contactForm").reset();

    let modal = bootstrap.Modal.getInstance(document.getElementById('contactModal'));
    modal.hide();
});
</script>

</body>
</html>
